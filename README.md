# CV_Object_detection
YOLO Algorithm Basic For Object Detection

Object detection is a computer technology related to computer vision and image processing that deals with detecting instances of semantic objects of a certain class (such as humans, buildings, or cars) in digital images and videos. 
Object detection has applications in many areas of computer vision, including image retrieval and video surveillance.

There are two types of approach -
1. Non Neural approach
2. Neural approach

We will be dealing with the Neural Network approach.

Object detection can be done by any of the Neural approached listed below :

1. Region Proposals (R-CNN, Fast R-CNN, Faster R-CNN, cascade R-CNN)
2. Single Shot MultiBox Detector (SSD) 
3. You Only Look Once (YOLO) 
4. Single-Shot Refinement Neural Network for Object Detection (RefineDet)
5. Retina-Net 
6. Deformable convolutional network

YOLO - (You Only Look Once)
YOLO is a deep learning algorithm which came out in May 2016 and it became popular because it is fast compared to the other deep learning algorithms like R-CNN, Fast R-CNN , Faster R-CNN. There are many versions of YOLO algorithms. I am making use of Version 3 v3 for convinience. 

With YOLO we can detect objects at relatively high speed. With a GPU we would be able to process over 45 frames/second while with a CPU around 1 frame per second.

YOLO is a deep learning algorithm, so it doesn’t need any installation, what we need instead is a deep learning framework to run the algorithm.

The 3 most used and known frameworks compatible with YOLO and the advantages and disadvantages of each one are mentioned below :

1. Darknet : It is the framework built from the developer of YOLO and made specifically for YOLO.
   Advantage: It is fast, it can work with GPU or CPU
   Disadvantage: It olny works with Linux OS
2. Darkflow: It is the adaptation of darknet to Tensorflow (another deep leanring framework).
   Advantage: It is fast, it can work with GPU or CPU, and it’s also compatible with Linux, Windows and Mac.
   Disadvantage: The installation is complex, especially on windows
3. Opencv: Opencv has a deep learning framework that works with YOLO. Just make sure you have opencv 3.4.2 at least.
   Advantage: It works without needing to install anything except opencv.
   Disadvantage: It only works with CPU, so you can’t get really high speed to process videos in real time.
   

 YOLO with OpenCV is the best approach for beginners without any complex installations.


You can refer to the following links for better understanding :
https://www.pyimagesearch.com/2018/11/12/yolo-object-detection-with-opencv/
https://pysource.com/2019/06/27/yolo-object-detection-using-opencv-with-python/
