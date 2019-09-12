# Self Driving Car-TensorFlow
A TensorFlow implementation of this [Nvidia paper](https://arxiv.org/pdf/1604.07316.pdf) with some changes.

# How to Use
Download the [dataset](https://drive.google.com/file/d/0B-KJCaaF7elleG1RbzVPZWV4Tlk/view?usp=sharing) and extract into the repository folder Size: 25 minutes = 25*60*30 = 45,000 images ~ 2.3 GB

Use `python train.py` to train the model

Use `python run.py` to run the model on a live webcam feed

Use `python run_dataset.py` to run the model on the dataset

To visualize training using Tensorboard use `tensorboard --logdir=./logs`, then open http://0.0.0.0:6006/ into your web browser.

### Demo 
<img src="demo.gif">

- Credits: https://github.com/SullyChen/Autopilot-TensorFlow
- Research paper: End to End Learning for Self-Driving Cars by Nvidia. [https://arxiv.org/pdf/1604.07316.pdf]

- NVidia dataset: 72 hrs of video => 72*60*60*30 = 7,776,000 images
- Nvidia blog: https://devblogs.nvidia.com/deep-learning-self-driving-cars/
