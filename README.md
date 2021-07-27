# Image classification model using FastAI

##  Data extraction-> Training -> Evaluation-> Front end in Flask ->  Dockers -> Kubernetes

## Aim

To build and deploy a web application where an image of anime character is entered into a web-based form which then identifies the name.

For this, I created a image classification model from scratch and used Kubernetes for automating computer application deployment, scaling, and management.

Steps performed:

* Downloaded image of 4 different anime protagonist(200 for each categories) and created a custom dataset.

* Augmented the image to increase the size of the training set without acquiring new images.

* Used pre-trained ResNet18 Convolutional Neural Net model, and use transfer learning.

* Trained the model using Fast AI and hypertuned it.

* Evaluated and achieved the accuracy of 80% on validation dataset.

* Save the model and deploy a machine learning pipeline with a Flask app as a web service.

* Build a Docker image and upload it on Google Container Registry (GCR).
