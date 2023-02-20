## YOLOv4 Custom Object Detection ##

1. **YOLOv4 Object Detection:**  
source & tutorial (https://github.com/AlexeyAB/darknet)
   * yolov4_pred.jpg  
   ![yolov4_pred](https://github.com/tonyhsu32/YOLOv4-Custom-Object-Detection/blob/main/yolov4_pred.jpg)
   
   * YOLOv4-Object Detection-sample.png  
   ![sample](https://github.com/tonyhsu32/YOLOv4-Custom-Object-Detection/blob/main/YOLOv4-Object%20Detection-sample.png)
 
   * YOLOv4_drive_sample_1.jpg  
   ![drive_sample_1](https://github.com/tonyhsu32/YOLOv4-Custom-Object-Detection/blob/main/YOLOv4_drive_sample_1.jpg)  
   
   * YOLOv4_drive_sample_2.jpg  
   ![drive_sample_2](https://github.com/tonyhsu32/YOLOv4-Custom-Object-Detection/blob/main/YOLOv4_drive_sample_2.jpg)


2. **YOLOv4 Custom Colab GPU training:**  
Use ***Google Colab GPU Tesla T4***  
   * YOLOv4 Custom Object Detector.ipynb  
   * convert_annotations.py  
   * generate_test.py  
   * generate_train.py  
   * obj.data  
   * obj.names  
   * yolov4-obj.cfg -> (modifid yolov4-custom.cfg) 
   
Create a **custom dataset** with **3 classes(Airplane, Convenience store, Duck)**(each with **1500 images and annotations for training** and **300 images and annotations for testing**) by using the Open Images Dataset V6 (Google Datasets). 

Train the dataset using the ***darknet yolov4-custom.cfg*** and ***Colab GPU for 2000 iterations*** to achieve an ***mAP of 91%***. 
   * YOLOv4-mAP_91%.jpg  
   ![mAP](https://github.com/tonyhsu32/YOLOv4-Custom-Object-Detection/blob/main/YOLOv4-mAP_91%25.jpg)
   
   * YOLOv4-airplane.jpg  
   ![airplane](https://github.com/tonyhsu32/YOLOv4-Custom-Object-Detection/blob/main/YOLOv4-airplane.jpg)  
   
   * YOLOv4-convenience_store.jpg  
   ![convenience_store](https://github.com/tonyhsu32/YOLOv4-Custom-Object-Detection/blob/main/YOLOv4-convenience_store.jpg)
   
   
   
