# Object_detection_-_classification
Implementation and investigation of different objection detection and classification algorithms

1. region_cnn.ipynb

    This notebook shows the of airplane detection uisng the regional cnn. 
    The implementation of regional cnn is demonstrated from scratch uisng Keras with tensorflow backend
 
        a. At first, the patches are extracted using the selective serach algorithm
        b. The patches are save in the "patches" folder for future use.
        c. Later the paches are splitted into in trianing, validation and test folder
        d. keras ImageDatagenerator is used to augment the images
        e. the keras.fit_generator function is used to trian the model
      
      In case of failing to open the "train_mrcnn.ipynb" file here, go to:https://nbviewer.jupyter.org/ 
      and paste https://github.com/Fashiar/Object_detection_-_classification/blob/master/region_cnn.ipynb to the viewer tab
      
2. region_cnn_v2.ipynb

    This notebook also shows the of airplane detection uisng the regional cnn. 
    The implementation of regional cnn is demonstrated from scratch uisng Keras with tensorflow backend
 
        a. At first, the patches are extracted using the selective serach algorithm
        b. The patches are save as .npy file format.
        c. Later the paches are splitted into in trianing and test set
        d. The above dataset is unbalanced, so calculate the class_weight to trian the unbalanced data set
        d. the keras.fit function is used to trian the model
      
      In case of failing to open the "train_mrcnn.ipynb" file here, go to:https://nbviewer.jupyter.org/ 
      and paste https://github.com/Fashiar/Object_detection_-_classification/blob/master/region_cnn_v2.ipynb to the viewer tab
