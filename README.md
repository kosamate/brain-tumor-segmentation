# Tumor segmentation
This project is a part of my master thesis. The project contains an implementation for brain tumor segmentation. The project contains downloading dataset, defining dataloaders, training and evaluation of the results.
The jupiter notebook file contains more documentation about each section.

# Dataset
The following dataset used for the training: https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation

# Results
The patients have been separated during the training and testing.

Final average dice loss for test patients: 0.00581

#### Videos of test patients
| patient id       | link                         |
| ---------------- | ---------------------------- |
| patient 19960909 | https://youtu.be/bddG6SLTXls |
| patient 19970222 | https://youtu.be/ImbyExeK-qo |
| patient 20000902 | https://youtu.be/MH0ErDBvRGA |
| patient 20010208 | https://youtu.be/WQDhCisLpMI |
| patient 19990606 | https://youtu.be/qIz4HsqZvGw |


#### Hyperparameters
| learning rate | batch size | loss function |
| ------------- | ---------- | ------------- |
| 10e-5         | 16         | Dice Loss     |
