# TaskGrad

# Requirements
* python 3.8
* pytorch 2.0.1
* Numpy 1.25.1
* torchvision
* 
# Training
1. Download the training datasets for eight tasks and put them into ' /datasets/'
  
2. Download pre-trained model SMT
  
3. Modify paths of datasets, then run torchrun --nproc_per_node=4 TaskGrad_train.py in the terminal.


# testing
1. Download the pre-trained models, and put them in './models/'.

2. Modify paths of datasets.

3. Run TaskGrad_test.py.
