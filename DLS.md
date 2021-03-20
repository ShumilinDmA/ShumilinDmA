#### Deep learning school

##### Semester One:
Deep learning school is the course from specialists and students from the Moscow Institute of Physics and Technology (MIPT)
The first part of this course was dedicated to Computer Vision tasks with a small portion of classical machine learning approaches.

Startings steps in this course were recapping some classical machine learning approaches with Sklearn and Pandas.
First homework was to write own linear model with regularizers by using only NumPy library.
After some recap lectures about the rest of ML algorithms like Random Forest, Gradient Boosting, Naive Bayes, etc was pretty challenging homework based on Kaggle
competition
 <img src="https://user-images.githubusercontent.com/64522272/111849264-d5401f80-8915-11eb-96ad-3d822001deee.png" width="15">
dedicated to churn prediction of a telecom company. In this competition among 671 participants, I took #3 place on the private part of the leaderboard.
In my solution I applied the ensemble of models consisting of 2 Random Forest models, 4 Gradient Boosting models, and logistic regression.
 
The next main step in the course was about deep learning. I studied the Pytorch dialect, classical architectures, optimization methods, and loss functions.
To prevent my models from overfitting there was explained a lot of regularisation technics to avoid it. As important homework here was also Kaggle competition
about the classification of Simpsons characters. It was a highly imbalanced dataset where I achieved a 0.99787 F1 score, only two images were misclassified!
 
From classification task the course went to segmentation with their main architectures: Unet, SegNet, DeepLab. Homework for segmentation lessons was about segmentation
medical images of leather lesions. In this task, I wrote both architectures Unet and SegNet from scratch and also their loss functions (Binary Cross-Entropy loss, 
Dice loss, Focal loss, Tversky loss). As a result - a comparison of both models with different loss functions.

From segmentation to detection task! There were perfect lectures about single-shot detectors with deep details. Also, it looked challenging and I took this theme
as a final project.

The last part of the course was dedicated to generative adversarial networks and neural style transfer tasks. From the lecture, I got information about general approaches in GANs
and some specific architectures Pix2Pix and CycleGAN. As homework here was the task to implement style transfer on an image by using 2 style images at the same time for 1 content image.

The first part of the course was finished by implementing the object detection project where I got a lot of new things about frameworks, web, scripting,
and data processing. This project available here [repo](https://github.com/ShumilinDmA/Object_detection_pet)

##### Semester two:
The second part of this course is dedicated to Natural Language Processing task.

In the beginning, much attention was paid to word embeddings. Here were considered classical approaches to convert words to numerical representations like
Bag of Words approach, Skip-grams, TF-IDF. There was homework about sentiment classification task of tweets based on the classical approach of converting
sentences to vectors. Later was considered Word2Vec embeddings, Glove embeddings with homework about text classification based on Pytorch implementations
of Recurrent Neural Networks and Convolutional Neural Networks (applying 1D kernel to a sequence of tokens)

Language modeling! In this part, we learned about creating a language model applying a probabilistic approach based on Markov chains. Next were introduced
approaches to language modeling by using deep RNN and CNN. For homework was task implement probabilistic model, also RNN and CNN to part of speech tagging
of text tokens.
##### Course still going and I really enjoy it so much! 

<br/><br>
More links:
* [Deeplearning.ai | Deep Learning Specialization]()
* [Yandex and MIPT | Machine Learning and Data Analysis Specialization]()
