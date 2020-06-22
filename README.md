# Traffic-Sign-Detection

Start training by using the following steps:

For training yolo-obj.cfg download the pre-trained weights-file (162 MB): https://drive.google.com/file/d/1JKF-bdIklxOOVy-2Cr5qdvjgGpmGfcbp/view

Move the yolov4.conv.137 file to the darknet directory.

cd darknet/

./darknet detector train data/obj.data yolo-obj.cfg yolov4.conv.137

File "yolo-obj_last.weights" will be saved to the backup\ for each 100 iterations.

File "yolo-obj_xxxx.weights" will be saved to the backup\ for each 1000 iterations.

For more information visit the site: https://github.com/AlexeyAB/darknet#how-to-train-to-detect-your-custom-objects
