Problem Statement:
In this project, we have to take aligned images from CelebA dataset and detect whether they have specific attributes.
The attributes we are interested in are: (male/female; smile/not; mustache-beard/not; bangs/not; eyeglasses/not; hat/not; blonde/not; pale skin; attractive/not; blurry/not).
This is basically a multi-label classification problem which aims to target multiple attributes.
Therefore, we will develop a model which have an output layer with 10 neurons.

Developed a multilabel classifier CNN using pre-trained VGG16 model on Python's Keras library to label each face image on CelebA dataset with specific attributes. 

Data: http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html
