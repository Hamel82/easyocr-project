# OCR Handwriting Recognition avec EasyOCR

Ce projet propose une solution simple de reconnaissance d'écriture manuscrite (Handwriting Recognition) à partir d'images, en utilisant la bibliothèque [EasyOCR](https://github.com/JaidedAI/EasyOCR). Il s'appuie sur un notebook Python pour illustrer toutes les étapes, de l'import des images à l'affichage des résultats.

## Objectif
L'objectif est de détecter et de lire automatiquement du texte manuscrit présent sur des images, en exploitant la puissance d'EasyOCR, une librairie open-source performante pour l'OCR multilingue.

## Prérequis
- Python 3.7 ou supérieur
- Les bibliothèques suivantes :
  - easyocr
  - supervision
  - opencv-python (cv2)
  - numpy
  - matplotlib

Vous pouvez installer les dépendances principales avec :
```bash
pip install easyocr supervision opencv-python numpy matplotlib
```

## Utilisation
1. Ouvrez le notebook `im_pro_easyOcr.ipynb` dans Jupyter Notebook, JupyterLab ou PyCharm.
2. Suivez les étapes du notebook :
   - Import des bibliothèques
   - Initialisation du modèle EasyOCR
   - Lecture et affichage d'images
   - Extraction et affichage du texte reconnu

## Fonctionnalités principales du notebook
- Chargement d'un modèle EasyOCR pré-entraîné pour l'anglais
- Lecture de texte sur des images (exemples : `unnamed.png`, `sample1.jpeg`)
- Affichage des résultats sous forme de liste de textes détectés
- Visualisation des images traitées

## Exemple de résultat
```
['SERIAL NUMBER AOC1715821', 'PART NUMBER 9-00864-01']
['because be doing']
```

## Remarques
- Le notebook fonctionne sur CPU, mais l'utilisation d'un GPU est recommandée pour de meilleures performances.
- Pour une utilisation sur Google Colab, adaptez l'affichage des images avec `cv2_imshow`.

## Auteur
Projet réalisé dans le cadre d'une expérimentation sur la reconnaissance d'écriture manuscrite avec EasyOCR. 