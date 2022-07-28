# style-transfer-for-fundus-images

1. Download the dataset from Kaggle [here](https://www.kaggle.com/c/diabetic-retinopathy-detection/data).
2. Run the following commands to prepare the dataset:
`cat train.zip.* > train.zip`, 
`cat test.zip.* > test.zip`
3. Unzip the data.
4. Place `trainLabels.csv` into the `train` folder.
5. Place the `train` folder in a folder called `input`.
6. Run [`dr_detect.ipynb`](https://github.com/rvignav/style-transfer-for-fundus-images/blob/main/dr_detect.ipynb) in the same directory as `input`.
