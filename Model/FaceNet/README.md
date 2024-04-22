# Data
http://vis-www.cs.umass.edu/lfw/lfw-deepfunneled.tgz

In the article introducing the FaceNet system (which made the Triplet function popular), Schroff et al 2015 use two datasets: Labeled Faces in the Wild (LFW) and YouTube Faces DB. I will be using the LFW dataset. Mind that LFW official website warns that LFW is "a public benchmark for face verification" and not suitable for commercial-grade face recognition systems, but for the purpose of this Notebook it's good enough.

LFW consists of 13.000 images collected from the internet. Each image is labelled with the name of the person in the image.

The number of images per person varies. Therefore I will use and train faces of people with 5 or more photos

# Model
Implement FaceNet using SiameseNet with transfer learning model Inceptionv3

# References
https://www.kaggle.com/code/mishki/face-recognition-keras-facenet-inception-model#Tansfer-learning  