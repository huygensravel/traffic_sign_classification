# Classification of Traffic Signs using AlexNet like CNN: 100% test accuracy
### Author: Huygens Ravelomanana
## Description
+ Using a similar AlexNet like configuration as for our AlexNet like architecture for CIFAR10 [https://github.com/huygensravel/AlexNet_for_cifar10](https://github.com/huygensravel/AlexNet_for_cifar10), we create, train, and evaluate a model that classify 43 types of traffic signs. The difference with our CIFAR10 architecture is that here we do not use local response normalization since here we have only one channel.
 
+ The model to tell which of 43 traffic signs a given picture belongs to.<br>
That is the model determine if an input image means/is:
	* **Stop sign**,
	* or **Speed limit 30km/h**,
	* or **Children crossing**,
	* **... etc**.<br>

We assign 43 distinct integers (or 43 canonical vectors  of size 43) to the 43 traffic signs then later in the modelling part we do hot-encoding.<br> 

## Organization
- We first give the problem statement and prepare the data in data_preparation_pblm_statmnt.ipynb
- We do the training / modelling part in modelling.ipynb
- The raw data is stored in data/raw.
- The processed data is stored in data/processed

## Result
**After evaluating the model on test (unseen) data we got 100% accuracy.**
## Origin of raw dataset
The raw dataset we use consist of about 51839 freely available images from the
[German Traffic Sign Recognition Benchmark (GTSRB)]( http://benchmark.ini.rub.de).

### 
J. Stallkamp, M. Schlipsing, J. Salmen, and C. Igel.<br>
The German Traffic Sign Recognition Benchmark: A multi-class classification competition.<br>
In Proceedings of the IEEE International Joint Conference on Neural Networks, pages 1453–1460. 2011.

@inproceedings{Stallkamp-IJCNN-2011,
    author = {Johannes Stallkamp and Marc Schlipsing and Jan Salmen and Christian Igel},
    booktitle = {IEEE International Joint Conference on Neural Networks},
    title = {The {G}erman {T}raffic {S}ign {R}ecognition {B}enchmark: A multi-class classification competition},
    year = {2011},
    pages = {1453--1460}
}
