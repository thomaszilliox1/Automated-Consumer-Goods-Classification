# Résumé du projet

## Contexte

Sur cette place de marché anglophone, des vendeurs proposent des articles à des acheteurs en postant une photo et une description.  
Il devient nécessaire d'automatiser l'attribution de la catégorie des articles, pour rendre l’expérience utilisateur des vendeurs plus fluide.

## Mission

Étudier la faisabilité d'un moteur de classification des articles en différentes catégories, à partir du texte (en anglais) et de l’image.

## Méthodes utilisées

### Classification grâce aux descriptions des articles

- Méthodes classiques : Bag of Words et TF-IDF
- Méthodes de Word Embedding :
  - Word2Vec
  - BERT : Tensorflow Hub et Hugging Face Transformers
  - USE (Universal Sentence Encoder)

### Classification grâce aux images des articles

- Méthode SIFT : non concluante
- Méthodes Convolutional Neural Network : VGG16, VGG19 et ResNet50
