# Base
* mem[0-2] : file d'attente de création des robots (0: harvester,  1: explorer,  2: soldier)
* mem[3-4] : file d'attente de création des missiles
* mem10 : coordonnées des bases ennemie
* mem11 : énegie pour savoir de combien elle a changée tous les <un nombre> ticks
# Déplaçable
## Harvester
* mem5 : destination
## Rocket Launcher
* mem0 : mode de fonctionnement
* mem[1-2] : coordonnées des bases énemies
* mem5 : destination
## Explorer
* mem0 : mode de fonctionnement
* mem1 : base énemie repérée
* mem3 : nombre de bases à laquelle l'information courrante a été donné
* mem5 : destination
