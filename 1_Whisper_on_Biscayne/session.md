# Whisper on Biscayne

## Intro
La pluie a cessé, mais la nuit colle toujours au bitume. Sur le parking du Bayview Diner, un informateur tremble en murmurant au micro posé sous la table. Les néons dégoulinent. Tu mets ton casque, t’appuies sur Play et une voix filtrée glisse un mot : “Marina”. Tu sens que c’est le premier fil à tirer.

## Musique suggérée (ambiance):
Pistes instrumentales lentes, basse chaude et nappes analogiques — pense à l’intensité sobre de Heat, ou un groove nocturne façon Driver / GTA Vice City (synth bass + brushed drums).

## Objectifs techniques (débutant) :
* Charger l’audio en Python (librosa.load) et afficher la waveform.
* Générer un spectrogramme STFT et l’afficher.
* Repérer le timestamp exact du mot-clé (écoute + repérage visuel sur spectrogramme).
* Extraire et tracer la courbe RMS pour visualiser parole vs silence.
* Calculer la durée de la pause (en secondes) qui suit le mot-clé.
