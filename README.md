# AML_Classifying_distracted_drivers
## Mandatory assignment for Advanced Machine Learning, ITU Spring 2024

The data can be downloaded from [Kaggle](https://www.kaggle.com/c/state-farm-distracted-driver-detection)

### PLan:
- 1. Fine tune a model for binary classification, distracted or not
- 2. Fine tune a model for multiclass classification, according to provided classes.

[5 images and their predictions vs true labels](sample_results.png "Sample results from multiclass model")

- We then want to look at what areas the model is focussing on and create some heatmaps to demonstrate this:

[Example heatmap image](example_heatmap.png "Example of a heatmap from final model layer")

***

### Requirements:
[Requirements.txt](https://github.com/Xannadoo/AML_Classifying_distracted_drivers/blob/main/requirements.txt)
### Folder structure:
```
    model_v1.pt
    model_v2.pt
    statefarm_drivers_01.ipynb
    statefarm_drivers_02.ipynb
    driver_imgs_list.csv
    src
    ├───imgs
    │   ├───test
    │   └───train
    │       ├───c0
    │       ├───c1
    │       ├───c2
    │       ├───c3
    │       ├───c4
    │       ├───c5
    │       ├───c6
    │       ├───c7
    │       ├───c8
    │       └───c9
    ├───train
    │   ├───c0
    │   └───c1
    ├───train_m
    │   ├───c0
    │   ├───c1
    │   ├───c2
    │   ├───c3
    │   ├───c4
    │   ├───c5
    │   ├───c6
    │   ├───c7
    │   ├───c8
    │   └───c9
    ├───val
    │   ├───c0
    │   └───c1
    └───val_m
        ├───c0
        ├───c1
        ├───c2
        ├───c3
        ├───c4
        ├───c5
        ├───c6
        ├───c7
        ├───c8
        └───c9
 ```
***

