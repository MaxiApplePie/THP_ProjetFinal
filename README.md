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

Site écrit en <code>Rails</code>, hebérgé sur <code>Heroku</code>. 
Base de données <code>PostgreSQL</code>. 
Front-end en <code>HTML5</code> et <code>bootstrap</code>. 
Un minimum de Javascript pour commencer. 
Il faudra pouvoir envoyer des mails automatiquement.

### 3.1. Base de données

<code>PostgreSQL</code>.
Le design de la base est effectué en premier lors de la conception de l'application.
On modélise sur dbdiagram.io/ puis on exporte le modèle en <code>PostgreSQL</code>.
Ça nous permettra de comparer si on genere à l'identique
Le modèle sera conçu en 3e forme normale .. Au minimum [Lien](https://fr.wikipedia.org/wiki/Forme_normale_(bases_de_donn%C3%A9es_relationnelles))]

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
- <code>Bundler</code> : Ça serait pas mal de maîtriser Bundler pour éviter les écarts de configuration entre nous.
- <code>Heroku</code> : Une bonne compréhension du dashboard et du push.
- <code>Bootstrap</code> : Là aussi ce serait bien d'avoir une certaine maîtrise de <code>bootstrap</code> et d'aller un peu loin dans son utilisation.
- <code>Trello</code> : À partir de maintenant on passe en mode projet donc chacun a son objectif ... Même si on continue à bosser tous ensemble.
- <code>Discord</code> : Vocal ouvert en continu.
- <code>Rspec</code> : Et oui on va faire des tests ... Même sur la partie objet.

Perso, ~~je peux boire trois pintes de bière sans trop de difficulté~~ j'ai pas eu de difficultés particulières avec <code>Heroku</code> et <code>GitHub</code>. Le code que j'écris en ruby me fait penser à du caca donc je ne ferai pas office de référent technique. Par contre je connais très bien les bases de données et le design de DB. <code>Bootstrap</code> me plaît bien. Et je peux m'occuper des tests sous Rspec. 

- Un volontaire pour gerer le Trello.
- Un volontaire pour garantir la qualité du code de l'équipe.
- Un/deux volontaire(s) pour creuser <code>Bootstrap</code>.
- Un volontaire pour nous créer des données cohérente avec <code>Faker</code>.
- Il faudrait quelqu'un qui s'intéresse à <code>Bundler</code> mais là je crois que c'est difficile à trouver
 **... Tout ça en mode détendu ... On ne va pas révolutionner internet.**

Celui qui arrive à faire fonctionner ce qui suit est recruté direct
`config/initializers/backtrace_silencers.rb
Rails.backtrace_cleaner.add_silencer { |line| line =~ /lib/ }`

## 4. Notre MVP au bout de 5 jours

- Landing page avec du <code>Bootstrap</code> minimal.
- Une jolie navbar.
- Creation du User (Pas de page Admin).
- Liste des projets.
- Liste des développeurs.
- Un formulaire qui permet de proposer un projet.
- Un formulaire qui permet de proposer ses compétences.
 ... Le tout fonctionnel sur <code>Heroku</code>

## 5. La version que l'on présentera aux jury

- <code>Bootstrap</code> avancé.
- Interface administrateur. [Un gros bisou à celui qui arrive à nous installer [Lien](https://getbootstrap.com/docs/5.0/examples/dashboard/)
- Notion de tag: Rails, Python, Laravel, etc ...
- Nuage de tags ????
- Envoi de mails à la connexion.
- Robot qui envoie une lettre d'info le lundi matin à 9h.
- Image d'avatar pour le developpeur [Gravatar ?].
- Connexion avec Google [<code>gem Devise</code>].
- Des données de qualité en base pour la démo.

## 6. Notre mentor

Obi-Wan Kenobi

## Auteur

* **Laurent Mollard-Chaumette** _alias_ [MaxiApplePie](https://github.com/MaxiApplePie)