# 6 Chapeaux de Bono — GET409-DemDem

Équipe : GET409-DemDem
Séance : S2 — Design Thinking · Ideate & Define
Projet : DemDem — Planification de trajets multimodaux, Région de Dakar
Date : 08/06/2026

## HMW analysé

> Comment pourrions-nous permettre à un voyageur dakarois de comparer et choisir l'itinéraire optimal en coût et en temps entre plusieurs modes de transport, afin qu'il prenne sa décision de déplacement en confiance avant de quitter son domicile ?

---

## 🤍 Chapeau Blanc — Faits & Données

- Les voyageurs de Keur Massar, Pikine et Guédiawaye passent en moyenne 2 à 3h par jour dans les transports, selon les témoignages recueillis en interview terrain.
- Il n'existe aucun système GTFS (données de transport en temps réel) public et accessible pour le réseau de bus, Tata et cars rapides de Dakar — seul le TER dispose d'horaires officiels.
- Le prix d'un trajet en taxi, car rapide ou Tata varie selon l'heure, la direction et le chauffeur : aucun tarif officiel affiché, tout se négocie à l'oral.

---

## ❤️ Chapeau Rouge — Émotions & Intuitions

- Moussa ressent une anxiété chronique avant chaque départ : ne pas savoir combien coûtera le trajet ni à quelle heure il rentrera génère un stress quotidien invisible mais épuisant.
- Il éprouve de la honte lorsqu'il rate un rendez-vous professionnel ou familial à cause d'un retard de transport — une frustration que peu d'applications actuelles prennent en compte.
- Il y a une fierté tacite à « connaître les raccourcis » : les dakarois qui maîtrisent les astuces de déplacement se sentent compétents ; une app qui leur vole cette expertise risque d'être rejetée.

---

## 🖤 Chapeau Noir — Risques & Critique

- Les données de transport en temps réel n'existent pas pour la majorité des lignes — une app qui donne des estimations sans source fiable perd toute crédibilité dès le premier trajet raté.
- Le profil de Moussa (50 ans, usage WhatsApp et vocal) indique une faible appétence pour les interfaces complexes : un parcours utilisateur avec plus de 2 écrans avant l'info risque d'être abandonné immédiatement.
- La tarification variable des taxis et cars rapides rend toute estimation de coût incertaine ; l'app peut donner un prix indicatif mais ne peut pas garantir le tarif réel — source de déception et de méfiance.

---

## 💛 Chapeau Jaune — Optimisme & Valeur

- Une estimation même approximative (fourchette de prix et de durée) suffit à débloquer la décision de départ : Moussa n'a pas besoin d'exactitude absolue, juste d'un seuil de confiance.
- Le TER est sous-utilisé par les voyageurs de banlieue qui ne savent pas qu'il est parfois plus rapide et moins cher que le taxi : une comparaison visible pourrait réorienter massivement la demande.
- L'usage de WhatsApp est déjà universel dans le profil cible : une intégration ou une interface familière (boutons simples, résumé en 1 ligne) maximise l'adoption sans formation.

---

## 💚 Chapeau Vert — Créativité & Idées

- Et si l'app apprenait les trajets habituels de Moussa et lui envoyait une alerte proactive le matin avant qu'il parte, sans qu'il ait à ouvrir l'application ?
- Et si les voyageurs eux-mêmes signalaient en temps réel la fréquence et le prix des véhicules, créant une base de données communautaire à la manière de Waze pour les transports dakarois ?
- Et si une version USSD (sans internet, juste le réseau GSM) permettait aux voyageurs sans data d'accéder à une estimation simplifiée via un code comme `*384#` ?

---

## 💙 Chapeau Bleu — Processus & Organisation

- La priorité S3 est de valider une seule chose : est-ce que Moussa utilise l'app au moins une fois avant de partir ? Tout le reste est secondaire.
- Le scénario de démo S6 doit simuler un trajet réel Keur Massar → Plateau avec les 3 modes (bus, TER, taxi) et montrer la comparaison en moins de 10 secondes.
- L'équipe doit trancher en S2 entre deux hypothèses concurrentes : (1) l'app mobile Flutter, (2) un bot WhatsApp — les deux ont des profils de risque opposés sur la donnée et l'adoption.

---

## 🔵 Synthèse Chapeau Bleu

**HMW révisé :**

> Comment pourrions-nous permettre à Moussa de voir en moins de 10 secondes, depuis son smartphone, quelle combinaison bus/TER/taxi lui coûte le moins cher et lui prend le moins de temps pour aller de Keur Massar au centre de Dakar, afin qu'il parte en confiance sans avoir à négocier à l'aveugle ?

**Risques prioritaires :**
1. Absence de données en temps réel pour les lignes informelles (Tata, cars rapides) → les estimations seront des fourchettes, pas des certitudes.
2. Interface trop complexe pour un profil 50 ans / usage vocal dominant → risque d'abandon au premier écran.

**Question ouverte :**
Faut-il construire une app mobile Flutter ou un bot WhatsApp pour maximiser l'adoption dans le profil Moussa ?
