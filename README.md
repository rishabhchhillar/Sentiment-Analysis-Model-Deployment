# Sentiment-Analysis-Model-Deployment

The aim of this project was to use the SageMaker, S3, Lambda and API Gateway services from AWS to train a Sentiment Analysis model using the IMDB reviews dataset and delpoy and use it on a simple web app, which takes as input a moview review and tells whether it is positive or negative.

    
  *This project is part of the Udacity Deep Learning Nanodegree*


## Viewing the Jyputer Notebook
In order to better view and work on the jupyter Notebook I encourage you to use [nbviewer](https://nbviewer.jupyter.org/) . You can simply copy and paste the link to this website and you will be able to edit it without any problem. Alternatively you can clone the repository using 
```
git clone https://github.com/rishabhchhillar/Sentiment-Analysis-Model-Deployment/
```
then in the command Line type, after you have downloaded jupyter notebook type
```
jupyter notebook
```
locate the notebook and run it.

## GPU
As the network makes use of a sophisticated deep convolutional neural network  the training process is impossible to be done by a common laptop. In order to train your models to your local machine you have three options

1. **Cuda** -- If you have an NVIDIA GPU then you can install CUDA from [here](https://developer.nvidia.com/cuda-downloads). With Cuda you will be able to train your model however the process will still be time consuming
2. **Cloud Services** -- There are many paid cloud services that let you train your models like [AWS](https://aws.amazon.com/fr/) or  [Google Cloud](https://cloud.google.com/)
3. **Coogle Colab** -- [Google Colab](https://colab.research.google.com/) gives you free access to a tesla K80 GPU for 12 hours at a time. Once 12 hours have ellapsed you can just reload and continue! The only limitation is that you have to upload the data to Google Drive and if the dataset is massive you may run out of space.

However, once a model is trained then a normal CPU can be used for the prediction and you will have an answer within some seconds.


## Authors

* **Rishabh Chhillar** 
* **Udacity**

## License

This project is licensed under the MIT License - see the (LICENSE.md) file.
