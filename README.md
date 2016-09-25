# Tensorflow-real-time-video-analysis

##Introduction:
Tensorflow provides many powerful libraries for object detection and segmentation in images. In this increment, I tried to implement one such advancement in deep learning, The Inception Architecture, for detection and segmentation of objects in images and generating captions to explain objects in images. The system, currently in development, can automatically generate captions from input images.
##Objectives:
Design a real-time video analysis system using deep learning framework Tensorflow.
Automatically detect objects in video and segment them. The system will be pre-trained on training datasets and a model is generated. Based on available computing resources the video is divided into 30/60 frames/second and objects will be classified/detected and segmented.
Automatically generate captions for currently displayed frames. It can be helpful in assisting blind people. 

##Data sources:
Microsoft COCO image caption generation, object segmentation and dataset for training the inception architecture. 

Flickr30k image Dataset for training and testing the generated image captions.

##Tools: 
Tensorflow
Google Protobuf
NumPy
Keras
OpenCV
scikit-image 

##Sample Input/Output
Training the model requires significant GPU computing power. After training the model for some time on my local machine, the results are not that good. There are pre-trained models available on the same Flickr 30k dataset, I tested my input images on one of such [model](https://drive.google.com/file/d/0B5o40yxdA9PqeW4wY0wwZXhrZkE/view) made available by the user Taeksoo Kim [@jazzsaxmafia](https://github.com/jazzsaxmafia).  

###Input

![](https://cloud.githubusercontent.com/assets/16812117/18818788/faeca41a-8348-11e6-8a2c-de4ae38dce4b.jpg)

###Output

Testing the model on the same image multiple times, results in different output each time.

![](https://cloud.githubusercontent.com/assets/16812117/18818772/75147110-8348-11e6-92d4-9bff09fa2bbe.PNG)

![](https://cloud.githubusercontent.com/assets/16812117/18818848/26f287d6-834a-11e6-9cd0-8d66a1e4c2d4.PNG)


As the model is not fully trained, it wrongly predicted university sign-board as a man in blue shirt.



##References:
[1]. Vinyals, Oriol, et al. "Show and Tell: Lessons learned from the 2015 MSCOCO Image Captioning Challenge." (2016).

[2]. He, Kaiming, et al. "Deep residual learning for image recognition." arXiv preprint arXiv:1512.03385 (2015).

[3]. https://github.com/tensorflow/tensorflow

[4]. Donahue, Jeffrey, et al. "Long-term recurrent convolutional networks for visual recognition and description." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2015.

[5]. Cho, Kyunghyun, Aaron Courville, and Yoshua Bengio. "Describing multimedia content using attention-based encoder-decoder networks." IEEE Transactions on Multimedia 17.11 (2015): 1875-1886.

[6].  https://research.googleblog.com/

[7]. https://github.com/tensorflow/models/tree/master/im2txt#a-note-on-hardware-and-training-time

[8]. https://github.com/jazzsaxmafia/show_and_tell.tensorflow

[9]. http://mscoco.org/

[10]. http://shannon.cs.illinois.edu/DenotationGraph/


