# Implementation 
ResNet34 was used as a decoder for the U-net network architecture. 
The network is trained on images of size 384. 
In the future, it can be trained to a larger size.

task: 
https://www.kaggle.com/c/airbus-ship-detection/overview
This approach was chosen because the ratio of pixels of ships to non-ships is very unbalanced, and it makes no sense to train the network on large images at once, as this will only increase the training time  

# Setup 
 python version: Python 3.6.4 :: Anaconda custom (64-bit)
 Run pipenv enviroment with `pipenv shell`
 install all the libraries from requirements.txt
 [Download weights](https://drive.google.com/file/d/1GXtzxA8plwZEfGU5_aoJuGTNsj5WpMSD/view?usp=sharing) and put in directory `notebooks/Resnet34_lable_384_1.h5`
 Download dataset from task and put it in directory `./input/airbus-ship-detection/ <files>`
 
# Credits 
It is also important to note these notebooks that helped in completing this task and understanding it.
https://www.kaggle.com/code/iafoss/unet34-dice-0-87
https://www.kaggle.com/code/iafoss/unet34-submission-tta-0-699-new-public-lb
https://www.kaggle.com/code/julian3833/4-exploring-public-models
https://www.kaggle.com/code/inversion/run-length-decoding-quick-start
https://www.kaggle.com/code/iafoss/fine-tuning-resnet34-on-ship-detection
https://www.kaggle.com/code/julian3833/3-basic-exploratory-analysis