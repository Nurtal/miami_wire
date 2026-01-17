# Glitched Tape

## Introduction
Tu reçois une cassette marquée d’un tampon “Confidentiel”. Sur la bande, la voix paraît fine, puis, 3 secondes après le début, quelque chose la traverse : une tonalité plus aiguë, un écho. Viktor Petroff aime jouer avec les bandes — est-ce un trucage ? Tu dois prouver si la bande a été altérée.

## Musiques

## Objectifs techniques (débutant → diagnostique simple) :
* Afficher spectrogramme et identifier la zone avec la pitch-shift (repérage visuel / écoute).
* Extraire pitch (F0) via librosa.pyin ou autocorrélation, et tracer F0 dans le temps.
* Comparer la distribution F0 avant/après l’anomalie (moyenne et variance).
* Détecter présence d’écho/reverb basique (analyse d’autocorrélation ou observation de smearing temporel dans spectrogramme).
* Documenter preuves (timestamps + captures spectrogramme) à usage du dossier.
