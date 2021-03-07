# Detection-of-Invasive-Ductal-Carcinoma-IDC-

This repository contains the code for detecting Invasive Ductal Carcinoma (IDC), a type of breast cancer, from whole mount slide images of Breast Cancer (BCa). The original dataset consisted of 162 whole mount slide images of Breast Cancer (BCa) specimens scanned at 40x. From that, 277,524 patches of size 50 x 50 were extracted (198,738 IDC negative and 78,786 IDC positive). Each patch’s file name is of the format: uxXyYclassC.png — > example 10253idx5x1351y1101class0.png . Where u is the patient ID (10253idx5), X is the x-coordinate of where this patch was cropped from, Y is the y-coordinate of where this patch was cropped from, and C indicates the class where 0 is non-IDC and 1 is IDC. These patches are used to train and test the model.

The dataset can be found here: https://www.kaggle.com/paultimothymooney/breast-histopathology-images/

Citation: https://www.ncbi.nlm.nih.gov/pubmed/27563488 and http://spie.org/Publications/Proceedings/Paper/10.1117/12.2043872

Invasive ductal carcinoma (IDC) is the most common form of breast cancer. Thus, it is important to automate the process of identifying and categorizing breast cancer subtypes in order to save time and possible reduce error.
