# Exercices de modélisation de bases de données à l’aide du langage Entité-Association

Pour chacun des exercices suivants : donnez le schéma Entité-Association d’une base de données pouvant capturer les différents éléments du domaine d’application décrit dans l’extrait textuel (et, éventuellement, précisez les contraintes d'intégrité).
Pour se lancer…

## 1. Système d’information d’une bibliothèque
Le système informatique d'une bibliothèque enregistre le numéro national, le nom, le prénom et l'adresse (composée de la rue, du numéro, du code postal et de la commune) de chacun de ses clients. Le système enregistre pour chaque livre disponible son numéro unique ISBN, son titre, le nom de ses auteurs et sa date d'achat. Il apparaît que la bibliothèque possède au plus un livre par numéro ISBN. Le système enregistre également tous les emprunts des clients. On identifie ces emprunts avec un numéro unique, on retient la date d'emprunt et la date de retour lorsque le livre rentre. Cette date ne peut normalement pas excéder 15 jours après la date d’emprunt.

## 2. La gestion de plats
Un plat possède un nom, une origine et se compose de certaines quantités d'ingrédients différents. Ces ingrédients portent un nom. Il faut pouvoir enregistrer plusieurs plats ayant un nom identique mais une recette différente. La quantité s'exprime en différentes unités selon l'ingrédient : par exemple, une quantité d'eau s'exprimera en litres tandis qu'une quantité de farine en grammes.


## 3. L’éditeur
Un éditeur souhaite installer une base de données structurant les informations suivantes:
- Les livres sont identifiés par leur numéro ISBN. Un livre possède un titre et un prix de vente. Il est écrit par un ou plusieurs auteurs.
Chaque livre est tiré en une ou plusieurs éditions, datées et identifiées par leur ordre (première édition, seconde édition, etc.). Chaque édition comporte un certain nombre d'exemplaires. Le prix de vente peut changer d'une édition à l'autre.
Un livre peut éventuellement être primé : Goncourt, Fémina etc.
- Les auteurs sont identifiés par leur nom et prénoms, et peuvent avoir un pseudonyme. Pour chaque livre, un auteur perçoit des droits d'auteur annuels, calculés comme un pourcentage des ventes (il varie en fonction des auteurs et de leur nombre pour un livre donné).
- Les libraires (identifiés par leur nom et adresse complète) commandent des livres en précisant l’édition et le nombre d’exemplaires désiré

[URL vers l'intégralité du fichier d'exercices tf-cours-bdd-mar9-aout2022-tou-les-exercices](https://acrobat.adobe.com/link/review?uri=urn:aaid:scds:US:d4d83748-8ad2-3cf4-8976-90a71c39fd2c)
