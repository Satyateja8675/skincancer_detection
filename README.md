Abstract:

Skin cancer has been gradually increasing among the people for decades.Every
year the number of new cases of melanoma,and ,the death rate is increasing.In
2020 325,00 cases of melanoma were found among which 57,000 people
died.Classifying these melanoma from images is a difficult task because of their
minute variation from non cancerous skin lesions.In this project we are going to
build a computer-aided diagnosis system for classifying skin lesions.In the
preprocessing steps hair and other artifacts from the image are removed using
morphological filtering.And to extract the foreground or lesion region from the
image we used grab-cut segmentation.Melanoma and benign lesions are detected
according to the image processing method using CNN’s.Pre trained CNN’s like
Resnet50,MobileNet,VGG16 were used in this project for the image classification
task.And also to improve the efficiency Data Augmentation techniques like
Rotation are also employed.

steps involved:
1. image pre-processing 
2.segmentation 
3.feature extraction 
4.classification

base paper & datasets:
Base paper URL:https://link.springer.com/article/10.1007/s11042-022-13081-x

datasets:
ISIC2017 Database: 580 Images (270 Malignant and 310 Benign) with
            Patients Age (Years)   Patients Gender (Male and Female)
HAM10000 Database: 350 Images (135 Malignant and 215 Benign cases) with
          Patients Age (Years) Patients Gender (Male and Female)
               https://challenge.isic-archive.com/data/#2017
                 https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000




