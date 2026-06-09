# Backlog S3 — GET409-DemDem

Équipe : GET409-DemDem
Séance : S2 → S3 — User Stories prêtes à construire
Projet : DemDem — Planification de trajets multimodaux, Région de Dakar
Date : 08/06/2026

---

## HMW Définitif

> Comment pourrions-nous permettre à Moussa de voir en moins de 10 secondes, depuis son smartphone, quelle combinaison bus/TER/taxi lui coûte le moins cher et lui prend le moins de temps pour aller de Keur Massar au centre de Dakar, afin qu'il parte en confiance sans avoir à négocier à l'aveugle ?

---

## User Stories — À Construire en S3

**US-01 — Comparaison multimodale instantanée**

En tant que Moussa,
je veux saisir mon point de départ et ma destination,
afin de voir en moins de 10 secondes le coût et la durée estimés pour le bus, le TER et le taxi côte à côte.

Critères d'acceptation :
- [ ] Affichage de 3 modes minimum (bus, TER, taxi)
- [ ] Résultat visible en < 10 secondes
- [ ] Prix affiché en fourchette (ex. 200–350 FCFA)
- [ ] Durée affichée en minutes
- [ ] Pas de compte requis

**Priorité :** 🔴 Must Have — Score alignement HMW : 6/6

---

**US-02 — Interface 2 champs, zéro friction**

En tant que Moussa (50 ans, usage WhatsApp dominant),
je veux accéder au résultat en 2 actions maximum (départ + destination),
afin de ne pas abandonner l'app avant d'avoir l'information.

Critères d'acceptation :
- [ ] Écran principal : 2 champs de saisie + bouton Comparer
- [ ] Suggestions de quartiers connus (Keur Massar, Plateau, Yoff…)
- [ ] Résultat sans redirection vers un autre écran
- [ ] Bouton retour visible

**Priorité :** 🔴 Must Have — Score alignement HMW : 6/6

---

**US-03 — Indication de fiabilité de la donnée**

En tant que Moussa,
je veux savoir si l'estimation est récente ou approximative,
afin de calibrer ma confiance avant de partir.

Critères d'acceptation :
- [ ] Indicateur visible (ex. "Données vérifiées ce matin" / "Estimation basée sur les 7 derniers jours")
- [ ] Message clair si aucune donnée récente disponible
- [ ] Pas de fausse précision (pas d'affichage "exact" si données incertaines)

**Priorité :** 🟡 Should Have — Score alignement HMW : 5/6

---

**US-04 — Résultats en français simple + noms Wolof**

En tant que Moussa,
je veux que les noms de lignes et de quartiers soient en français courant ou en Wolof,
afin de reconnaître immédiatement mes arrêts habituels.

Critères d'acceptation :
- [ ] Nom de quartier affiché tel qu'utilisé localement (ex. "Keur Massar" pas "KM Zone 4")
- [ ] Nom de ligne en clair (ex. "Bus ligne Pikine–Plateau" pas "L27")
- [ ] Pas d'abréviations non expliquées

**Priorité :** 🟡 Should Have — Score alignement HMW : 5/6

---

## User Stories — Reportées Post-MVP

**US-05 — Alerte proactive matin**

En tant que Moussa, je veux recevoir une notification avant 7h avec le meilleur trajet du jour.
**Raison du report :** Nécessite permissions de notification + données temps réel — hors scope S3.

**US-06 — Données communautaires (crowdsourcing)**

En tant que voyageur, je veux signaler le prix payé pour enrichir la base de données.
**Raison du report :** Requiert modération, gestion des faux signalements — roadmap S4+.

**US-07 — Bot WhatsApp**

En tant que Moussa, je veux obtenir la comparaison via WhatsApp sans ouvrir une app.
**Raison du report :** Décision canal (app vs bot) à valider par test utilisateur S3 — H4.

---

## Ordre de Construction S3

| Ordre | US | Justification |
|---|---|---|
| 1 | US-01 | Cœur du produit — sans elle, rien n'existe |
| 2 | US-02 | Conditionne l'adoption — sans elle, US-01 est inaccessible |
| 3 | US-03 | Crédibilité de la donnée — critique pour la confiance (H2) |
| 4 | US-04 | Accessibilité — si le temps le permet en S3 |
