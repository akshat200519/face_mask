# Real-Time Face Mask Detection

This project implements a real-time face mask detection system using TensorFlow, OpenCV, and a pre-trained TensorFlow 2 Detection Model ZOO (SSD MobileNet V2 FPNLite 320x320). 
It is designed to detect whether individuals in a video stream are wearing face masks or wearing face masks incorrectly or not at all wearing.

## Features:
* Detects faces in real-time using SSD MobileNet v2 from OpenCV.
* Classifies each detected face as "with_mask" or "without_mask" or "mask_weared_incorrect" using a pre-trained model.
* Visualizes the results with bounding boxes and labels on the video stream.

## Prerequisites
* Python==3.7.4
* TensorFlow==2.10.1
* OpenCV
* protoc==libprotoc3.13.0
* object-detection

## Customization
* You could try different models of TensorFlow 2 Detection Model ZOO or try with your own custom models.
* Try training on a much larger dataset to increase exposure or the model.

## Contributing
Feel free to fork this repository.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Disclaimer
This project is provided for educational purposes only and should not be used in critical applications or rely on for public safety measures. 
The accuracy of the face mask detection may vary depending on factors like lighting, mask type, and occlusion.
