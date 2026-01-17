# Dockside Engines

## Intro
Dock 19, le vent sent l’huile. Deux voix s’emmêlent au-dessus du grondement des moteurs — ordre et contre-ordre. Tu écoutes une conversation où l’un chuchote une adresse pendant que l’autre cale une voiture. C’est l’écheveau final : localiser le lieu de stockage des véhicules volés.

## Musiques
Rythme tendu, percussions industrielles et basse lourde — pense Heat durant l’assaut, ou une bande-son de Driver pendant la poursuite nocturne.

## Objectifs techniques (débutant → intégration des acquis) :
* Produire spectrogramme et identifier les deux voix (différences harmoniques / F0).
* Extraire F0 et tenter de séparer (grossièrement) segments dominés par speaker A vs speaker B (par pitch / energy).
* Extraire la signature fréquentielle du moteur (bandes basses) et sauvegarder un petit “fingerprint” (ex : spectre moyen sur 3–4s).
* Comparer ce fingerprint avec un mini-database fourni en jeu (ici, on te donnera 3 empreintes hypothétiques) — implémenter une distance spectrale simple (euclidienne) pour matching.
* Résumer les preuves en un court rapport (timestamps, qui parle quand, motor-match score).
