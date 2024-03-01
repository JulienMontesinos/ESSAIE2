# ESSAIE2

```
https://www.youtube.com/watch?v=_fx7FQ3SP0U&list=PLzMcBGfZo4-kR7Rh-7JCVDN8lm3Utumvq

Serveur minecraft
Context: La semaine dernière, j'étais occupé à déployer une machine virtuelle sur GCP et à y installer une application pour un serveur Minecraft.

Ce que j'ai fait : Jusqu'à présent, pour déployer notre serveur Minecraft, nous étions confrontés à une contrainte nécessitant systématiquement 4 Go de mémoire. nous avons opté pour des machines virtuelles de spécifications supérieures, qui sont généralement beaucoup plus coûteuses. Cependant, après une période de recherche approfondie, nous avons découvert que le problème pouvait être résolu simplement en modifiant une valeur dans le fichier de propriétés du serveur. En ajustant le paramètre "tick-time" dans ce document,le véritable besoin en mémoire pour notre serveur Minecraft s'est avéré être de seulement 1024 Mo. Nous avons réussi à réduire la mémoire requise à seulement 1024 Mo.

Nous avons élaboré des scripts de démarrage (startup) et d'arrêt (shutdown) et les avons intégrés à notre machine virtuelle dans le but de synchroniser le lancement de notre serveur avec celui de la VM. Cependant, malgré nos efforts, nous n'avons pas encore réussi à les faire fonctionner correctement. Nous allons continuer de poursuivre nos recherches pour résoudre ce problème.

Nous n'avons pas encore eu l'occasion de tester notre solution de sauvegarde dans un contexte réel d'utilisation. Néanmoins, d'après les tests préliminaires que nous avons effectués, nous sommes optimistes quant à son succès.

Python 
J'ai codé via python un pierre feuille ciseau en multijoueur

On a mis le serveur python sur une de son machine virtuel donc maintenant via le langage de programation python je sais faire une application ou different client peuvent communiquer entre eux, ce sera utile pour nos futur projet
![image](https://github.com/JulienMontesinos/ESSAIE2/assets/61452154/dff77dff-eb4d-407a-9eea-2b350e8f7513)

```
