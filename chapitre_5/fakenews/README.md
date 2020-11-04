# Modifier une page web (et en faire une fake news)

### Sommaire :

## Prérequis

* google chrome (version ordinateur)
* un site internet pour la fake news. Por l'exemple on prendra [celui-ci](https://www.ouest-france.fr/catastrophes/ouragan/l-ouragan-delta-s-eloigne-du-mexique-et-se-rapproche-des-etats-unis-7006129). (ne le reprenez pas c'est ce que j'ai fais ^^)

> ![image 1](./delta-1.png)
> 
> Le site de l'exemple.

### Sauvergarder le site une première fois

Il suffit de cliquer *droit* n'importe où sur la page et de sélectionner `Enregistrer sous...`. Là vous enregistrez la page quelque part sur votre ordi (c'est possible que ça vous enregistre d'autres fichiers aussi, ___c'est normal___) :

![image 1](./delta-2.png)

### Ouvrir la page **locale**

1. Il faut d'abord aller dans le dossier où se trouve la page téléchargée
2. Ensuite il faut ouvrir la page avec *google chrome* : (dans mon exemple, il y a un fichier et un dossier pour cette page web)
  * clic droit sur le fichier de **type** `.html`
  * choisir `Ouvrir avec`
  * choisir le choix qui contient `google chrome`

![image 3](./delta-3c.png)

Une page avec le site web devrait s'afficher dans google chrome. Si la page s'afficher mal (*vraiment* mal), il vaut mieux prendre un autre site...

## Modifier un élément de la page

Pour changer un élément (= une partie) de la page, il faut :

1. faire un clic droit sur la partie à modifier
2. choisir `Inspecter` (voir image dessous)

=> Un volet s'ouvre à droite (ou ailleurs) dans google chrome : c'est l'inspecteur. Il permet de modifier la page "en direct". Il est coupé en trois parties :

* En haut, avec le texte "Elements" souligné en ici bleu. C'est le code source de la page rendu plus lisible. C'est de ça qu'on aura le plus besoin.
* Au milieu, il y a un éditeur de style. On n'en l'utilise pas là.
* En bas, la console et les nouveautés. Pareil, cette partie nous on s'en fiche.

![image 4](./delta-4.png)

![image 5](./delta-5.png)

> Vous pouvez redimensionner les différentes parties du volet pour mieux voir de la même façon qu'on redimensionne une fenêtre dans windows
