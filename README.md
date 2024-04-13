# RESNET-ON-CIFAR-10
In this project, we proposed a straightforward strategy to engineer Residual networks with fewer than 5M trainable parameters, thereby diminishing their memory requirements: 
Our experiments on the CIFAR10 dataset with custom ResNet architectures involving Squeeze and Activation Blocks and parameter sharing demonstrate that it is possible to maintain good accuracy despite reducing parameters.

## GETTING STARTED
```bash
git clone https://github.com/Navya0203/RESNET-ON-CIFAR-10.git
cd RESNET-ON-CIFAR-10
cd Main_Project_Model(checkpoint included)
```
Welcome to our project! To get up and running with the repository you've cloned, please follow the steps below:

1) First, navigate to the primary project directory titled `Main_Project_Model(checkpoint included)`. This directory is structured to contain everything you need to work with our custom ResNet model.

2) Within this directory, you'll find a Jupyter notebook named `MiniProject_Model(SE_Enhanced_Basic_ResNet)`. This notebook is your starting point for training the model and contains all the necessary code, from data preprocessing to the training loop.

3) Alongside the notebook, there's a model checkpoint file named `lat_model`. Code to create the checkpoint is present towards the end of the python file. 

4) To use the model checkpoint, you'll find the code snippet to load the saved model checkpoint at the end of the notebook. This allows you to quickly evaluate the model's performance and accuracy on the test dataset without the need to retrain the model from scratch.It is crucial that this checkpoint file is located in the same directory as the Jupyter notebook. This placement ensures that when you run the notebook, it can seamlessly locate and load the model checkpoint without any path issues.

5) To see the checkpoint model in action, simply go to the end of the `MiniProject_Model(SE_Enhanced_Basic_ResNet)` notebook. It has the code to load the checkpoint and use the `lat_model` checkpoint to instantiate the trained model, allowing you to validate the performance and accuracy on your no-label test dataset immediately.

By ensuring that the notebook and the model checkpoint are in the same directory, you'll be able to fully reproduce our environment and results, making your experience as smooth as possible. Enjoy exploring the capabilities of our custom ResNet model!


