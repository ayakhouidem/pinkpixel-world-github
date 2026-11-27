# Notes sur le bug PPW-6

## Problème
Le solde de PinkCoins n'est pas déduit après un achat en boutique.

## Hypothèse
La fonction d'achat ajoute l'article à l'inventaire sans appeler la déduction du solde.

## Correction prévue
Appeler la déduction du solde avant la validation de l'achat.
