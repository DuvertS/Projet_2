# Présentation du projet

## Analyse des tendances cinématographiques pour un nouveau studio

Aperçu

Ce projet a pour objectif d’aider une entreprise à identifier les types de films à produire pour son nouveau studio de cinéma. À travers une analyse des tendances actuelles des films populaires, nous proposons des recommandations stratégiques basées sur les données de films (genres, durée, notes, votes).


**Contexte**:

L'entreprise souhaite créer un studio de cinéma mais ne possède aucune expertise dans le domaine. Elle veut maximiser ses chances de succès dès ses premières productions.


**Problème commercial**:

> "Quels types de films devrions-nous produire pour augmenter nos chances de réussite au box-office ?"


**Questions clés des parties prenantes** :
- Quels genres dominent actuellement le marché ?
- Quel est le profil typique d’un film à succès ?
- Quels types de films devrions-nous éviter ?
- La durée ou la note influence-t-elle la rentabilité ?

## Compréhension et analyse des données

Source des données
Les données proviennent d’une base simplifiée inspirée d’IMDb, composée de deux tables :
- `movie_basics` : titre, année, durée, genre
- `movie_ratings` : note moyenne, nombre de votes

Nous avons filtré les films avec :
- Plus de 100 votes
- Année de sortie renseignée
  

## Trois visualisations clés

### 1. **Genres les plus fréquents**

- Les genres **Drame**, **Documentaire** et **Thriller** sont les plus représentés parmi les films populaires.
  

### 2. **Distribution des notes IMDb**
- La majorité des films ont une note entre **6 et 8**.
- Peu de films très mal notés (<5), ce qui reflète un certain filtrage qualitatif.
  

### 3. **Durée moyenne des films par genre**
- Les **documentaires** sont globalement plus courts.
- Les **drames** et **thrillers** ont des durées plus longues (souvent > 100 min).

## Conclusion 

### Résumé des conclusions

1. **Les genres dominants** chez les films bien notés et populaires sont :
   - Drame
   - Biographie
   - Thriller

2. **Durée optimale** : Les films qui réussissent le mieux durent entre **90 et 150 minutes**.

3. **Éviter les films** :
   - Trop longs (>180 minutes)
   - Trop expérimentaux ou peu populaires
   - Avec des genres rares ou mal classés

## Recommandations

- Produire principalement des **drames et thrillers avec une bonne narration**.
- Viser une **note IMDb supérieure à 7**.
- Éviter les projets à risque avec peu d’intérêt public identifiable.

