# object_detection

In this repo, I am trying out different ways for straight-forward object detection that can be run on images or in real-time on a webcam.

The openCV approach is very straightforward, you can download a trained model, load it in with openCV and apply it for object detection on images. I followed [Adrian Rosebrock's blog post](https://www.pyimagesearch.com/2017/09/11/object-detection-with-deep-learning-and-opencv/) which gives a very good introduction.

Using the tensorflow object detection API gives more flexibility. They offer a variety of different pre-trained networks ranging from very fast to very accurate. It can be used for out-of-the-box object detection or as a starting point for applying transfer learning to train your own object detector. For more information and the necessary installation instructions, take a look [on their official github repo](https://github.com/tensorflow/models/tree/master/research/object_detection).
