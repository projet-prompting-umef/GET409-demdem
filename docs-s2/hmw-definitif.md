# HMW Définitif Validé — GET409-DemDem

Équipe : GET409-DemDem
Séance : S2 — Validation post-6 Chapeaux de Bono
Projet : DemDem — Planification de trajets multimodaux, Région de Dakar
Date : 08/06/2026

---

## HMW Initial (S1)

> Comment pourrions-nous permettre à un voyageur dakarois de comparer et choisir l'itinéraire optimal en coût et en temps entre plusieurs modes de transport, afin qu'il prenne sa décision de déplacement en confiance avant de quitter son domicile ?

---

## HMW Définitif (S2 — post 6 Chapeaux)

> Comment pourrions-nous permettre à Moussa de voir en moins de 10 secondes, depuis son smartphone, quelle combinaison bus/TER/taxi lui coûte le moins cher et lui prend le moins de temps pour aller de Keur Massar au centre de Dakar, afin qu'il parte en confiance sans avoir à négocier à l'aveugle ?

---

## Ce qui a changé et pourquoi

| Élément | HMW S1 | HMW S2 | Raison du changement |
|---|---|---|---|
| Persona | "voyageur dakarois" (générique) | "Moussa" (nommé, ancré) | Chapeau Rouge : l'émotion et le contexte précis sont indispensables |
| Contrainte temps | Absente | "moins de 10 secondes" | Chapeau Bleu : critère de démo S6 mesurable |
| Localisation | Absente | "Keur Massar → centre de Dakar" | Chapeau Blanc : trajet réel observé en interview terrain |
| Modes | "plusieurs modes" (vague) | "bus/TER/taxi" (explicite) | Chapeau Blanc : modes réellement disponibles sur ce trajet |
| Tension | "en confiance" (abstract) | "sans avoir à négocier à l'aveugle" | Chapeau Noir : le vrai problème est l'asymétrie d'information face au chauffeur |

---

## Critères de Validation du HMW

Le HMW est atteint si :

- [ ] Moussa obtient une comparaison en < 10 secondes (M1)
- [ ] Il déclare qu'il partirait sur la base de l'info affichée (M3)
- [ ] Il n'a pas eu besoin d'aide pendant le test (M2)
- [ ] Les 3 modes (bus, TER, taxi) sont affichés simultanément (M5)

---

## Périmètre du HMW

**Dans le scope :**
- Trajet Keur Massar ↔ centre de Dakar (Plateau, Médina, Yoff)
- Modes : bus DAKAR DEM DIKK, TER, taxi, Tata, car rapide
- Usage : décision avant le départ, smartphone Android

**Hors scope (roadmap post-MVP) :**
- Tracking GPS temps réel
- Bot WhatsApp / USSD
- Trajets hors région de Dakar
- Notation des chauffeurs
