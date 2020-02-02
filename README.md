

# About 
This is a pytorch implementation of DeepLabV3 for semantic scene segmentation, trained on Cityscapes dataset. 


# How to run in the UChicago RCC cluster
1. Grab an interactive GPU node using the sinteractive command.
2. (As of 02/02/2020) Load the modules. NOTE: you need to setup your own local conda env so that it can run ```import torchvision``` and ```import cv2```. 
```
module load Anaconda3/2019.03
module load cuda/10.0
source activate pytorch-gpu-1.2-cuda-10.0 # WARNING: this conda env is not enough
```
3. Put the street images under the input directory.
4. Run the jupyter notebook line-by-line.
5. Output files will be in the output directory you specify. The summary csv file is named 00_object_ratio.csv.
6. The script also saves the label visualization images for the first 10 images. 

