# Image Segmentation

### Datasets Used
- Cityscapes
- PascalVOC 2012
- CamVid

### Requirements
`pip install -r requirements.txt`

### Dataset Preprocessing
Follow steps in `dataset_preprocess` and accumulate the data in a particular directory structure. To test with other datasets, you will need to follow the same directory structure as mentioned in `dataset_preprocess`.

### Models Used
1. Unet (tested with all datasets). Follow these materials to get a better understanding of the Unet architecture:
    * [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597)
    * [Understanding Semantic Segmentation with UNET](https://towardsdatascience.com/understanding-semantic-segmentation-with-unet-6be4f42d4b47#:~:text=The%20UNET%20was%20developed%20by,convolutional%20and%20max%20pooling%20layers.)

2. DeepLabv3 model (tested only for PascalVOC 2012 dataset). To know about DeepLabv3 architecture, follow these materials:
    * [Rethinking Atrous Convolution for Semantic Image Segmentation](https://arxiv.org/abs/1706.05587)
    * [DeepLabv3: Semantic Image Segmentation](https://towardsdatascience.com/deeplabv3-c5c749322ffa)

### Run
Run the notebook `segmentation.ipynb` in steps to get the desired results. To run with DeepLab, run the notebook `DeepLab/segmentation.ipynb`.

### References
1. [Multiclass Semantic Segmentation Camvid](https://github.com/advaitsave/Multiclass-Semantic-Segmentation-CamVid)
2. [Keras DeepLab V3.1+](https://github.com/Golbstein/Keras-segmentation-deeplab-v3.1)
