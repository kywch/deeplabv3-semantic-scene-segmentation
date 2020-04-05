

# About 
This is a pytorch implementation of DeepLabV3 for semantic scene segmentation, trained on Cityscapes dataset. 
The code comes from https://github.com/fregu856/deeplabv3

# How to run this in the UChicago RCC cluster
1. Grab an interactive GPU node using the sinteractive command.
2. Load the necessary modules. NOTE: you need to setup your own local conda env so that it can run ```import torchvision``` and ```import cv2```. For example, see https://github.com/kywch/deep-learning-practice/blob/master/RCC_midway2.md. Or, you can create a conda environment that can run the script using the environment.yml file here: ```conda env create -f environment.yml```
```
module load Anaconda3/2019.03
module load cuda/10.0
source activate rcctorch-1.2
```
3. Put the street images under a directory, which you will specify in the notebook.
4. Run the jupyter notebook line-by-line.
5. Output files will be in the output directory you specify. The summary csv file is named 00_object_ratio.csv.
6. The script also saves the label visualization images for the first 100 images. 
