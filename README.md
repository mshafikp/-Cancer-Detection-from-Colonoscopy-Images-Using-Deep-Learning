# Cancer-Detection-from-Colonoscopy-Images-Using-Deep-Learning

Images from cases of gastrointestinal endoscopy were used. These were simply diagnosed as either benign or malignant. A deep learning model has been designed to construct an artificial intelligence based diagnostic application which is a convolutional neural network (CNN) implemented using TensorFow. CNNs are found to be one of the most popular network models for deep learning images. The CNN recognizes an image that has been fed as an input and the output is classification of the input image. There several of levels in CNN, where each neuron in a layer connects to the next neuron of preceding layer. The classifications were initially manually interpreted of all the tumor images in the training set and all the information were fed to the CNN architecture. The input image that is fed to the system represents the first layer of the architecture. The neurons associated in the first layer is usually 3 times to the number of pixels present in the input image. The trained application could identify the Region of Interests (ROI) by convolutional and pooling process. In the last and the final layer of the architecture, for each connection of the neural network, a parameter is associated that is adjusted by learning. Softmax function in python has been used to represent the output of the CNN model which in result was classification of the tumor into cancerous or not with values ranging from 0 to 1. The higher the value, the CNN was able to classify the ROI. The proposed application is able to detect and classify tumor from endoscopic images, proving the need of such algorithms in future AI based cancer diagnosis support system for endoscopy as computer-aid diagnosis using AI techniques has a high potential outperforms the accuracy of diagnostics of the health professionals and have a chance to provide more accurate results.

## Requirements
Python 3.5.4 or higher with Tensorflow installed

## Useage
Run the file retrain.py

A file "retrained_graph.pb" gets created
