# brief-multi-input

Projet réalisé dans le cadre de la formation Simplon Développeur en Intelligence Artificielle.

## Description du projet :

L'objectif du projet est de créer un modèle multi-inputs de classification pour déterminer la catégorie d'un produit, en utilisant la description et l'image du produit.

## Étapes du projet :

Modèle basé sur le texte : Entraîner un modèle de NLP pour classer les produits en fonction de leur description.
Modèle basé sur l'image : Entraîner un réseau de neurones convolutif pour classer les produits en fonction de leur photo.
Modèle multi-inputs : Combiner les deux modèles en une architecture multi-inputs pour améliorer la précision des prédictions.

## Choix des modèles :

Afin d'accélérer l'entraînement, des modèles légers en terme de nombre de paramètres ont été séléctionnés via la librairie Keras : 
- pour le modèle de NLP : "bert_tiny_en_uncased"
- pour le modèle de CV : "efficientnetv2_b0_imagenet"
