# Hypothèses à Valider en S3 — GET409-DemDem

Équipe : GET409-DemDem
Séance : S2 — Issues des 6 Chapeaux (Chapeau Noir + Synthèse Bleu)
Projet : DemDem — Planification de trajets multimodaux, Région de Dakar
Date : 08/06/2026

---

## Hypothèses Critiques (bloqueuses si fausses)

**H1 — Hypothèse de déclenchement**

**Énoncé :** Moussa consulte une app de trajet AVANT de partir de chez lui, pas en cours de route.
**Risque si fausse :** Le produit est conçu pour le mauvais moment d'usage — toute l'UX est à revoir.
**Test S3 :** Observation terrain : à quelle étape du déplacement Moussa sort-il son téléphone ?
**Critère de validation :** 3 utilisateurs sur 5 consultent l'app avant de quitter leur domicile.

**H2 — Hypothèse de confiance dans les données**

**Énoncé :** Une fourchette de prix approximative suffit à Moussa pour prendre sa décision — il n'a pas besoin d'un prix exact.
**Risque si fausse :** L'app génère de la méfiance si le prix réel s'écarte de l'estimation → abandon après 1 utilisation.
**Test S3 :** Prototype papier avec 3 scénarios de prix (exact / fourchette / estimation large) → lequel déclenche la confiance ?
**Critère de validation :** La fourchette ±20% est jugée "suffisante pour partir" par 4 utilisateurs sur 5.

**H3 — Hypothèse d'accessibilité interface**

**Énoncé :** Moussa peut utiliser l'app sans assistance dès la première ouverture (pas d'onboarding nécessaire).
**Risque si fausse :** Le produit ne scale pas — chaque nouvel utilisateur a besoin d'aide humaine.
**Test S3 :** Test utilisateur non assisté avec prototype Figma ou Flutter : Moussa complète un trajet sans aide en moins de 2 minutes.
**Critère de validation :** 0 abandon sur l'écran principal lors du test non assisté.

---

## Hypothèses Secondaires (importantes mais non bloqueuses)

**H4 — Hypothèse de canal**

**Énoncé :** Une app mobile Flutter est préférable à un bot WhatsApp pour le profil Moussa.
**Risque si fausse :** L'investissement Flutter est mal orienté — un bot WhatsApp aurait un taux d'adoption 3× supérieur.
**Test S3 :** Test comparatif rapide sur 5 utilisateurs : app Flutter vs maquette bot WhatsApp — lequel préfèrent-ils ?
**Critère de validation :** 3 utilisateurs sur 5 choisissent spontanément l'app Flutter pour leur trajet du lendemain.

**H5 — Hypothèse TER**

**Énoncé :** Les voyageurs de banlieue ne prennent pas le TER faute d'information, pas faute d'envie.
**Risque si fausse :** Le TER est connu mais trop cher ou mal desservi — l'afficher ne changera pas les comportements.
**Test S3 :** Question directe en interview : "Avez-vous déjà pris le TER ? Pourquoi pas ?" suivi d'un test de comparaison TER vs taxi en direct.
**Critère de validation :** Au moins 2 utilisateurs sur 5 disent qu'ils prendraient le TER si l'app leur montrait que c'est plus rapide.

---

## Tableau de Priorisation

| Hypothèse | Criticité | Coût du test | Priorité S3 |
|---|---|---|---|
| H1 — Moment d'usage | 🔴 Bloqueur | Faible (observation terrain) | 1 |
| H2 — Confiance données | 🔴 Bloqueur | Faible (prototype papier) | 2 |
| H3 — Accessibilité interface | 🔴 Bloqueur | Moyen (test Figma) | 3 |
| H4 — Canal app vs WhatsApp | 🟡 Important | Moyen (test comparatif) | 4 |
| H5 — Adoption TER | 🟡 Important | Faible (interview) | 5 |
