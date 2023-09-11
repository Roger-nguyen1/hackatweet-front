# 📚 Hackatweet

Bonjour,

Je me présente, je suis Roger. Actuellement, je suis en train d’approfondir mes compétences en développement web, avec une concentration particulière sur le développement frontend en utilisant React. J’ai trouvé un immense plaisir à programmer tous ces projets. Je vous invite à me poser des questions et à explorer mes autres réalisations.

## ✍️ Description

L'objectif de ce projet est de créer un réseau social basé sur Twitter.

Pour la configuration, le frontend doit interagir avec un service backend via fetch, tout en favorisant les principes de code propre et le développement piloté par les tests (TDD) pour certaines fonctionnalités spécifiques, telles que la vérification des champs saisis.

La page de connexion permet aux utilisateurs de créer un compte ou de se connecter. En cliquant sur les boutons "S'inscrire" ou "Se connecter", une fenêtre modale s'ouvre avec les champs d'entrée correspondants. L'application communique avec le backend, et si les informations sont correctes, l'utilisateur est redirigé vers le composant "Accueil". En cas d'inscription, les informations de l'utilisateur sont enregistrées dans la base de données. Un jeton est utilisé, et les mots de passe sont hachés. Trois composants sont utilisés : "Login.js", "SignUp.js" et "SignIn.js".

La page d'accueil est divisée en trois sections. La section de gauche affiche les informations de l'utilisateur et un bouton de déconnexion, tandis que la section de droite présente les "Tendances", c'est-à-dire les hashtags utilisés et leur fréquence. Dans la section centrale, les utilisateurs peuvent ajouter des tweets et consulter les derniers tweets de tous les utilisateurs. Un tweet ne peut pas dépasser 280 caractères, et des fonctionnalités de "j'aime" et de suppression sont mises en œuvre pour les tweets appartenant à l'utilisateur. Quatre composants sont utilisés : "Home.js", "LastTweets.js", "Tweet.js" et "Trends.js".

Enfin, la page des hashtags apparaît lorsque l'utilisateur clique sur un hashtag dans la section "Tendances". Cette page comporte des composants similaires à la page d'accueil, avec une barre de recherche et une liste de tweets contenant le hashtag sélectionné. L'utilisateur peut rechercher d'autres hashtags à l'aide de la barre de recherche. Si aucun tweet ne contient le hashtag recherché, un message est affiché. Quatre composants sont utilisés : "Hashtag.js", "LastTweets.js", "Tweet.js" et "Trends.js".

## 🎬 Getting Started : Dependencies and Other

La plupart de mes projets ont un frontend et backend séparés, vous les trouverez sur mon github.

```

yarn install

```

```

yarn dev

```

## ⚛️ Tech and Stuff

- HTML
- CSS
- JavaScript
- React
- Redux
- MongoDB
- Node.JS
- Next.JS
- Vercel
- …

## 🚀 Deploy

⇒ https://hackatweet-front-mu.vercel.app/

## 🧑‍💻 Authors

Roger NGUYEN

## 🌐 Network

My Portfolio : [Roger NGUYEN](https://portfolio-roger.vercel.app/)

LinkedIn : [https://www.linkedin.com/in/roger-nguyen-7705aa257](https://www.linkedin.com/in/roger-nguyen-7705aa257/)
