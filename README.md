# HardHead-Detection-for-Safety-Surveilance
HardHead Detection for Safety Surveilance

## **Problem Statement** - [sharepoint link](https://wobotintelligence-my.sharepoint.com/personal/hr_wobot_ai/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fhr%5Fwobot%5Fai%2FDocuments%2FHackathon%2D%20Extended%20%288th%20August%29%2FHackathon%204%2E0%2Epdf&parent=%2Fpersonal%2Fhr%5Fwobot%5Fai%2FDocuments%2FHackathon%2D%20Extended%20%288th%20August%29&originalPath=aHR0cHM6Ly93b2JvdGludGVsbGlnZW5jZS1teS5zaGFyZXBvaW50LmNvbS86YjovZy9wZXJzb25hbC9ocl93b2JvdF9haS9FWU1KcVBRUWpDMUVrZ1JWZi1qMEdYTUJJTy0taEQ3YjBBX1JqRXZ4dnNfTnJRP3J0aW1lPTlHcjFXcjlkMlVn)

• **Task: Build A Personal Safety Equipment Detection System**

#### Dataset Details:•
   * Hardhat/ head detection dataset is available here - [Dataset Link](https://wobotintelligence-my.sharepoint.com/personal/animikh_wobot_ai/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fanimikh%5Fwobot%5Fai%2FDocuments%2FHackathon%2FDataset&originalPath=aHR0cHM6Ly93b2JvdGludGVsbGlnZW5jZS1teS5zaGFyZXBvaW50LmNvbS86ZjovZy9wZXJzb25hbC9hbmltaWtoX3dvYm90X2FpL0Vnc3hvcTV6YW1wUGpmbm9KbFB6X3owQkFyODdLWGttSXZZNkRLclRDTnltYWc%5FcnRpbWU9eGxyZ1J2OWMyVWc)
#### Dataset annotation format: Pascal VOC (XMLs)
#### Dataset Size:
* Data with Annotations: 4,750
* Data without Annotations (Test): 250

## **Collab Implemenetation**

The entire **Helmet/Head object detection** implementation pipeline using **YoloV3** can be found here **[colab_notebook](https://colab.research.google.com/drive/1Z3Y62pOOKiU1cuIMkFWf5j2udOcW14N5?usp=sharing)**

## **Sample Result**

Sample Helmet and Head detection results can be found here.

Helmet detection
![Image1](https://github.com/sayan0506/HardHead-Detection-for-Safety-Surveilance-using-YoloV3/blob/main/Images/helmet_1.jpg)

Head detection - Here we can find that as in the dataset there are less head data as compared to helmet sets, so the model is not that good enough in finding heads in the 1st image. For this 2nd clean single person image head detection though is good.

![Image2](https://github.com/sayan0506/HardHead-Detection-for-Safety-Surveilance-using-YoloV3/blob/main/Images/head_1.jpg)
![Head2](https://github.com/sayan0506/HardHead-Detection-for-Safety-Surveilance-using-YoloV3/blob/main/Images/head_2.jpg)

Here also helmet detection result is quite good enough

![Helmet_2](https://github.com/sayan0506/HardHead-Detection-for-Safety-Surveilance-using-YoloV3/blob/main/Images/helmet_2.jpg)

## **Note :**

* The project details and workings files can be found here - [Drive Link](https://drive.google.com/drive/folders/1zKN6qu5KjsXS4mlESZPjD_TKHf9-Zfcc?usp=sharing)
* A guide to the project documentation can be found [here]()

## **Reference:**

* [Dive Really Deep into YOLO v3](https://towardsdatascience.com/dive-really-deep-into-yolo-v3-a-beginners-guide-9e3d2666280e)
* [Real-time Object Detection with YOLO, YOLOv2 and now YOLOv3
](https://jonathan-hui.medium.com/real-time-object-detection-with-yolo-yolov2-28b1b93e2088)
* [mAP (mean Average Precision) for Object Detection](https://jonathan-hui.medium.com/map-mean-average-precision-for-object-detection-45c121a31173)
* [Automatic Hardhat Wearing Detection - Caffe](https://github.com/wujixiu/helmet-detection)
* [Hardhat (Helmet) detection from construction site using YOLOv3_tiny with TensorFlow](https://github.com/rashidch/Yolov3_tiny-Hardhat-detection_Tensorflow)
* [Helmet Detection using YOLOv2 in Keras](https://github.com/rekon/keras-yolo2)
* [YoloV3 Implemented in TensorFlow 2.0](https://github.com/zzh8829/yolov3-tf2)
* [Faster video file FPS with cv2.VideoCapture and OpenCV](https://www.pyimagesearch.com/2017/02/06/faster-video-file-fps-with-cv2-videocapture-and-opencv/)
* [Writing a training loop from scratch in Tensoorflow](https://www.tensorflow.org/guide/keras/writing_a_training_loop_from_scratch)
