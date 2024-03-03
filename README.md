# Food_Identification_CNN
Check out the related post on [Medium](https://medium.com/@pwrxndr/pytorch-transfer-learning-how-to-choose-the-right-model-ed4ad94c8b02)

Here I am striving to experiment with the [dataset](https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/)
which contains more than 100,000 different pictures of food.

I am using this dataset to tackle the capabilities of PyTorch and Convolutional Neural Networks (CNN). The models are based on the EfficientNetB0, EfficientNetB1, EfficientNetB2 weights for model creation, which were trained on ImageNet.

First attempt is focused on building a small imperfect sample with only 3 food categories: Sushi, Pizza, Steak.
to understand possible pros and cons of different approaches without killing your computers CPU.

Afterwards I am going to gradually enlarge the model and its working samples.

The ultimate goal is to build a model that is going to be able to identify custom dataset with High Accuracy and further proceed to creation the "NutriVision" App.
