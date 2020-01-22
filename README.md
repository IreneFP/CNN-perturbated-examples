# Perturbated examples in CNN 
Understanding the features a CNN uses to perform a classification between Caucasian and African-American faces by creating perturbated examples

Tilburg University Course - Deep Learning (CS&AI) with [Eric Postma](https://scholar.google.com/citations?user=EpsyWjIAAAAJ&hl=es) and [Sebastian Olier](https://scholar.google.it/citations?user=bc8UtIoAAAAJ&hl=en)

In this paper, I aimed to perform a very modest experiment to understand what features a convolutional neural network (CNN) uses to perform a simple binary classification task. The research question addressed in this paper reads as follows: Which features does a CNN classifier use when distinguishing between faces belonging to the Caucasian and the African-American race? The data set used belongs to the Face Place 3.0 [Tarr, 2008] public database.I addressed this research question with three hypothesize in mind of what the CNN could be looking at: (1) the facial expressions, (2) the shape and head position, (3) and the color. 

This study has been done by training a CNN and used it to predict perturbated images. I extracted the conclusions by analyzing how the probability of each prediction varies in each case. Eight different perturbations have been created in form of image filters, and some of them are image-level distortions while other are face-level distortions. Each perturbation is created to challenge an initial hypothesis. Some of these filters are inspired by the paper Unravelling Ro-bustness of Deep Learning based Face Recognition Against Adversarial Attacks [Goswami, Ratha, Agarwal, Singh & Vatsa, 2018], which created a framework to evaluate robustness of deep learning-based face recognition engines. Others are product of my own creation to address this specific task. 

The final abstract can be accessed [here](https://github.com/IreneFP/CNN-perturbated-examples/blob/master/IreneFontPeradejordi_DeepLearning_Experiment.pdf).
