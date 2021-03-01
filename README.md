# Deep-Learning Project
In this project we have designed a smart system capable of performing image classification and accurate real time recognition which will take the picture and Analyze the image using TensorFlow and detect what is that picture is about, then Using a speaker or headphone, the voice assists the person about that picture.

How it works -
Step 1: Firstly, we capture an image using the raspberry pi 3 model B camera
module.
Step 2 : Save the captured image where the trained model is saved.
Step 3 : That image is passed to our trained model - train.py
Step 4: That image is analyzed using Tensorflow.
Step 5: Predicted output is converted to sound - predictions.py

In this we are using CIFAR10 Library which have 60,000 images out of which 50,000 images are training images and 10,000 are testing images. The image will be captured by the camera module of the raspberry pi 3 model b. This captured image will be passed to our trained model and then we will detect all the objects or obstacles present in the image.

Software requirements : 
1. Raspbian os: Raspbian is a Debian-based computer operating system for Raspberry Pi. There are several versions of Raspbian including Raspbian Stretch and Raspbian Jessie.
2. Tensorflow: TensorFlow is an end-to-end open source platform for machine learning. It has a comprehensive, exible ecosystem of tools,libraries and community resources that lets researchers push the state-of-the-art in ML and developers easily build and deploy ML powered applications.
3. Open CV: OpenCV (Open source computer vision) is a library of pro-gramming functions mainly aimed at real-time computer vision.
4. keras: Keras is an open-source neural-network library written in Python. It is capable of running on top of TensorFlow, Microsoft Cognitive Toolkit, Theano, or PlaidML.
5. espeak:eSpeak is a compact open source software speech synthesizer for English and other languages, for Linux and Windows.

Hardware Requirements : 
1. Raspberry pi 3: The Raspberry Pi 3 Model B is a tiny credit card size computer. Just add a keyboard, mouse, display, power supply, micro SD card with installed Linux Distribution and you'll have a fully edged computer that can run applications from word processors and spreadsheets to games.
2. Camera module:The Raspberry Pi Camera Module v2 is a high quality 8 megapixel Sony IMX219 imagesensor custom designed add-on board for Raspberry Pi, featuring a fixed focus lens. It'scapable of 3280 x 2464 pixel static images, and also supports 1080p30, 720p60 and640x480p90 video.
3. Speaker: This is for hearing the voice commands.
4. Button: When the button is pressed then the image is captured.

![image](https://user-images.githubusercontent.com/50194117/109481900-5e94cc80-7aa3-11eb-9663-39c4aae253f8.png)

CIFAR10 Dataset: The dataset is comprised of 60,000 32x32 pixel colour photographs of objects from 10 classes such as frogs, birds, cats, ships, etc.
The class labels and their standards associated integer values are listed below:
 0: Airplane
 1: Automobile
 2: Bird
 3: Cat
 4: Deer
 5: Dog
 6: Frog
 7: Horse
 8: Ship
 9: Truck

References : https://www.tensorflow.org/datasets/catalog/cifar10


