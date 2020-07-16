## Preprocessing of Datasets

### Datasets Used:
- Cityscapes
- PascalVOC 2012
- CamVid

### Downloading Datasets
- Cityscapes

Download cityscapes dataset from [here](https://www.cityscapes-dataset.com/) and place it in this directory. You can also use command line to download the dataset by following [this link](https://towardsdatascience.com/download-city-scapes-dataset-with-script-3061f87b20d7). The packages needed for this experiment is 'gtCoarse', 'gtFine' and 'leftImg8bit_trainvaltest'. 

- PascalVOC 2012

Download Pascal dataset from [here](https://pjreddie.com/projects/pascal-voc-dataset-mirror/) and place it in this directory.
- CamVid(CamSeq01)
Download Pascal dataset from [here](http://mi.eng.cam.ac.uk/research/projects/VideoRec/CamSeq01/) and place it in this directory.

### Running the notebooks
For Cityscapes dataset, run cells of `cityscape_preprocessing.ipynb`, for PascalVOC 2012, run `pascal_preprocessing.ipynb` and for CamVid, run `camvid_preprocessing.ipynb`

### Output Directory Hierarchy
    data/
      train_frames/
        train/
      train_masks/
        train/
      val_frames/
        val/
      val_masks/
        val/
      test_frames/ (if_applicable)
        test/
      test_masks/  (if applicable)
        test/
      label_colors.txt
      
`{}_frames/{}/` contains the images in png format for the datasets while `{}_masks/{}/` contain their segmentation masks in png format as well. Image name and mask name must coincide, i.e., both should have same filename. `label_colors.txt` is a file containing the rgb of a mask along with the class name.
        
