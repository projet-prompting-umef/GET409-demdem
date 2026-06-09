# Métriques de Succès S6 — GET409-DemDem

Équipe : GET409-DemDem
Séance : S2 — Définition des critères de réussite
Projet : DemDem — Planification de trajets multimodaux, Région de Dakar
Date : 08/06/2026

---

## Métrique Polaire (North Star)

**Nombre de décisions de départ prises en confiance grâce à DemDem**

Définition opérationnelle : un utilisateur ouvre l'app, obtient une comparaison, et part effectivement (sans renoncer).
Cible S6 : 5 trajets validés en démo live par des utilisateurs réels.

---

## Métriques Primaires (mesurées en démo S6)

| # | Métrique | Définition | Cible S6 | Source |
|---|---|---|---|---|
| M1 | Temps jusqu'au résultat | Durée entre ouverture de l'app et affichage de la comparaison | < 10 secondes | Chronomètre démo |
| M2 | Taux de complétion sans aide | % d'utilisateurs qui obtiennent un résultat sans assistance lors du test | ≥ 80% (4/5) | Test utilisateur S3 |
| M3 | Taux de confiance déclarée | % d'utilisateurs qui disent "je partirais sur la base de cette info" | ≥ 60% (3/5) | Question post-test |
| M4 | Précision estimation prix | Écart entre prix affiché et prix réel constaté terrain | ≤ ±25% | Validation terrain S3 |

---

## Métriques Secondaires (contexte et impact)

| # | Métrique | Définition | Cible S6 |
|---|---|---|---|
| M5 | Modes comparés | Nombre de modes affichés simultanément (bus / TER / taxi) | 3 modes minimum |
| M6 | Couverture de trajets | Nombre de trajets Keur Massar → destinations testés et fonctionnels | ≥ 3 trajets |
| M7 | Adoption TER | % d'utilisateurs qui choisissent le TER après l'avoir vu comparé | Mesure indicative |
| M8 | Satisfaction UX | Score NPS simplifié (0-10 : "recommanderiez-vous cette app ?") | ≥ 7/10 |

---

## Critère de Réussite Global S6

> La démo DemDem est réussie si : (1) Moussa ou un utilisateur équivalent obtient une comparaison en moins de 10 secondes, (2) déclare qu'il partirait sur la base de l'info affichée, (3) sans avoir reçu d'aide pendant le test.

---

## Ce Qu'on Ne Mesure PAS en S6

- Nombre d'utilisateurs actifs (pas encore en production)
- Revenus ou modèle économique (hors scope cours)
- Précision GPS temps réel (données non disponibles en MVP)
