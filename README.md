# KoSAIM2022-chest-x-ray-classification
[KoSAIM 2022 Summer School] Hands-On-CNN: Chest X-ray Classification

[Colab Link](https://colab.research.google.com/drive/1KjMR0sGlR5S0yAYNgF4g8G5J-IWBC2aW?usp=sharing)

[Slides](https://docs.google.com/presentation/d/1j2YHD0k7uJAgznQqJAxSvTqPmnoAZNGjMs5hF2gTKlg/edit?usp=sharing)

## objective
Given a chest X-ray image, you need to predict positive diagnosis (pneumonia) labels. Construct the binary image classifier for prediction, and you could consider any kind of image encoder.

## dataset
Ped-Pneumonia  
[https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)  
[http://www.cell.com/cell/fulltext/S0092-8674(18)30154-5](http://www.cell.com/cell/fulltext/S0092-8674(18)30154-5)

The normal chest X-ray (left panel) depicts clear lungs without any areas of abnormal opacification in the image. Bacterial pneumonia (middle) typically exhibits a focal lobar consolidation, in this case in the right upper lobe (white arrows), whereas viral pneumonia (right) manifests with a more diffuse ‘‘interstitial’’ pattern in both lungs.

## images & labels
Feel free to pre-process the images as you see fit (the minimum resolution is 224x224).

## things to consider
- Image resolution
- Pixel value normalization
- Class imbalance

## data split


## modeling & evaluation
- Use whatever model you prefer.
    - Recommended: any CNN-based model (e.g., VGGNet, ResNet)
- Use both [AUROC](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.roc_auc_score.html) and [AUPRC](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.average_precision_score.html) as the evaluation metric.
