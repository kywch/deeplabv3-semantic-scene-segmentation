
# About 
The is a pytorch implementation of DeepLabV3 for semantic scene segmentation, trained on Cityscapes dataset. 

# How to run it?

1. If you're using Google colab, upload the `evaluation` folder to your Google Drive.
2. Upload your image files/folders into `Dataset` folder. (You might need to modify the DatasetVal class in `evaluation.ipynb` if you're using your own dataset).
3. Open `evaluation.ipynb` in Google colab and make sure you nevigate into `evaluation` folder before running the code. 
4. The predicted image files are stored in `evaluation/deeplabv3/training_logs/model_eval_val/` and category ratios are stored in `object_ratios.csv` in `evaluation` folder.

