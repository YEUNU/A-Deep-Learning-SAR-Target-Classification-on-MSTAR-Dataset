# A-Deep-Learning-SAR-Target-Classification-on-MSTAR-Dataset

## 1. Outline

This project is based on the university class (hannam.ac.kr).

basic paper : https://www.researchgate.net/publication/323587302_A_Deep_Learning_SAR_Target_Classification_Experiment_on_MSTAR_Dataset


## 2. Goal

Make same accuracy as basic paper (91%)

## 3. information

SAR data has many features magnitude, real, imaginary.

Traditionary researcher uses only magnitude datas.

but in this paper, using all feature affects on accuracy

SAR : https://en.wikipedia.org/wiki/Synthetic-aperture_radar

## 4. Result

Only Magnitude data : 88 % 

All data : 91 %

## 5. Parameter

Epoch : 40

Batch Size : 32

learning Rate : 0.001

Loss Function : MultiLabelSoftMarginLoss(with Softmax Layer)

Optimizer : Adam

random seed : 77

Model : CNN
