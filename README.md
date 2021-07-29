# VSB-Power-Line-Fault-Detection

Medium voltage overhead power lines run for hundreds of miles to supply power to cities. These great distances make it expensive to manually inspect the lines for damage that doesn't immediately lead to a power outage, such as a tree branch hitting the line or a flaw in the insulator. These modes of damage lead to a phenomenon known as partial discharge — an electrical discharge which does not bridge the electrodes between an insulation system completely. Partial discharges slowly damage the power line, so left unrepaired they will eventually lead to a power outage or start a fire.

The objectif of this project is to detect partial discharge patterns in signals acquired from these power lines with a new meter designed at the ENET Centre at VŠB. Effective classifiers using this data will make it possible to continuously monitor power lines for faults.



## Contents

This repository is organized into two main folders refering to each mentioned part of the project.

The first bruch is about all the methods tested and the second bruch is about the best model selected. 
In this project i only used the train dataset and decomposed into 33% for testing and 67% for training; 

The dataset available to download at: https://www.kaggle.com/c/vsb-power-line-fault-detection

## How to use:

in  partial discharge not  partial discharge classification:

Data preprocessing: 
- Start by downloading  train files (.parquest)  from  https://www.kaggle.com/c/vsb-power-line-fault-detection.
- run https://github.com/khelloufleila/VSB-Power-Line-Fault-Detection/blob/master/main_project.ipynb which will process the feature extraction and  it also splits the data in 2 sets (train, test ) and use the 5 fold cross validation.

## License


[1] https://www.kaggle.com/c/vsb-power-line-fault-detection.

[2] https://suhaskvaithal.medium.com/vsb-power-line-fault-detection-47f9e94d11d2
