# aerial-semantic-segmentation
Segmentation/Classification on aerial data using various methods


## Instructions for use 
- Download the aerial data from [here](https://www.kaggle.com/datasets/bulentsiyah/semantic-drone-dataset?resource=download) 
- Clone this repository
- Move the downloaded data inside the `dataset_here` folder of this repository so that the directory structure looks like this:
```
aerial-semantic-segmentation
├── dataset_here
│   ├── dataset 
│   ├── RGB_color_image_masks
│   └── class_dict_seg.csv
├── README.md
├── DCNN.ipynb
├── random_forest.ipynb
├── SVM.ipynb
├── data_preprocessing.ipynb
└── LICENSE
```

- Run the `data_preprocessing.ipynb` notebook to generate the training and testing data. The data will be saved in numpy files.
- Run the `DCNN.ipynb` notebook to train the DCNN model
- Run the `random_forest.ipynb` notebook to train the Random Forest model
- Run the `SVM.ipynb` notebook to train the SVM model

## Results
