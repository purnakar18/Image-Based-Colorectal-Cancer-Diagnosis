# Image-Based-Colorectal-Cancer-Diagnosis

'Final Report.pdf' is the report for the project.

For the Cancer detection problem:
1.	dataset used for training: ‘dualclass.zip’, dataset used for testing ‘test2class.zip’.
2.	codes for training models using Adam optimizer: \Adam optimizer\Cancer detection\Models
3.	codes for testing models using Adam optimizer: \Adam optimizer\Cancer detection\Test
4.	codes for training models using SGD optimizer: \SGD\Cancer detection\Models
5.	codes for testing models using SGD optimizer: \SGD\Cancer detection\Test


For tissue classification problem:
1.	dataset used for training: ‘converted.zip’, dataset used for testing ‘test9class.zip’.
2.	codes for training models using Adam optimizer: \Adam optimizer\ tissue classification\Models
3.	codes for testing models using Adam optimizer: \Adam optimizer\ tissue classification\Test
4.	codes for training models using SGD optimizer: \SGD\ tissue classification\Models
5.	codes for testing models using SGD optimizer: \SGD\ tissue classification\Test

Transfer Learning problem:

1.	For transfer learning on Lung cancer model: ‘lung cancer.zip’ was used to train the GoogLeNet model. 
2.	The pre-trained model was then used on ‘test2class.zip’ to train further
3.	The code for training on Lun cancer images \Adam optimizer\Transfer Learning\ GoogleNet_Lung_cancer.ipynb
4.	The code for Transfer learning \Adam optimizer\Transfer Learning\ GoogleNet_2_LCancerTL_test.ipynb
For segmentation problem:
1.	The dataset used for training UNET is ‘gland segmentation.zip’
2.	The dataset used to train googlenet on segmented images: ‘segmented images.zip’
3.	The code for training Unet model: \Gland Segmentation\ unet model.ipynb
4.	The code for training the segmented images in GoogleNet: \Gland Segmentation\Googlenet_segmented_(1).ipynb

For Traditional Methods
1.	The dataset used is ‘smalldata.zip’
2.	The code for LBP: \Traditional Methods\LBP.ipynb
3.	The code for Haralick: \Traditional Methods\Haralick.ipynb
4.	Code for training Googlenet: \Traditional Methods\Googlenet_small_dataset.ipynb

All weights of the models are in the path: \weights\
All datasets are in the path: \datasets\
