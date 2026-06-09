# Value Proposition Canvas — GET409-DemDem

Équipe : GET409-DemDem
Séance : S2 — Value Proposition Design
Projet : DemDem — Planification de trajets multimodaux, Région de Dakar
Date : 08/06/2026

---

## Profil Client — Moussa Fall

### Jobs To Be Done

| # | Job | Type |
|---|---|---|
| J1 | Se rendre de Keur Massar au centre de Dakar à l'heure et dans son budget | Fonctionnel |
| J2 | Décider quel transport prendre avant de quitter son domicile | Fonctionnel |
| J3 | Maintenir sa réputation de ponctualité auprès de sa famille et de son employeur | Social |
| J4 | Maîtriser son budget transport mensuel sans mauvaises surprises | Fonctionnel |

### Pains

| # | Pain | Intensité |
|---|---|---|
| P1 | Ne connaît pas le coût estimé du trajet avant de partir → renonce parfois à sortir | ★★★★★ |
| P2 | Tarification opaque et variable selon le mode, l'heure et le chauffeur | ★★★★★ |
| P3 | Perd 2 à 3h par jour dans les transports sans pouvoir anticiper | ★★★★☆ |
| P4 | Doit changer de transport en cours de route sans information pour décider au bon moment | ★★★★☆ |
| P5 | Interface mobile complexe → abandon si plus de 2 écrans avant l'info | ★★★☆☆ |

### Gains

| # | Gain | Priorité |
|---|---|---|
| G1 | Connaître coût + durée estimés avant de partir pour décider en confiance | ★★★★★ |
| G2 | Comparer bus, TER et taxi en un coup d'œil selon sa situation du moment | ★★★★★ |
| G3 | Être alerté au bon moment pour changer de transport en cours de trajet | ★★★★☆ |
| G4 | Interface simple, en français courant ou Wolof, sans jargon | ★★★★☆ |

---

## Proposition de Valeur — DemDem

### Produits & Services

- Application mobile Flutter (Android)
- Moteur de comparaison multimodale : bus / Tata / car rapide / TER / taxi
- Base de données tarifaires enrichie par la communauté
- (Roadmap) Bot WhatsApp et canal USSD pour usage sans data

### Pain Relievers

| # | Pain adressé | Comment DemDem le soulage |
|---|---|---|
| PR1 | P1 — Incertitude avant le départ | Affiche une fourchette coût + durée en < 10 secondes, même sans données temps réel |
| PR2 | P2 — Tarification opaque | Agrège les tarifs déclarés communautairement et les met à jour régulièrement |
| PR3 | P4 — Décision de changement | Notifications proactives si un mode plus rapide devient disponible en cours de trajet |
| PR4 | P5 — Interface trop complexe | 2 champs max (départ / destination) → résultat immédiat, zéro compte requis |

### Gain Creators

| # | Gain adressé | Comment DemDem le crée |
|---|---|---|
| GC1 | G1 — Décision en confiance | Comparaison claire des 3 options avec indicateur de fiabilité de la donnée |
| GC2 | G2 — Comparaison instantanée | Écran unique listant bus, TER, taxi côte à côte avec prix et durée |
| GC3 | G3 — Alerte au bon moment | Suggestion de changement de mode déclenchée par géolocalisation (phase 2) |
| GC4 | G4 — Langue accessible | Interface en français simple, noms de quartiers en Wolof, pas de codes de lignes |

---

## Fit Résumé

> DemDem réduit l'anxiété du départ (Pain P1) en donnant à Moussa une estimation coût + temps en moins de 10 secondes (Pain Reliever PR1), lui permettant de prendre sa décision de déplacement en confiance (Gain G1) sans quitter sa maison sans savoir (Job J2).
