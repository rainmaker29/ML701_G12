## Dataset
The dataset can be found at https://www.kaggle.com/datasets/rainmaker29/sdss-images

## Environment
To set up environment, please install the libraries from libraries_installed.txt using conda


## Reproduce results

To reproduce the results, please run the following files:

### Numeric modelling 
1) Data Preprocessing : .\Numeric data modelling\Testing_Normal_distribution_features.ipynb
2) Traditional models on numeric data :  .\Numeric data modelling\Traditional ml algorthims.ipynb

### Image Modelling 
1) Fetch images from tabular data (optional as the shared dataset already has fetched images from sdss database) : Image modelling\Fetch images.ipynb
2) SVM : .\Image modelling\SVM.ipynb
3) CNN : .\Image modelling\CNN.ipynb
4) DNN : .\Image modelling\DNN.ipynb
5) ViT : .\Image modelling\ViT Train and Eval.ipynb

### Imbalanced techniques 

1) Generate quasar augmentations : .\Imbalanced techniques\Augmentation\image_augmentation.ipynb
2) CNN on augmented data : .\Imbalanced techniques\Augmentation\CNN_Augmentations.ipynb
3) Transfer learning on all data : .\Imbalanced techniques\Transfer Learning\All data\all_data_DNN.ipynb
4) Transfer learning on balanced data : .\Imbalanced techniques\Transfer Learning\Balanced data\post_DNN.ipynb
5) SimCLR Pretraining : .\Imbalanced techniques\Pretraining\SimCLR Train.ipynb
6) SimCLR + other classifiers train,eval : .\Imbalanced techniques\Pretraining\SimCLR Validation.ipynb
7) BYOL Pretraining : .\Imbalanced techniques\Pretraining\BYOL Train.ipynb
8) BYOL + other classifiers train,eval : .\Imbalanced techniques\Pretraining\BYOL Validation.ipynb


## Alternate (and easily) reproduce results 

We also provide Colab/Kaggle versions of most of above notebooks so that reproduction of results gets easier (below are the links).
### Image Modelling 
1) Fetch images from tabular data (optional as the shared dataset already has fetched images from sdss database) : https://www.kaggle.com/code/rainmaker29/sloan-dataset-code-amaan/notebook
2) CNN : https://colab.research.google.com/drive/1rSXBMaxN1MXrGxNMDwEnVcipveR0iUa3?usp=sharing
3) ViT : https://www.kaggle.com/rainmaker29/vision-transformer-vit-tutorial-baseline

### Imbalanced techniques 

1) Generate quasar augmentations : https://colab.research.google.com/drive/19Mhhhs0O73tVKQHSW_anubQ0GXepfRIa?usp=sharing
2) CNN on augmented data : https://colab.research.google.com/drive/1f7uU4YYBOJuAw66hR_r4fbSpV5L2PxtD?usp=sharing
3) SimCLR Pretraining : https://www.kaggle.com/rainmaker29/simclr-ml701
4) SimCLR + other classifiers train,eval : https://www.kaggle.com/code/rainmaker29/simclr-post-training-ml701-byol
5) BYOL Pretraining : https://www.kaggle.com/rainmaker29/contrastive-learning-using-byol
6) BYOL + other classifiers train,eval : https://www.kaggle.com/code/mohammadamaansayeed/contrastive-learning-using-byol

