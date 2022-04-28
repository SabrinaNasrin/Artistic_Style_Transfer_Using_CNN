# Artistic_Style_Transfer_Using_CNN
### MM805- Final Project
#### Date: April 27,2022

This project is done as a part of the MM-805 course.

##### Files:
* [sanet.py](https://github.com/SabrinaNasrin/Artistic_Style_Transfer_Using_CNN/blob/main/sanet.py)
* [SANet_training.py](https://github.com/SabrinaNasrin/Artistic_Style_Transfer_Using_CNN/blob/main/SANet_training.ipynb)
* Input folder containing content images
* Style folder containing the style images
* Output folders are also added for different models

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
* TensorboardX
* tqdm


##### How to run the code:
* Download the repository
* Open Google Colab
* Keep all the files in the repository in the same folder
* Download the pretrained models
* Change the location of style image, content image, pretrained models and the output directory
* run [sanet.py](https://github.com/SabrinaNasrin/Artistic_Style_Transfer_Using_CNN/blob/main/sanet.py)

##### How to train the model:
* run the [SANet_training.py](https://github.com/SabrinaNasrin/Artistic_Style_Transfer_Using_CNN/blob/main/SANet_training.ipynb)
* download the dataset as per notebook from kaggle and dependencies
* change the location of the datasets in the main code of training

#### Models
Download the pre-trained models for improved SANet from here: https://drive.google.com/drive/folders/1zW9E3xrMr1plYHxokdsHZ8DTR48S27_b?usp=sharing

#### Baseline Models
* Gatys: https://github.com/anishathalye/neural-style
* AdaIN: https://github.com/naoto0804/pytorch-AdaIN
* Avatar-net: https://github.com/tyui592/Avatar-Net_Pytorch
* Universal Style Transfer : https://github.com/irasin/Pytorch_WCT 
* SANet: https://github.com/GlebSBrykin/SANET
```
Run them through Google Colab follow the instructions as given in the repository and take the content and style images from this repository input folder.
```

```
Run in your local machine using Spyder or Visual Studio Code and Anaconda and take the content and style images from this repository input folder.

```

#### References

* L. Sheng, Z. Lin, J. Shao, and X. Wang, “Avatar-net: Multi-scale zero-shot style transfer by feature decoration,” in Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, 2018, pp. 8242–8250.
* L. A. Gatys, A. S. Ecker, and M. Bethge, “Image style transfer using convolutional neural networks,” in Proceedings of the IEEE conference on computer vision and pattern recognition, 2016, pp. 2414–2423.
* D. Y. Park and K. H. Lee, “Arbitrary style transfer with style-attentional networks,” in proceedings of the IEEE/CVF conference on computer vision and pattern recognition, 2019, pp. 5880–5888
* X. Huang and S. Belongie, “Arbitrary style transfer in real-time with adaptive instance normalization,” in Proceedings of the IEEE international conference on computer vision, 2017, pp. 1501–1510.
* Y. Li, C. Fang, J. Yang, Z. Wang, X. Lu, and M.-H. Yang, “Universal style transfer via feature transforms,” Advances in neural information processing systems, vol. 30, 2017.
