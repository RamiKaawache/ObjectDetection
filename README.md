I developed a Python application demonstrating real-time object detection and image classification using pre-trained 
deep learning models with OpenCV’s dnn module. The project is split into two components:

Object Detection with MobileNetSSD
Utilized the MobileNetSSD model trained on the COCO dataset to detect and label objects in real-time from a webcam feed. 
The model identifies classes such as person, car, dog, etc., drawing bounding boxes and confidence scores around detected objects.

Image Classification with GoogLeNet (ImageNet)
Implemented an image classifier using the GoogLeNet architecture pre-trained on ImageNet. 
The system processes an input image, runs forward inference, and displays the top predicted label along with its confidence percentage, 
visually overlaying the result on the image.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE.txt) file for details
