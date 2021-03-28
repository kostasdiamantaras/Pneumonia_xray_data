# Pneumonia_xray_data

Chest X-rays from 3 classes: normal, bacterial pneumonia, viral pneumonia

### Context

This dataset is about detecting two types of pneumonia (from bacterial infection or from a viral infection) using chest X-Ray images. The images are gray-scale with various sizes. There are 3 image classes:  

* Class 0: no disease  

* Class 1: bacterial pneumonia  

* Class 2: viral pneumonia



### Content

The data are split into two folders:  

* Folder `train_images` contains 4672 train images, out of which  

    - 1227 images belong to class 0  
    - 2238 images belong to class 1  
    - 1207 images belong to class 2  

* Folder `test_images` contains 1168 test images  

The file `labels_train.csv` contains the class labels of the images in the form of pairs  

*file\_name*, *class\_id*  

where  

* *class\_id* = 0 if the image corresponds to a subject without disease (normal)  

* *class\_id* = 1 if the image corresponds to a patient with bacterial pneumonia  

* *class\_id* = 2 if the image corresponds to a patient with viral pneumonia


### Acknowledgements

The data are adapted from the [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia) dataset  where images are labeled as either *normal* or *pneumonia*. The original filenames of class pneumonia, however, contained information regarding the type of pneumonia (bacterial or viral), so it was possible to re-label the images using the three classes mentioned above. The original train and test sets where merged and then re-split into a train set (80%) and a test set (20%). The files were renamed as *img_NNN.jpg* where *NNN* = random 17 digit code.

Original Data: https://data.mendeley.com/datasets/rscbjbr9sj/2

License: CC BY 4.0

Citation: http://www.cell.com/cell/fulltext/S0092-8674(18)30154-5

