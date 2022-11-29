# YOLO
YOLO is a fast object detection algorithm. In this project, I have implemented YOLO-v1 using 10K street scene images to detect objects belonging to the vehicle, people and animal classes. The input data include the images along with the labels as training data. The image dimension is 128X128X3 and the labels consist of semantic class together with the bounding boxes corresponding to each object in the image.

# Network Architecture
![image](https://user-images.githubusercontent.com/42107613/204451561-c44b8f5b-adb1-4a6b-98ab-191b527adf1b.png)

# Loss Function
During training, the localization and classification errors are optimized jointly. The loss function is shown as below.  indicates number of grid cells and  indicates number of anchor boxes at each grid cell. In our case, there is only one anchor box at each grid cell.

![image](https://user-images.githubusercontent.com/42107613/204451937-0c675e2b-a4d9-4a0a-b906-1cb019730b99.png)
