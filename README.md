<!--
  MODÈLE DE README — Pipeline Data, séquence 1, chapitre 5
  Les blocs comme celui-ci sont des consignes : GitHub ne les affiche pas.
  Remplace chaque \\\[crochet] par ton texte, puis supprime les crochets.
  Repères Markdown : une ligne qui commence par # est un titre ; une ligne qui commence par - est une puce.
-->

# Entrepôts – Analyse territoriale


Comparer la répartition des entrepôts logistiques à celle de la population en France pour repérer les disparités régionales.

## 1. Le problème

<!-- Reprends ta fiche projet : le contexte en 2 ou 3 phrases, la question centrale, l'utilisateur. -->

* **Contexte** : Les entrepôts logistiques sont répartis sur le territoire français. Leur implantation ne correspond pas forcément à la répartition de la population.
* **Question centrale** : Les entrepôts logistiques sont-ils répartis de manière cohérente avec la population française ?
* **Utilisateur** : Une direction Supply Chain, pour repérer les régions où le réseau logistique pourrait être développé.

## 2\. Les données

<!-- Une ligne par source envisagée, comme dans ta fiche projet. -->

|Source|Type|Ce qu'elle apporte|
|-|-|-|
|SDES – Entrepôts et plateformes logistiques|Excel, CSV|Informations sur la répartition des entrepôts et plateformes logistiques en France|
|INSEE – Population par région|Excel, CSV|Données sur la population des régions françaises|

## 3\. L'organisation du dépôt

<!-- Laisse cette liste telle quelle : elle décrit les dossiers créés au chapitre 3. -->

* `data/raw/` : les données brutes, telles que reçues, jamais modifiées
* `data/processed/` : les données nettoyées, prêtes pour l'analyse
* `notebooks/` : les notebooks Jupyter d'exploration et d'analyse
* `scripts/` : les scripts Python du projet
* `sql/` : les requêtes SQL
* `api/` : l'API du projet
* `dashboard/` : le rapport Power BI et ses captures d'écran
* `docs/` : la fiche projet et les documents du projet

## 4\. L'avancement

<!-- Les étapes de ton projet. La première est faite. Tu cocheras les suivantes une fois le module terminé, quand tu appliqueras chaque méthode à ton projet : remplace alors \\\[ ] par \\\[x]. -->

* \[x] Sujet choisi, dossiers créés, dépôt publié
* \[ ] Collecte des données
* \[ ] Requêtes SQL
* \[ ] Nettoyage et dataset final
* \[ ] Stockage en base
* \[ ] API
* \[ ] Analyse et tableau de bord

\---

Axel Vayne · Formation Data Analyst \& IA · DataSuits





