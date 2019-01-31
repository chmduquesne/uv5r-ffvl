# uv5r-ffvl

Fichier [Chirp](https://chirp.danplanet.com/projects/chirp/wiki/Home) orienté parapentisme pour la radio baofeng uv5r. Chirp [fonctionne très bien sous Linux](https://chirp.danplanet.com/projects/chirp/wiki/Running_Under_Linux).

## Fréquences pré-enregistrées

| Canal   | Description                                                                                                    |
|---------|----------------------------------------------------------------------------------------------------------------|
| 0       | [FFVL](http://pmr446.free.fr/index_vol-libre.htm)                                                              |
| 1-8     | Fréquences [talkie walkie](https://fr.wikipedia.org/wiki/PMR446)                                               |
| 9       | Secours Montagne ([canal E](https://fr.wikipedia.org/wiki/Canal_E_(VHF)))                                      |
| 10      | [Appel d'urgence Europe](https://en.wikipedia.org/wiki/International_distress_frequency) en bande des 2 mètres |

Les [LPD433](https://fr.wikipedia.org/wiki/LPD433) n'y sont pas programmées car la puissance autorisée est trop faible pour une utilisation sérieuse.

## Réglages

### Lignes A/B

* La ligne du haut (A) est réglée pour afficher la fréquence du canal
* La ligne du bas (B) est réglée pour afficher le nom du canal

Ceci permet de consulter à la fois la fréquence d'un canal enregistré et son nom (en se positionnant sur le même canal sur les lignes A et B).

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
