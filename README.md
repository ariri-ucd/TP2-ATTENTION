# TP – Image Captioning avec RNN et Attention

## Description du projet
Ce TP consiste à implémenter un modèle de **captioning d’image** utilisant un **ResNet pré-entraîné** comme extracteur de caractéristiques, combiné à un **RNN avec un module d’attention**.  
L’objectif est de générer automatiquement des légendes textuelles pertinentes à partir d’images.  
Le dataset utilisé est **Flickr30k**, contenant plus de 30 000 images annotées.

Le TP permet de pratiquer :  
- Le **transfer learning** avec un ResNet50 pré-entraîné.  
- La création et l’utilisation d’un **module d’attention personnalisé**.  
- La construction d’un **LSTM modifié avec attention**.  
- La manipulation d’**embeddings pré-entraînés** (Word2Vec).  
- La gestion du **learning rate scheduling** et du pipeline d’entraînement.  
- La génération et l’évaluation de légendes au fil des epochs.

## Contenu du dépôt
- `TP_Attention_ImageCaptioning.ipynb` : Notebook principal avec toutes les étapes (prétraitement, modèle, attention, entraînement, génération de captions).  
- `compte_rendu_TP_Attention.pdf` : Rapport détaillé du TP.  
- `README.md` : Ce fichier d’information.  
## Prérequis
Avant de lancer le notebook, assurez-vous d’avoir installé :  
- Python ≥ 3.8  
- PyTorch  
- torchvision  
- NumPy  
- pandas  
- matplotlib  
- (optionnel) jupyter ou JupyterLab  

Installation des dépendances via pip :  
```bash
pip install torch torchvision numpy pandas matplotlib jupyter
