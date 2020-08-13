# Classification of Traffic Signs using LeNet CNN

## Description
We construct a LeNet type Convolutional Neural Network model and train the model to tell which of 43 traffic signs a given picture belongs to.<br>
That is the model determine if an input image means/is:
* **Stop sign**,
* or **Speed limit 30km/h**,
* or **Children crossing**,
* **... etc**.<br>

We assign 43 distinct integers (or 43 canonical vectors  of size 43) to the 43 traffic signs.<br>

## Organization
- We first give the problem statement and prepare the data in data_preparation_pblm_statmnt.ipynb
- We do the training / modelling part in modelling.ipynb
- The raw data is stored in data/raw.
- The processed data is stored in data/processed

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
