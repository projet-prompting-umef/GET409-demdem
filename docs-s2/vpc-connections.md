# Connexions 6 Chapeaux → VPC — GET409-DemDem

Équipe : GET409-DemDem
Séance : S2 — Traçabilité Design Thinking → Value Proposition
Date : 08/06/2026

---

## Profil Client — Origines

### Jobs To Be Done

| Job | Chapeau d'origine | Citation source |
|---|---|---|
| J1 — Rejoindre Dakar à l'heure et dans son budget | Chapeau Blanc | "Les voyageurs passent en moyenne 2 à 3h par jour dans les transports" |
| J2 — Décider quel transport avant de partir | Chapeau Rouge | "Anxiété chronique avant chaque départ : ne pas savoir combien coûtera le trajet" |
| J3 — Maintenir sa ponctualité | Chapeau Rouge | "Il éprouve de la honte lorsqu'il rate un rendez-vous à cause d'un retard de transport" |
| J4 — Maîtriser son budget transport | Chapeau Blanc | "Le prix varie selon l'heure, la direction et le chauffeur : aucun tarif officiel affiché" |

### Pains

| Pain | Chapeau d'origine | Citation source |
|---|---|---|
| P1 — Incertitude coût avant le départ | Chapeau Noir | "Les estimations sans source fiable perdent toute crédibilité dès le premier trajet raté" |
| P2 — Tarification opaque | Chapeau Blanc | "Aucun tarif officiel affiché, tout se négocie à l'oral" |
| P3 — 2 à 3h perdues par jour | Chapeau Blanc | "Les voyageurs de Keur Massar passent en moyenne 2 à 3h par jour dans les transports" |
| P4 — Changement de transport sans info | Chapeau Vert | "Et si les voyageurs signalaient en temps réel la fréquence des véhicules ?" |
| P5 — Interface complexe = abandon | Chapeau Noir | "Un parcours avec plus de 2 écrans avant l'info risque d'être abandonné immédiatement" |

### Gains

| Gain | Chapeau d'origine | Citation source |
|---|---|---|
| G1 — Estimation coût + temps avant départ | Chapeau Jaune | "Une estimation même approximative suffit à débloquer la décision de départ" |
| G2 — Comparaison multimodale instantanée | Chapeau Jaune | "Le TER est sous-utilisé : une comparaison visible pourrait réorienter massivement la demande" |
| G3 — Alerte de changement en cours de trajet | Chapeau Vert | "Et si l'app envoyait une alerte proactive le matin avant le départ ?" |
| G4 — Interface en langue accessible | Chapeau Rouge | "Fierté tacite de maîtriser les trajets — l'app complète le savoir local, ne le remplace pas" |

---

## Proposition de Valeur — Origines

### Pain Relievers

| Pain Reliever | Pain adressé | Chapeau d'origine |
|---|---|---|
| PR1 — Fourchette coût + durée en < 10s | P1 | Chapeau Jaune + Chapeau Bleu (critère de démo : 10 secondes) |
| PR2 — Tarifs communautaires agrégés | P2 | Chapeau Vert (données communautaires à la Waze) |
| PR3 — Notifications de changement | P4 | Chapeau Vert (alerte proactive matin) |
| PR4 — 2 champs max, zéro compte | P5 | Chapeau Noir (risque d'abandon si trop d'étapes) |

### Gain Creators

| Gain Creator | Gain adressé | Chapeau d'origine |
|---|---|---|
| GC1 — Comparaison 3 modes côte à côte | G2 | Chapeau Jaune (TER sous-utilisé faute de comparaison visible) |
| GC2 — Indicateur de fiabilité de la donnée | G1 | Chapeau Noir (données imparfaites → transparence nécessaire) |
| GC3 — Alerte géolocalisée (phase 2) | G3 | Chapeau Vert (alerte proactive déclenchée sans action de l'utilisateur) |
| GC4 — Français simple + noms Wolof | G4 | Chapeau Rouge (respect du savoir local, pas de jargon technique) |

---

## Éléments Non Tracés

- "Système de notation des chauffeurs" → Non tracé — idée émergente, à valider en interview S3 ou déplacer en roadmap
- "Version USSD `*384#`" → Chapeau Vert (idée créative) mais éliminée en contraintes MVP — reporter post-MVP

---

## Synthèse de Cohérence

**Alignement :** Fort

**Tension principale :** Le Chapeau Vert a généré plusieurs idées créatives (USSD, données communautaires, bot WhatsApp) qui enrichissent le VPC mais dépassent le scope MVP S3. Risque de scope creep si l'équipe tente de tout construire.

**Recommandation :** Figer le MVP S3 sur PR1 + PR4 + GC1 uniquement — les autres Pain Relievers et Gain Creators passent en roadmap post-MVP et sont documentés dans backlog-s3.md avec statut REPORTER.
