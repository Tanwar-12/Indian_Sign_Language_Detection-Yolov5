# Indian Sign Language Detection-Yolov5


### Overview : 
The purpose of this project is to create a Deep Learning model and  ISL detection technology involves the use of computer vision and artificial intelligence to recognize and interpret sign language gestures made by individuals who are deaf or hard of hearing.
### 📁 Dataset Used : https://universe.roboflow.com/yolov5-53hnk/isl-using-yolov5-0vwmd/dataset/7.
![image](https://github.com/Tanwar-12/Indian_Sign_Language_Detection-Yolov5/assets/110081008/1d96ecc4-b90e-4cf8-a4b0-c76856042a9e)


**The dataset consists of classes:**

0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z 
# Workflow:
  ## Data Preparation:
  * Total 2244 images for training and 213 images for validation present inclasses.
  * Create a bounding boxes with the help of label-img And makesense.ai website according to YoloV5.
  * Prepare folder structure that can be accept by YoloV5.
  

## Steps to use Yolov5:
* Cloning the YoloV5 file from official repository.
* Changing the directory of yolov5
* Installing the dependencies
* Download all versions pre-trained weights.

 ## Steps Before Training Custom Dataset:
* Go to yolov5/data/.
* Open data.yaml
* Edit the following inside it:

 1. Training and Validation file path
 2. Number of classes and Class names.
 3.  ## Training YOLOV5 Model
* Set images size 640 with batch of 8.
* Train model around 50 epochs .
* Visualise the training metrics with the help of tensorboard.

 ## Testing Images Using Test Data:
 ![image](https://github.com/Tanwar-12/Indian_Sign_Language_Detection-Yolov5/assets/110081008/0777da45-6890-4175-a1d6-63372973f15f)
![image](https://github.com/Tanwar-12/Indian_Sign_Language_Detection-Yolov5/assets/110081008/01955b8d-77d7-499f-a945-a388ee488225)

 



## Testing Video Demo:
 ISL detection technology involves the use of computer vision and artificial intelligence to recognize and interpret sign language gestures made by individuals who are deaf or hard of hearing.

  https://github.com/Tanwar-12/Indian_Sign_Language_Detection-Yolov5/assets/110081008/88d2d1bf-cd59-42dc-a2e5-6434f81aed79



