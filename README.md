
# FaceNet-Authentication Application using flutter

Simple facial recognition authentication (Sign up + Sign in) developed in Flutter with Tensorflow Lite and the Google Machine Learning Kit library.

## Stack

### Flutter Framework
### Dart
### Data is being stored in the local storage, connecting to a cloud platform or any other database like Firebase or MongoDB is in progress and will be one of the key features of the further versions of the application.
## Mobilefacenet 
MobileFaceNet is a neural network and obtains accuracy upto 99.28 percent on labelled faces in the wild (LFW) dataset, and a 93.05 percent accuracy on recognising faces in the AgeDB dataset. The network used around a million parameters taking only 24 milliseconds to run and produce results on a Qualcomm Snapdragon processor. We can compare this performance to accuracies of 98.70 percent and 89.27 percent for ShuffleNet, which has many more parameters and takes a little longer to execute on the CPU.

### Tensorflow lite
TensorFlow Lite is an open source deep learning framework for on-device inference.

#### Flutter + Tensrorflow lite = tflite_flutter package 
TensorFlow Lite plugin provides a dart API for accessing TensorFlow Lite interpreter and performing inference. It binds to TensorFlow Lite C API using dart:ffi.

## Setup

1- Clone the project:

```
https://github.com/GurmanBhullar/Flutter-Face-Recognition-Authentication
```
2- Open the folder:

```
cd FaceRecognitionAuth
```
3- Install dependencies:

```
flutter pub get
```
4- Run on device (Check device connected or any virtual device running):

```
flutter run
```





