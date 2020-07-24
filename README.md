# uv5r-ffvl

Fichier [Chirp](https://chirp.danplanet.com/projects/chirp/wiki/Home) orienté parapentisme pour la radio baofeng uv5r. Chirp [fonctionne très bien sous Linux](https://chirp.danplanet.com/projects/chirp/wiki/Running_Under_Linux).

## Fréquences pré-enregistrées

| Canal   | Description                                                                                                    |
|---------|----------------------------------------------------------------------------------------------------------------|
| 0       | [FFVL](http://pmr446.free.fr/index_vol-libre.htm)                                                              |
| 1       | Secours Montagne ([canal E](https://fr.wikipedia.org/wiki/Canal_E_(VHF)))                                      |
| 2       | Bodenlos                                                                                                       |
| 3-18    | Fréquences [talkie walkie](https://fr.wikipedia.org/wiki/PMR446)                                               |
| 19-56   | Sous-canaux CTCSS 1-38 des radios Midland pour la PMR 01                                                       |

Les [LPD433](https://fr.wikipedia.org/wiki/LPD433) n'y sont pas programmées car la puissance autorisée est trop faible pour une utilisation sérieuse.

## Réglages

### Autolock

* l'autolock est activé

### Modes d'affichage des lignes

* La ligne du haut (A) affiche la fréquence de son canal
* La ligne du bas (B) affiche le nom de son canal

Ceci permet de consulter la fréquence d'un canal enregistré en choisissant le même canal pour A et B.

### Dual watch

* La radio est réglée pour écouter sur A et B en même temps, mais pour
  n'émettre que sur A. L'idée est d'écouter la FFVL sur B et de parler sur
  A.

### Message de démarrage

* La radio indique Tof's Radio au démarrage. Sentez-vous libre de modifier
  ce message!

## Rappels utiles

Il faut se mettre en mode fréquence pour pouvoir mémoriser un canal. Seule la ligne du haut (A) peut être mémorisée.
Il existe un [manuel d'utilisation non officiel](https://radiodoc.github.io/uv-5r/).
