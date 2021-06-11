# Projet-Cooperation-INSAT-WYNSYS

Dans le cadre d’une collaboration INSAT-WYNSYS, ce TP représente une étude et mise en place d’une
solution d’affectation et suivi en temps réel des opérateurs pour une ligne de production donnée.
Ce rapport est subdivisé en deux parties.

Dans la 1ére partie, nous allons présenter respectivement la société WYNSYS TUNISIE et le contexte
général du TP5 mettant en relief une description du système que nous développerons par la suite.

La 2éme partie sera dédiée au déploiement de la solution en se basant sur l’analyse fonctionnelle des besoins
proposé par WYNSYS, en commençant par le développement du modèle BPMN. Par la suite, nous nous
intéresserons au développement et configuration de l’application BUILD.ME de la nouvelle solution
proposée.

Dans le troisième chapitre, nous nous intéressons à la modélisation et le choix des ressources pour cette
solution.

Nous terminons notre travail par une conclusion générale présentant les principaux résultats ainsi que les
perspectives à ce travail.

![image](https://user-images.githubusercontent.com/83011466/121744699-90d2b300-cb03-11eb-9dde-4db5a8d17c20.png)

# Cadrage du système

Grâce à la digitalisation des processus industriels via la mise en place des systèmes connectés de
Gestion d’exécution de la production MES les industriels cherchent à maitriser l’ensemble des
processus industriels et à superviser la progression des travaux dans les différents ateliers.

La problématique qui se présente aujourd’hui est l’exploitation de ces nouvelles opportunités offertes
par les systèmes MES pour modéliser une solution ergonomique dont le but est de suivre en temps
réel l’exécution de la production.

# Déploiement de la solution BPMN

l’outil BPMN
L’outil BPMN (Business Process Model and Notation) a été développé avec l'objectif de
faciliter la communication entre les différents acteurs engagés dans le développement des
systèmes d'information et des applicatifs orientés sur les processus de l'entreprise, afin de
favoriser l'utilisation d'un langage commun de modélisation.

A ce niveau, nous allons modéliser les flux et décrire l’enchainement des processus
d’authentification, d’affectation et suivi en temps réel des opérateurs et superviseurs.

![image](https://user-images.githubusercontent.com/83011466/121745053-240be880-cb04-11eb-82f8-67714015ba72.png)

Application Build.me

Cette étape comprend l’implémentation de la solution sur le système d’information Build.me
Outil Build.me

Un outil de SAP build est un outil destiné à construire un projet informatique pour obtenir
un livrable, un JAR ou encore un WAR (destiné à être déployé sur un serveur d'applications).

# Déploiement de la solution sur Build.me

On commencera par définir notre base de données. 
Après nous passerons à l’explication par
étape de l’utilisation de notre solution.

Les operateurs :
![image](https://user-images.githubusercontent.com/83011466/121745195-633a3980-cb04-11eb-88a2-8fb97d84daeb.png)

Les machines et les operations (de production et Hors-production :

![image](https://user-images.githubusercontent.com/83011466/121745305-7816cd00-cb04-11eb-9fb7-784f4fa87e29.png)  ![image](https://user-images.githubusercontent.com/83011466/121745370-81079e80-cb04-11eb-853d-a5567cdcabea.png)  ![image](https://user-images.githubusercontent.com/83011466/121745405-89f87000-cb04-11eb-8345-ba3636f72880.png)
