# How Train Yolov3

1. Download LabelImg in https://tzutalin.github.io/labelImg/
2. Labeling Image (you can see in my Medium https://bimap98.medium.com/how-to-train-yolo-v3-45120ead54bb)
3. Setting this bellow picture
<img src= "Screenshot_2.jpg">
4. But that's not absolute, you can see documentation in here (https://github.com/AlexeyAB/darknet#how-to-train-to-detect-your-custom-objects)
<br>
5. Train
<br>
6. Anyway the results will be like this, weights results each 1000 iteration
<img src= "Screenshot_3.jpg">
8. Let's test in yolo_object_detection.py and also dont forget set where thats weights and config from "net = cv2.dnn.readNet("yolov3_training_last.weights", "yolov3_testing.cfg")
<br>
7. This result our model
<img src= "Screenshot_4.jpg">
8. For config you can find here https://github.com/AlexeyAB/darknet/blob/master/cfg/yolov3.cfg or you can download in my repository
9. If you have any issue you can up Issues in my github repository
