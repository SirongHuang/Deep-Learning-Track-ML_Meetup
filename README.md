# Deep learning track
Four week deep learning course + coding assignment --> Kaggle competition <br>
:exclamation:= Compulsory materials and assignments

## Week 1 - Deep learning basics & Image classification
#### Course material: 
- Theory:
  - [MIT Introduction to Deep Learning](https://www.youtube.com/watch?v=JN6H4rQvwgY)
  - [MIT Computer Vision with Convolution Neural Network](https://www.youtube.com/watch?v=NVH8EYPHi30)
  - [Stanford Convolutional Neural Networks](https://www.youtube.com/watch?v=vT1JzLTH4G4&list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv)
- Practice:
  - :exclamation:[Fastai Image Classification](https://course.fast.ai/videos/?lesson=1) 
  - :exclamation:[Fastai Data Cleaning and Production & Gradient Descent](https://course.fast.ai/videos/?lesson=1)

#### Coding assignment: Implement an image classifier with any dataset

1. :exclamation: Build a Notebook from [a cloud server](https://course.fast.ai/start_kaggle.html)
    - Lecture dataset: [The Oxford-IIIT Pet Dataset](https://www.kaggle.com/tanlikesmath/the-oxfordiiit-pet-dataset)
      - Other interesting image datasets:
        - [Stanford Dogs Dataset](https://www.kaggle.com/jessicali9530/stanford-dogs-dataset/home) 
        - [Dogs vs Cats](https://www.kaggle.com/c/dogs-vs-cats)
        - [Fruits dataset](https://www.kaggle.com/moltean/fruits)
        - many more ... 
2. :exclamation: Minimum requirement: Implement using Fastai library<br>
=>&nbsp;  Beyond minimum requirement:
      - Implement with Keras, Pytorch, Tensorflow etc.
      - Explanation / visualization of concepts  
3. Send the link of your notebook with this [Google form](https://goo.gl/forms/8wimYUJgtAwDtTm42) (all notebook links will be posted here)
4. Present your code in next workshop 

##### Notebooks
| Name        | Notebook           | Code  |
| ------------- |:-------------:| -----:|
| Aditya     | [Lecture 1](https://www.kaggle.com/adityajitta/fastai-lecture-1-explore) | fastai |
| Rong     | [Image classification: clothing](https://github.com/SirongHuang/Deep-learning-workflow/blob/master/image_classification.ipynb)      |   fastai, opencv |
| Ruben | [Pets dataset Keras implementation](https://www.dropbox.com/s/ws1uahjwp13fj3t/Pet%20dataset%20keras%20v2.ipynb?dl=0)      |   Keras |
| Qingli | [Lecture 1 ](https://github.com/QingliGuo/Machine_Learning/blob/master/Image_Classification.ipynb)      |   fastai | 

#### Workshop:
- Presentation of codes and concepts
- Coding challenge - to be decided

## Week 2 - Deep learning Image classification
#### Course material:
- Theory:
  - (Optional) Papers that explain finding learning rate [Paper1](https://arxiv.org/abs/1506.01186)  [Paper 2](https://arxiv.org/abs/1803.09820)
  - (Optional) [Bag of tricks for training CNNs](https://arxiv.org/abs/1812.01187)
  - (Optional and very helpful) [Troubleshooting Deep Neural Networks](http://josh-tobin.com/assets/pdf/troubleshooting-deep-neural-networks-01-19.pdf)
- Practice:
  - :exclamation:Fastai Image Classification [Lecture 2](https://course.fast.ai/videos/?lesson=2) [Lecture 3](https://course.fast.ai/videos/?lesson=3)
  - :exclamation:Fastai NLP [Lecture 4](https://course.fast.ai/videos/?lesson=4) Interesting ideas i.e. `learn.freeze_to()`

#### Coding assignment: Implement an image classifier (continued from week 1)
1. Another interesting dataset for image classification task
    - [Mushrooms dataset](https://www.kaggle.com/maysee/mushrooms-classification-common-genuss-images)
2. Send the link of your notebook with this [Google form](https://goo.gl/forms/8wimYUJgtAwDtTm42) (all notebook links will be posted here)
3. Present your code in next workshop 

#### Workshop:
- Presentation of codes and concepts
- Coding challenge
    - (Option 1) Classification of mushroom images 

##### Notebooks
| Name        | Notebook           | Code  | Accuracy |
| ------------- |:-------------:| -----:|-----:|
| Aditya     | [Image classification: Mushrooms](https://github.com/gradjitta/ds_project_template/blob/master/Mushroom%20Classification%20FastAI%20ResNet34%2087.ipynb) | fastai |87 |
| Salih     | [Image classification: Mushrooms](https://www.kaggle.com/salihb/mushrooms-classification-using-keras) | keras |89 |

## Week 3 - Backprop and CNN deep dive
#### Course material: 
- Theory:
  - (Optional) Heatmaps generated by `interp.plot_top_losses` [Grad-CAM heatmaps](http://openaccess.thecvf.com/content_ICCV_2017/papers/Selvaraju_Grad-CAM_Visual_Explanations_ICCV_2017_paper.pdf)
  - (Still very helpful) [Troubleshooting Deep Neural Networks](http://josh-tobin.com/assets/pdf/troubleshooting-deep-neural-networks-01-19.pdf)
  - (Optional)[CNN visualization repo](https://github.com/utkuozbulak/pytorch-cnn-visualizations), [Deep visualization repo](https://github.com/yosinski/deep-visualization-toolbox)
  - (Optional)[CNN visualization paper](https://cs.nyu.edu/~fergus/papers/zeilerECCV2014.pdf)
- Practice:
  - :exclamation:Fastai Lectures [Lecture 5](https://course.fast.ai/videos/?lesson=5) [Lecture 6](https://course.fast.ai/videos/?lesson=6)
#### Coding assignment: Improve your models
1. Ideas from the session
    - Use custom FeedForwardNet to replace the simple one provided by Fastai
    - Experiment with `learn.fit` which uses Cosine learning rates
    - More experiments: unfreeze more last layers, lower weight decay `wd` (allows for higher learning rate) and [bayesian NN](https://github.com/paraschopra/bayesian-neural-network-mnist/blob/master/bnn.ipynb)
2. Send the link of your notebook with this [Google form](https://goo.gl/forms/8wimYUJgtAwDtTm42) (all notebook links will be posted
 here)
#### Notebooks
| Name        | Notebook           | 
| ------------- |:-------------:| 
| Aditya     | [Understanding grads and hooks](https://www.kaggle.com/adityajitta/understanding-grads-and-hooks)|
| Rong     | [Understanding Pytorch Hooks](https://www.kaggle.com/sironghuang/understanding-pytorch-hooks?scriptVersionId=11851979)|
| Rong     |[Visualizating CNN slides](https://github.com/SirongHuang/Deep-Learning-Track_Machine-Learning-Meetup/blob/master/Visualizing_cnn_compressed.pdf)|
3. Present your code in next workshop

## Week 4 - Kaggle competition kick-off and team formation
:exclamation: [Join teams in this Google form](https://goo.gl/forms/nUYJ4NF4Xqeh4onA3)

## Final project - [Earthquake Kaggle competition](https://www.kaggle.com/c/LANL-Earthquake-Prediction)
Select 8 most active and contributive members near the end of the course. May divide into teams if there are more than 8 participants. 

## Q & A:

**Q: Why Fastai?**<br><br>
A: Fastai is a high level library that implements cutting edge deep learning algorithms. It allows anyone to start implementing deep learning quickly with world-class performance and it's being used frequently in top Kaggle submissions. Fastai has excellent automation for data loading and data preprocessing. Even you wish to use other deep learning libraries to implement the models, these helper functions will still help with the boring tasks.

All in all, it's great place for beginners to start, and a valuable tool for experienced data scientist. 
<br><br>
**Q: I want to learn how Deep Learning models are implemented from scratch but Fastai makes models appear as block boxes. Why don't we learn Tensorflow or Pytorch instead?**<br><br>
A: It could take months to study deep learning theories and implement everything with Tensorflow or Pytorch from scratch. Also, not everyone is interested in theory and implementation details. Fastai offers a **minimum requirement** to understand and implement deep learning models, which is a good point to jump start. 
<br><br>
If you are curious to learn more, you could study on your own from our recommended resources and numerous online resources. You are also encouraged to implement with other deep learning frameworks and share your codes in the weekly workshop. 
