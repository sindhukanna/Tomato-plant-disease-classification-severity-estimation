# Hybrid Deep Learning and Handcrafted Features for Tomato Plant Disease Classification and Severity Estimation

## Description

This repository contains the implementation of a hybrid tomato leaf disease classification and severity estimation framework that combines EfficientNetB0 deep features with handcrafted HSV color features. The framework includes image preprocessing, leaf segmentation, feature extraction, feature fusion, classification, and severity estimation.

## Dataset Information

Dataset: PlantVillage Tomato Leaf Disease Dataset
Source: https://www.kaggle.com/datasets/kaustubhb999/tomatoleaf
The dataset contains healthy and diseased tomato leaf images belonging to multiple disease categories.

## Code Information

Main implementation files:
main.ipynb - comprising 
* preprocessing – image preprocessing and augmentation
* segmentation – leaf segmentation
* feature_extraction – EfficientNetB0 and HSV feature extraction
* classification – disease classification
* severity_estimation – disease severity calculation

The code is implemented using Python and Jupyter Notebook.

## Usage Instructions

Step 1: Download the PlantVillage Tomato Leaf Dataset from Kaggle.
Step 2: Place the dataset inside the dataset folder.
Step 3: Run main notebook.

## Requirements

Python 3.10
TensorFlow 2.15
NumPy
OpenCV
Scikit-learn
Matplotlib
Seaborn
Pandas
Install dependencies using:
pip install tensorflow numpy opencv-python scikit-learn matplotlib seaborn pandas

## Methodology

The proposed framework follows the following pipeline:
1. Image acquisition
2. Data preprocessing and augmentation
3. Leaf segmentation
4. Deep feature extraction using EfficientNetB0
5. Handcrafted HSV feature extraction
6. Feature fusion
7. Disease classification
8. Disease severity estimation


## Output

The framework generates:
* Disease class prediction
* Classification accuracy
* Precision
* Recall
* F1-score
* Confusion matrix
* Disease severity percentage

## Citation

If you use this repository, please cite the associated manuscript:
Hybrid Deep Learning and Handcrafted Features for Tomato Plant Disease Classification and Severity Estimation (under review).

Dataset citation:

PlantVillage Tomato Leaf Disease Dataset
https://www.kaggle.com/datasets/kaustubhb999/tomatoleaf

## License

This repository is released under the MIT License.

## Contribution Guidelines

Contributions are welcome.
To contribute:
1. Fork the repository.
2. Create a new branch.
3. Commit changes.
4. Submit a pull request.

Please ensure code is documented and tested before submission.
