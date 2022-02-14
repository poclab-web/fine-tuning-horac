# fine-tuning-horac

# Title
Predicting Hydrophilic Oxygen Radical Absorption Capacity Using Transfer Learning and Fine-Tuning

# Abstruct
In recent years, obtaining sufficient labeling data for time-consuming measurements or samples that contain target substrates in limited quantities has become more difficult. One example is the measurement of antioxidant capacity. Methods such as transfer learning and fine-tuning are effective in such cases. In this study, a model for predicting the hydrophilic oxygen radical absorption capacity was created by calculating bond dissociation enthalpy related to the reaction of antioxidants by creating a pre-training model and fine-tuning it. Using this method, we were able to improve the generalization performance of the prediction model.

# Program
*X = radius of Morgan fingerprint (2 or 3)*

H_ORAC_onlyX.ipynb : no fine-tuning (H_ORAC.csv)

QM9_X.ipynb : QM9 potential energy (pre-training, qm9.pickle)  

*Y = BDE, IP, PDE, PA, ETE(pre-training)*

TCI_X_Y.ipynb : compounds sold at Tokyo Chemical Industry Co., Ltd. (BDE_t.csv)

ori_X_Y.ipynb : virtual compounds (bde_list.csv)


# Requirements
Python 3.7

rdBase 2020.09.1

tensorflow 2.4.0

Keras 2.4.3

matplotlib 3.2.2

numpy	1.19.5

pandas 1.1.5

# Data
If you run this program on your local environment, please download qm9.pickle, H_ORAC.csv, bde_list.csv, and BDE_t.csv.

# License
Please view a License file.
