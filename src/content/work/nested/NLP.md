---
title: Extraction d'Information et Recherche de Réponses avec NLP et Machine Learning
publishDate: 2025-01-12 00:00:00
img: /assets/nlp.avif
img_alt: Une image abstraite représentant des flux de données et de l'intelligence artificielle
description: |
  Ce projet vise à extraire des informations pertinentes d'un document PDF et à utiliser des techniques de traitement du langage naturel pour répondre à des questions basées sur le contenu extrait.
tags:
  - NLP
  - Machine Learning
  - Traitement du Langage Naturel
---

## Introduction au projet

Dans ce projet, nous avons développé un système permettant d'extraire du texte d'un document PDF et d'utiliser des modèles de **Traitement du Langage Naturel** (NLP) pour répondre à des questions en se basant sur le contenu extrait. Nous avons intégré des techniques de **Nettoyage de Texte**, **Embeddings**, et de **Recherche** pour trouver la réponse la plus pertinente.

### Objectif du projet

L'objectif est de construire un modèle capable de traiter un document PDF, d'en extraire le texte, de le nettoyer, puis d'utiliser des embeddings pour transformer ce texte en représentations numériques. Ensuite, un système de recherche est mis en place pour trouver des réponses précises à des questions données en se basant sur les données extraites.

### Approche

1. **Extraction du texte** : Nous avons utilisé la bibliothèque **PyPDF2** pour extraire le texte brut du fichier PDF. Le texte est ensuite nettoyé pour enlever les éléments non pertinents comme les numéros de pages ou les liens URL.

2. **Nettoyage du texte** : Nous avons nettoyé le texte extrait en supprimant les espaces inutiles, les retours à la ligne, et en enlevant les informations telles que les numéros de page et les URL. Cela permet d’obtenir un texte plus lisible et structuré.

3. **Création d'Embeddings** : Nous avons utilisé **OpenAI** pour générer des embeddings du texte nettoyé. Ces embeddings représentent le texte sous forme de vecteurs numériques dans un espace vectoriel, ce qui permet de comparer facilement la similarité entre des phrases ou des documents.

4. **Recherche de réponses** : Grâce à l'indexation avec **FAISS**, nous avons pu effectuer une recherche rapide et efficace pour trouver la phrase la plus proche de la question posée, en calculant la distance entre l'**embedding** de la question et ceux des phrases extraites.

### Résultats

Le système a montré une grande capacité à répondre correctement à des questions en utilisant le contenu du PDF, avec des réponses provenant des phrases les plus pertinentes. Par exemple, pour une question sur l'historique d'un virus, le système a pu extraire une phrase pertinente du document, avec une précision élevée.

### Conclusion

Ce projet illustre l'importance de l'utilisation des techniques NLP et des embeddings dans l'extraction d'informations et la recherche de réponses. Il est possible d'adapter ce système pour répondre à des questions sur différents types de documents, ce qui peut être utile dans divers domaines tels que la gestion de documents légaux, l'analyse de rapports financiers, ou même dans des applications de support client automatisé.

---

### Technologies utilisées

- **PyPDF2** : Pour l'extraction du texte brut à partir de fichiers PDF.
- **Spacy** : Pour le traitement du texte, y compris la segmentation des phrases et la gestion du langage.
- **OpenAI** : Pour la génération des embeddings de texte, permettant de transformer le texte en vecteurs numériques.
- **FAISS** : Pour l'indexation et la recherche de similarité entre les embeddings afin de répondre aux questions.
- **Regex** : Utilisé pour le nettoyage du texte, afin de supprimer les éléments inutiles comme les espaces excessifs, les retours à la ligne et les liens URL.

