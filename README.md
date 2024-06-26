# Traitement automatique du langage naturel avec les Tweets de catastrophes 

<p align="center">
    <img src="https://github.com/TAOUFIK05/Traitement-automatique-du-langage-naturel-avec-les-Tweets-de-catastrophes/assets/48359677/51c684d2-addd-4ae3-9dc7-28acc948bb4b.jpg" width='900' height="400" />
</p>


Ce projet de traitement automatique du langage naturel (TALN) visant à prédire les tweets relatifs aux catastrophes. Le projet se concentre sur le développement d'un modèle d'apprentissage automatique capable de distinguer les tweets réels sur les catastrophes des tweets non pertinents. Les données utilisées sont issues d'un ensemble de tweets annotés manuellement. Ce projet vise à explorer les techniques de TALN et à fournir une solution pratique pour la surveillance des médias sociaux en cas d'urgence.

Twitter est devenu un canal de communication crucial en cas d'urgence. Avec la prolifération des smartphones, les gens peuvent annoncer en temps réel les urgences qu'ils observent. Cependant, il n'est pas toujours évident de déterminer si les mots utilisés dans un tweet annoncent réellement une catastrophe.

Dans ce contexte, le défi consiste à développer un modèle d'apprentissage automatique capable de prédire quels tweets concernent de vraies catastrophes et lesquels ne le font pas. Pour cela, nous disposons d'un ensemble de données comprenant des tweets manuellement classifiés.

## Description du jeu de données

Chaque échantillon dans l'ensemble d'entraînement et de test contient les informations suivantes :

    - Le texte d'un tweet
    - Un mot-clé associé à ce tweet (qui peut être vide)
    - L'emplacement d'où le tweet a été envoyé (également susceptible d'être vide)
    - La cible, qui indique dans l'ensemble d'entraînement si le tweet concerne une véritable catastrophe (1) ou non (0)

## Fichiers

    train_disaster_tweets.csv : l'ensemble d'entraînement
    test_disaster_tweets.csv : l'ensemble de test

## Colonnes

    id : un identifiant unique pour chaque tweet
    text : le texte du tweet
    location : l'emplacement d'où le tweet a été envoyé (peut être vide)
    keyword : un mot-clé associé au tweet (peut être vide)
    target : dans train.csv seulement, cela indique si un tweet concerne une véritable catastrophe (1) ou non (0)

##### Ce projet est inspiré par la compétition "Natural Language Processing with Disaster Tweets" sur Kaggle https://kaggle.com/competitions/nlp-getting-started.
