# Image-Segmentation-Assignmnet

## TASK 1: Dataset preparation using python

[Download](http://cocodataset.org/#download "Download COCO") the following files on to your PC. 

**2017 train images, 2017 val images, 2017 Train/Val annotations**

Some simple re-arrangement and re-naming of folders is required as below. The file structure for the following code is:
```
Project Folder
│
└───COCO
|   |
|   └───annotations
|   |   └───   instances_train2017.json
|   |   └───   instances_val2017.json   
|   └───images
|   │   └───train2017
|   │   │    │   000000000009.jpg
|   │   │    │   000000000025.jpg
|   │   │    │   ...
|   │   └───val2017   
|   │        │   000000000139.jpg
|   │        │   000000000285.jpg
|   │        │   ...
|   └───Assignmnet_VJT_PavanKumar.ipynb
```

This task involves datat processing and training image segmentation model using PyTorch
### Goals
1) Get subsets of the COCO dataset as per requirement  
2) Generate masks from the given COCO annotations  
3) Add image augmentations  
4) Create a data generator object to ease training models
5) Train an image segmentation model
