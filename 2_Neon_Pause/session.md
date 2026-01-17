# Neon Pause

## Intro
Club Tropique fume la nuit; la conversation sur le patio est couverte par une nappe musicale. Une patiente du centre de réhab chuchote des phrases entre deux refrains, puis s’évanouit dans une pause qui paraît démesurée. Quelque chose cloche : est-ce fatigue, manipulation, ou danger ?

## Musique suggérée (ambiance):
Nappes disco-funk, pads analogiques. Évoque Lethal Weapon pour les contrastes entre action et introspection, ou un morceau synthwave lent style GTA.

## Objectifs techniques (débutant → intermédiaire simple) :
* Générer un spectrogramme mel-log (ou STFT) et repérer la nappe musicale vs la voix.
* Séparer grossièrement la voix et la musique par simple filtrage spectral (ex : filtrage passe-bas ou soustraction de bruit spectral).
* Détecter et mesurer la longue pause : timestamp début/fin, durée.
* Extraire MFCC moyen pour le segment vocal principal (pour références ultérieures).
* Noter toute baisse d’énergie RMS pendant la pause.
