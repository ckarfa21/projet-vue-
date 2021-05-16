# projet-vue-
# Application Vue.js avec NodeJS .  

L'api est un moyen permettant la communication entre 2 applications préalablement  crées en 2 language différents.
# C'est quoi Node JS ?   
Node.js est très couramment utilisé pour écrire des services côté serveur appelés API (interfaces de programmation d’application).  
Enfin, on peut dire que Node.js représente une alternative aux langages serveur tels que PHP, Java ou Python.  
Par rapport à Java, les lignes de code dans Node.js sont réduites de 33% et les fichiers sont réduits de 40%  
La version Node.js est 35% plus rapide que la version Java.
# C'est quoi Vue JS ?  
Vue.js, est un framework JavaScript open-source utilisé pour construire des interfaces utilisateur et des applications web monopages.
# L'application :   
Développement et l'exécution d'une application Vue avec NodeJS.  
Application  dans laquelle nous pouvons ajouter des utilisateurs, les compter et les afficher sur le côté, et les récupérer.  

# Installations nécessaires à la création de l'application :  

[Installer Node JS ](https://nodejs.org/en/)  

[Installer Vue Cli ](https://cli.vuejs.org/)  

[Installer  Bootstrap pour la présentation graphique du site .](https://bootstrap-vue.org/)  

[Installer Vs code : l'éditeur de texte . ](https://code.visualstudio.com/)  
## Structure de l'application :  
Nous aurons deux package.json: un pour l'API Vue et un autre pour l'API nodejs. Il est toujours préférable d'avoir des node_modules complètement différents pour chacun. De cette façon, vous n'obtiendrez pas de problèmes de fusion ou d'autres problèmes concernant la collision des modules de nœuds Web et de serveur.
##  1: Création de l'application :  
NB:(Si vous placez l'API NodeJS dans le dossier racine au lieu de dans un dossier séparé, vous pourriez avoir des problèmes avec la CLI Vue en récupérant les node_modules racine.)  
## Vue UI:
Pour créer l'interface utilisateur qui s'appellera my-app,il faut ouvrir un cmd  puis se positionner  dans le répertoire du projet  et taper cette commande : vue create my-app .  
(Dans la phase de développement, l'application Vue s'exécute sur le port 8080 à l'aide d'une CLI Vue et d'une API nodejs s'exécutant sur le port 3080 .)  
### 1 er cmd:
cd api  
npm install  
npm run dev  
### 2 éme cmd :  
// start the react app  
cd my-app  
npm install  
npm run serve  





