# ObjectCountingCNN
Jupyter Notebooks used in my Master's thesis. 

Abstract from thesis:

My goal with this paper was to check if neural network could count like a human,
i.e. to specify a small number of objects without counting them one by one.
Initially a dataset was needed, but due to the nature of the problem we couldn’t find
one. I had to generate itmyself, which made learning the network a bit more difficult
when considering the possibilities of the subject. Initially, I wanted this network to
be able to count objects from real photos, but it would take a much larger dataset
than I created for it to work satisfactorily. I was unable to generate an image with
various real-world objects with the code, so images with various figures were generated.
I created several models where I checked the effect of hyperparameters on
a given problem. Later I compared the best model with the already made structure -
ResNet50v2.



I compared the models with each other by the following scores:  
• validation accuracy - accuracy in a set which wasn’t used in a training (validation
set)  
• validation loss - the difference between real class and the class selected by model
in a validation set

Keywords: **Python, Keras, Deep Learning, classification, counting**
