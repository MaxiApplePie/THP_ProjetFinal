# THP_ProjetFinal
Repo de travail pour brainstormer sur le projet final

## 0. Titre

IZITEAM

## 1. Présentation

L'objectif est de créer une plate-forme de mise en relation de porteurs de projets et de développeurs informatiques. 
Le service est totalement gratuit parce que lorsqu'on a une bonne idée on n'a pas forcément le budget pour la développer.

## 2. Parcours utilisateur

Une landing page avec la présentation du concept IziTeam (un bon gros <code>bootstrap</code> avec de jolis effets) 
La liste des derniers inscrits qui proposent leurs compétences. 
La liste des derniers projets proposés. 
Avant de consulter quoi que ce soit l'utilisateur du site devra se connecter. 
Ensuite il a la possibilité d'aller consulter les projets et de voir les personnes qui sont inscrites. 
Le porteur de projet définira son projet via un formulaire. 
Possibilité pour les utilisateurs de se contacter entre eux.

## 3. Concrètement et techniquement

Site écrit en <code>Rails</code>, hebérgé sur Heroku. 
Base de données <code>PostgreSQL</code>. 
Front-end en <code>HTML5</code> et <code>bootstrap</code>. 
Un minimum de Javascript pour commencer. 
Il faudra pouvoir envoyer des mails automatiquement.

### 3.1. Base de données

<code>PostgreSQL</code>.
Le design de la base est effectué en premier lors de la conception de l'application.
On modélise sur dbdiagram.io/ puis on exporte le modèle en <code>PostgreSQL</code>
Ça nous permettra de comparer si on genere à l'identique
Le modèle sera conçu en 3e forme normale .. Au minimum [<code>https://fr.wikipedia.org/wiki/Forme_normale_(bases_de_donn%C3%A9es_relationnelles)</code>]

### 3.2. Front

On va faire du <code>bootstrap</code>, du <code>bootstrap</code> et du <code>bootstrap</code>. 
D'ailleurs ce serait bien d'arriver à installer un template un peu sympa.
Utilisation du flash-alert

### 3.3. Backend

- <code>Rails</code>
- <code>Ruby</code>
- <code>POO</code>
- <code>Gem Devise</code>
- <code>Gem Faker</code>
- <code>gem Better errors</code>
- <code>gem Dotenv-rails</code>
- <code>Mailer</code> avec <code>SendGrid</code> (perso, Je n'ai pas réussi à trouver la version gratuite de Mailjet)

### 3.4. La DreamTeam

Des moussaillons motivés, compétents et sympas .. Mais enfin si on est arrivés jusqu'ici c'est que tout va bien.

#### Compétences

- <code>GitHub</code> : Il faudra avoir une connaissance minimale des fonctionnement des branches pour pouvoir travailler en parallèle.
- <code>Rails</code> : À ce niveau on est à peu près tous pareils .. Écrire un code de qualité qui suit les standards. Quand quelqu'un me fait une remarque sur mon code et qu'il me propose mieux je suis preneur.
- <code>POO</code> : Tout en POO ... pas de SQL dans le code. Validation des modèles dès qu'on fait une modification
- <code>Bundler</code> : Ça serait pas mal de maîtriser bonne l'heure pour éviter les écarts de configuration entre nous.
- <code>Heroku</code> : Une bonne compréhension du dashboard et du push.
- <code>Bootstrap</code> : Là aussi ce serait bien d'avoir une certaine maîtrise de <code>bootstrap</code> et d'aller un peu loin dans son utilisation.
- <code>Trello</code> : À partir de maintenant on passe en mode projet donc chacun a objectif ... Même si on continue à bosser tous ensemble.
- <code>Discord</code> : Vocal ouvert en continu.
- <code>Rspec</code> : Et oui on va faire des tests ... Même sur la partie objet.

Perso, ~~je peux boire trois pintes de bière sans trop de difficulté~~ 

Balance ici tes compétences, puis tes besoins pour les 3-4 personnes restantes.

## 4. La version minimaliste mais fonctionnelle qu'il faut avoir livré la première semaine
Nous allons vous demander de livrer une version minimaliste mais fonctionnelle à la fin de la première semaine. Décris ce que vous voulez avoir fait à la fin de la première semaine. Pense minimaliste, fonctionnel, efficace. Comment avec le moins de code possible vous arrivez à donner une version fonctionnelle de l'application. 

Ceci s'appelle le MVP, pour Minimum Viable Product. Voici un exemple de MVP pour un site que tu connais bien, celui de THP : les gens peuvent s'enregistrer sur le site, puis s'inscrire à une session. S'ils s'inscrivent, ils ont accès à tout le cursus qui est hébergé sur la plateforme. Nous nous occuperons à la main d'envoyer des emails pour annoncer le début de la session et nous ferons les groupes à la main. Spoiler : THP a commencé comme ceci ;)

## 5. La version que l'on présentera aux jury
La deuxième semaine vous allez ajouter des fonctionnalités pour améliorer l'expérience utilisateurs de votre application. Quelles fonctionnalités tu aimerais bien ajouter ?

## 6. Notre mentor
Qui est ton mentor ?

## Fabriqué avec

* [Windows 10 // WSL2 // Ubuntu] - Environnement
* [VS Code] - Editeur de textes



## Auteur

* **Laurent Mollard-Chaumette** _alias_ [MaxiApplePie](https://github.com/MaxiApplePie)