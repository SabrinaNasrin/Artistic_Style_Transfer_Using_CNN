# Artistic_Style_Transfer_Using_CNN
### MM805- Final Project
#### Date: April 27,2022

This project is done as a part of MM-805 course.

##### Files:
* [sanet.py](https://github.com/SabrinaNasrin/Artistic_Style_Transfer_Using_CNN/blob/main/sanet.py)
* [SANet_training.py](https://github.com/SabrinaNasrin/Artistic_Style_Transfer_Using_CNN/blob/main/SANet_training.ipynb)
* Input folder containing content images
* Style folder containing style images
* Output_wct folder containing stylized images output obtained from Universal Style Transfer
* output AdaIN folder containing stylized images output obtained from AdaIN
* outputSANet folder containing stylized images output obtained from SANet
* output_Improved_SANet folder containing stylized images output obtained from Our model
* output_avatarnet folder containing stylized images output obtained from Avatarnet method
* output_gatys folder containing stylized images output obtained from Gatys method

##### IDE:
* Google Colab Pro

##### Language:
* Python 3.9

##### Dependencies:
Install the following libraries in the system:
* OS
* Torch
* TorchVision
* PIL
* argparse
* Kaggle
* Tensorboard


##### How to run the code:
* Download the repository
* Open Google Colab
* Keep all the files in the repository in the same folder
* 

#### Models
Download the pretrained models for improved SANet from here: https://drive.google.com/drive/folders/1zW9E3xrMr1plYHxokdsHZ8DTR48S27_b?usp=sharing

#### Baseline Models
* Avatar-net: https://github.com/tyui592/Avatar-Net_Pytorch
```
Run them through Google Colab follow the instructions as given in the repository and take the content and style images from this repository input folder.
```
* Universal Style Transfer : https://github.com/irasin/Pytorch_WCT 
```
Run in your local machine using Spyder or Visual Studio Code and Anacoda and take the content and style images from this repository input folder.

```

#### References

* Y. Jing, Y. Yang, Z. Feng, J. Ye, Y. Yu, and M. Song, “Neural style transfer: A review,” IEEE transactions on visualization and computer graphics, vol. 26, no. 11, pp. 3365–3385, 2019
* 
