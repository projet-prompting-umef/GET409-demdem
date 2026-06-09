# Contraintes MVP — GET409-DemDem

Équipe : GET409-DemDem
Séance : S2 — Issues des 6 Chapeaux de Bono
Projet : DemDem — Planification de trajets multimodaux, Région de Dakar
Date : 08/06/2026

## Persona

Moussa Fall, 50 ans, voyageur quotidien, Keur Massar — Smartphone, usage WhatsApp et vocal.

---

## Contraintes Non Négociables

**Contrainte 1**

**Critère :** Le MVP DOIT afficher la comparaison des modes (bus, TER, taxi) en moins de 10 secondes après la saisie du trajet.
**Origine :** Chapeau Noir (interface complexe = abandon immédiat pour un profil 50 ans / usage vocal)
**Élimine :** Écrans de chargement, onboarding multi-étapes, formulaires longs.

**Contrainte 2**

**Critère :** Le MVP DOIT fournir une fourchette de prix ET une durée estimée pour chaque mode — même approximatives.
**Origine :** Chapeau Blanc (aucun tarif officiel affiché → l'app doit compenser l'opacité tarifaire)
**Élimine :** Affichage d'un seul mode, prix sans durée, durée sans prix.

**Contrainte 3**

**Critère :** Le MVP NE DOIT PAS exiger plus de 2 actions de l'utilisateur pour obtenir le résultat (saisir départ + destination).
**Origine :** Chapeau Rouge (anxiété avant le départ → l'app doit réduire la friction, pas l'augmenter)
**Élimine :** Création de compte obligatoire, choix de l'heure, filtres avancés en page principale.

**Contrainte 4**

**Critère :** Le MVP DOIT fonctionner sans connexion parfaite — afficher un résultat en mode dégradé si les données temps réel sont indisponibles.
**Origine :** Chapeau Noir (données temps réel inexistantes pour lignes informelles)
**Élimine :** Blocage de l'app si pas de données live, dépendance à une seule API externe.

**Contrainte 5**

**Critère :** Le MVP DOIT présenter les résultats en langue accessible — français simple ou Wolof — sans jargon technique.
**Origine :** Chapeau Rouge (fierté de maîtriser son trajet → l'app complète le savoir local, ne le remplace pas)
**Élimine :** Codes de lignes non traduits, abréviations non expliquées, interface en anglais.

---

## Fonctionnalités Éliminées

- Tracking GPS en temps réel des bus → éliminé (données non disponibles sur lignes informelles en S3)
- Système de notation des chauffeurs → éliminé (hors scope MVP, risque de conflits terrain)
- Planification de trajets multi-jours → éliminée (usage ciblé sur le départ immédiat ou du lendemain matin)
- Compte utilisateur / profil personnel → éliminé (frein à l'adoption pour le profil Moussa)
- Version USSD → éliminée du MVP S3, déplacée en roadmap post-MVP (complexité d'intégration opérateur)

---

## Critère de Validation Final

Le MVP est valide si et seulement si : Moussa peut, depuis son domicile à Keur Massar, connaître en moins de 10 secondes quelle option (bus, TER ou taxi) lui coûte le moins cher et lui prend le moins de temps pour rejoindre sa destination — sans aide extérieure.
