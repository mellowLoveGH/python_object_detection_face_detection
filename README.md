# python_object_detection_face_detection
python, object detection: YOLO, faster R-CNN, face detection: Viola-Jones. 

object detection seems more difficulte than face detection,
it needs to detect the place of the object, than classify it by using trained model (transfer learning) such as VGG.

face detection has several models, such as detection human faces, and human eyes.

目标识别，检测（估计）物体的位置和大小，然后识别该物体。
识别位置和大小，一般用的是YOLO或者faster R-CNN算法，YOLO比较快一点，但是效果可能faster R-CNN更胜一筹。
识别该物体，即是一般的分类问题，一般用已经训练好的模型来处理，这个就是迁移学习（transfer learning）。

人脸识别，有不同的模式，可以识别人脸、也可以识别人的眼睛。

