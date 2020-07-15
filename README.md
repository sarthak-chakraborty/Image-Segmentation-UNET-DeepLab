# Image Segmentation

### Datasets Used
- Cityscapes
- PascalVOC 2012
- CamVid

### Requirements
`pip install -r requirements.txt`

### Dataset Preprocessing
Follow steps in `dataset_preprocess` and accumulate the data in a particular directory structure. To test with other datasets, you will need to follow the same directory structure as mentioned in `dataset_preprocess`.

### Model Used
Model used in this notebook is UNet. Follow these materials to get a better understanding of the Unet architecture:
1. [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597)
2. [Understanding Semantic Segmentation with UNET](https://towardsdatascience.com/understanding-semantic-segmentation-with-unet-6be4f42d4b47#:~:text=The%20UNET%20was%20developed%20by,convolutional%20and%20max%20pooling%20layers.)

### Run
Run the notebook in steps to get the desired results

### References
1. [Multiclass Semantic Segmentation Camvid](https://github.com/advaitsave/Multiclass-Semantic-Segmentation-CamVid)
