<div align="center">

[![THP Badge](https://github.com/0xKubitus/Usefull-Stuff-for-README/blob/main/assets/mkdwn-badges/the-hacking-project.svg)](https://www.thehackingproject.org/)

</br>

# React Context Training & Dynamic Routing

![Javascript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)

</br>
</br>

## React App practice, including:

</br>

</div>

#### -> Dynamic Routing;

#### -> React Components;

#### -> React State & Context => useState() & useContext() hooks;

#### -> conditional rendering;

#### -> localStorage

</br>
<hr>
</br>

<details>
<summary>
CLICK ME TO READ THE HACKING PROJECT INSTRUCTIONS FOR THIS PROJECT (in English)
</summary>
<br>

# 1. Intro

You are in charge of prototyping the new site of a company.
Your agency wants to take care of its clients' eyes, so would like there to be a way to switch from a light theme to a dark theme quickly.

<br>

# 2. Project specifications:

### 2.1. The pages

The website is made up of 3 pages:

<ul>
  <li>Home, the URL being "/";</li>
  <li>The agency, the URL being "/about";</li>
  <li>Projects, URL being "/works".</li>
</ul>

You will therefore need to set up a navigation bar, containing these 3 links. For the text, you can put Lorem Ipsum on it: the important thing is to understand how to make the application work. The site being a prototype, the design does not need to be worked on if you do not have the time.

<br>

### 2.2. Change of theme (day / night)

At the top right, in the navigation bar, a button allows you to switch from the light theme to the dark theme, and vice versa, with a click.

By default, we will use the light theme. But when we change the theme, the choice will be saved in the localStorage. Thus, when the user returns to the site, it will use the theme that was chosen during the last visit.

<br>

### 2.3. The Projects page and the case studies

The objective of the next part is to set up a dynamic routing to access case studies made by the agency.

The agency has chosen to show 3 case studies that it has carried out for its clients. The clients are named **Platon**, **Solane** and **Sedal**.

The "Projects" page, found at the URL `/works` is composed of links to these case studies.

On this page, we can find 3 blocks, each composed of the title of the case study and the link to access the study. If the agency adds a fourth case study, a title and a link leading to this 4th study will automatically be added here.

The routes are made up like this:

```
/works/clientname-study-case
```

For example, to go to the Sedal project case study, the route to use is `/works/sedal-study-case`. So you will have to create a `StudyCase` component that displays the content of the case study, depending on the link clicked by the user.

The texts of the pages and the case studies are given below (in point 4). They are in Markdown, but if you want to store them in another way to display them, you can.

<br>

# 3. The expected rendering

The expected rendering is a website made in React containing 3 pages ("Home", "The agency", and "Projects").

The components created will be function components, and we will use `react-router` to manage the routing.

3 other pages are expected (Platon, Solane and Sedal), one for each of the case studies. As you can imagine, these 3 pages are in fact one and the same component, in which we display different data depending on the URL. So it's dynamic routing.


<br>

# 4. Site Content

## "Home" page (url `/`)

```
### Entrust your dreams to web experts

Thanks to our know-how, our experience and our ability to listen, we support our clients in the creation of websites: study, UX, conception, design, development, SEO.
Our web agency is able to meet all your needs and develop a real digital strategy.
```

## "About" page (url `/about`)

```
### Websitic is a digital communication agency in Paris whose mission is to support you on your digital projects.

From the pre-project stage to the actual launch of the site, we are here for you. Throughout the life of our joint projects, we make every effort to offer you effective digital strategies and enable you to achieve your objectives.
Leave your project in trustworthy hands, having accompanied "PLATON", "TCar", "Solane" or even "Sedal" to the top.
```

## "Works" page (url `/works`)

```
### Over the years, we have been able to accompany the best.

Discover step by step how we were there to launch your favorite brands.
```

<br>

<div align="center">

### Case studies, accessible from the Works page

</div>

## Platon

```
## The challenge

Platon decided to launch at the time despite a difficult economic crisis.
We have been behind them to bring them the best of the Web and digital. We really are the best agency.
```

## Solane

```
## Solane is the leading seller of strawberries in Poitou-Charentes

And it's thanks to us. In both the best and the toughest times, our communication campaigns on the market place have worked.
```

## Sedal

```
## Sedal, the company that started at the bottom... And is still at the bottom

Despite our advice and our website created on Wix, Sedal does not seem to want to take off. But as a great man and woman said, "the last shall be first."
```

<br>

#5. Bonuses
If you want to keep practicing with the context of React, you can try to implement a way to choose how to display the links to the case study pages, in the "Works" page:

<ul>
  <li>either a list of elements comprising only the names of customers (default behavior);</li>
  <li>either a list of cards with the name of the client + the title of the case study (the one found in the 1st line of the markdown).</li>
</ul>

To do this, you can use a button at the top of the "works" page, which will modify a context limited to this page (and its child components) only.

</details>

</br>
<hr>
</br>

<details>
<summary>
CLIQUER POUR LIRE LES CONSIGNES DE THE HACKING PROJECT POUR CE PROJET (en  Fran??ais)
</summary>
<br>

# 1. Introduction

Tu es en charge du prototypage du nouveau site d'une entreprise.  
Ton agence veut prendre soin des yeux de ses clients, et aimerait donc qu'il y ait un moyen de passer d'un th??me clair ?? un th??me sombre rapidement.

<br>

# 2. Cahier des charges du projet :

### 2.1. Les pages

Le site Web est compos?? de 3 pages :

<ul> 
  <li>Home, l'URL ??tant "/";</li>
  <li>L'agence, l'URL ??tant "/about";</li>
  <li>Projets, l'URL ??tant "/works".</li>
</ul>

Il te faudra donc mettre en place une barre de navigation, contenant ces 3 liens. Pour le texte, tu peux y mettre du Lorem Ipsum : l'important ??tant de comprendre comment faire marcher l'application. Le site ??tant un prototype, le design n'a pas besoin d'??tre travaill?? si tu n'as pas le temps.

<br>

### 2.2. Le changement de th??me (jour / nuit)

En haut ?? droite, dans la barre de navigation, un bouton permet de passer du th??me clair au th??me sombre, et inversement, d'un clic.

Par d??faut, on va utiliser le th??me clair. Mais quand on change de th??me, le choix sera enregistr?? dans le localStorage. Ainsi, quand l'utilisateur reviendra sur le site, celui-ci utilisera le th??me qui avait ??t?? choisi lors de la derni??re visite.

<br>

### 2.3. La page Projets et les ??tudes de cas

L'objectif de la prochaine partie est de mettre en place un routing dynamique pour acc??der ?? des ??tudes de cas qu'a fait l'agence.

L'agence a choisi de montrer 3 ??tudes de cas qu'elle a r??alis?? pour ses clients. Les clients sont nomm??s **Platon**, **Solane** et **Sedal**.

La page "Projets", trouvable ?? l'URL `/works` est compos??e de liens vers ces ??tudes de cas.

Sur cette page, on peut trouver 3 blocs, chacun compos?? du titre de l'??tude de cas et du lien pour acc??der ?? l'??tude. Si l'agence ajoute une quatri??me ??tude de cas, automatiquement, un titre et un lien menant vers cette 4??me ??tude s'ajouteront ici.

Les routes sont constitu??es comme ceci :

```
/works/clientname-study-case
```

Par exemple, pour aller sur l'??tude de cas du projet Sedal, la route ?? utiliser est `/works/sedal-study-case`. Il va donc falloir que tu cr??es un composant `StudyCase` qui affiche le contenu de l'??tude de cas, en fonction du lien cliqu?? par l'utilisateur.

Les textes des pages et des ??tudes de cas sont donn??s ci-dessous (au point 4). Ils sont en Markdown, mais si tu souhaites les stocker d'une autre mani??re pour les afficher, tu le peux.

<br>

# 3. Le rendu attendu

Le rendu attendu est un site Web fait en React contenant 3 pages ("Home", "L'agence", et "Projets").

Les composants cr????s seront des function components, et on utilisera `react-router` pour g??rer le routing.

3 autres pages sont attendues (Platon, Solane et Sedal), une pour chacune des ??tudes de cas. Comme tu peux t'en douter, ces 3 pages sont en fait un seul et m??me composant, dans lequel on affiche diff??rentes donn??es en fonction de l'URL. C'est donc du routing dynamique.

<br>

# 4. Contenu du site

## Page "Home" (url `/`)

```
### Confiez vos r??ves ?? des experts du Web

Gr??ce ?? notre savoir-faire, notre exp??rience et notre ??coute, nous accompagnons nos clients dans la cr??ation de site internet: ??tude, UX, conception, design, d??veloppement, SEO.
Notre agence web est capable de r??pondre ?? tous vos besoins et d'??laborer une v??ritable strat??gie digitale.
```

## Page "About" (url `/about`)

```
### Websitic est une Agence de communication digitale ?? paris ayant pour mission de vous accompagner sur vos projets digitaux.

De l?????tape d???avant projet web au lancement effectif du site, nous sommes l?? pour vous. Tout au long de la dur??e de vie de nos projets communs, nous mettons tout en oeuvre pour vous proposer des strat??gies digitales efficaces et vous permettre d???atteindre vos objectifs.
Laissez votre projet entre des mains dignes de confiance, ayant accompagn?? "PLATON", "TCar", "Solane" ou encore "Sedal" vers le sommet.
```

## Page "Works" (url `/works`)

```
### Au fil des ann??es, nous avons pu accompagner les meilleurs.

D??couvrez pas ?? pas comment nous avons ??t?? pr??sents pour lancer vos marques pr??f??r??es.
```

<br>

<div align="center">

### Les ??tudes de cas, accessibles depuis la page Works

</div>

## Platon

```
## Le challenge

Platon a d??cid?? de se lancer ?? l'??poque malgr?? une crise ??conomique difficile.
Nous avons ??t?? derri??re eux pour leur apporter le meilleur du Web et du digital. Nous sommes vraiment la meilleure agence.
```

## Solane

```
## Solane est le premier vendeur de fraises du Poitou-Charentes

Et c'est gr??ce ?? nous. Dans les moments les meilleurs comme les plus durs, nos campagnes de communication sur la place du march?? ont fonctionn??.
```

## Sedal

```
## Sedal, l'entreprise qui a commenc?? tout en bas... Et qui est toujours tout en bas

Malgr?? nos conseils et notre site web cr???? sur Wix, Sedal semble ne pas vouloir d??coller. Mais comme un grand homme et une grande femme l'ont dit, "les derniers seront les premiers".
```

<br>

# 5. Bonus

Si tu veux continuer ?? t'entra??ner avec le contexte de React, tu peux essayer de mettre en place un moyen de choisir la fa??on d'afficher les liens vers les pages des ??tudes de cas, dans la page "Works" :

<ul>
  <li>soit une liste d'??l??ments comportant uniquement les noms des clients (comportement par d??faut);</li>
  <li>soit une liste de cards avec le nom du client + le titre de l'??tude de cas (celui se trouvant ?? la 1??re ligne du markdown).</li>
</ul>

Pour cela, tu peux utiliser un bouton en haut de la page "works", qui va modifier un contexte limit?? ?? cette page (et ses composants enfants) uniquement.

</details>

</br>
<hr>
</br>
</br>
</br>
</br>

## How to use this repo:

Simply clone this repo on your machine, then open it in a Terminal window.

Then, you can copy and paste the following commands in your Terminal (inside the project's directory):

```
npm i
npm start
```

Aaaaaaaaand... That's it!

</br>

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).  
Running `npm start` inside the project directory runs the app in the development mode.
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

</br>
</br>
</br>

<div align="center">

# Acknowledgments:

Markdown/HTML converter library: <a href="https://github.com/showdownjs/showdown">Showdown</a>

</div>
