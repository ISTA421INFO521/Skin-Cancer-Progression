# Skin Cancer Progression with Sequential Model in CNN

This is a pilot project for the detection and classification of skin cancer progression using different ML/AI models including Convolutional Neural Network (CNN). For this pilot project, sequential model used can classify different types of skin cancer, including:

- Melanoma (mel)
- Benign keratosis-like lesions (bkl) 
- Basal cell carcinoma (bcc) 
- Actinic keratoses (akiec) 
- Vascular lesions (vas) 
- Dermatofibroma (df)

(Work is still under way and we are re-labeling the image data on a scale of 1 to 10, with 1 indicating that the benign skin lesion is least likely to develop into cancer, whereas with 10 indicating that the benign skin lesion is most likely to debvelop into cancer)

## Getting Started

The project uses Python language and its libraries. The following libraries are used:

- matplotlib
- numpy
- pandas
- os
- glob
- PIL
- seaborn
- keras
- sklearn
- scipy

You can install the necessary libraries with:

```
pip install matplotlib numpy pandas seaborn keras sklearn scipy Pillow
```

## Usage

The model is trained on a dataset, 'HAM10000_metadata', which is stored locally. Please adjust the dataset path according to your local setup. 

The dataset includes various data about the lesion images, like lesion id, image id, diagnosis (dx), dx type, age, sex, and localization. It also includes the path of the actual images. The project involves preprocessing the data, including loading the images, resizing, and categorizing the classes.

Next, the dataset is split into a training set and a test set. The model is then defined using keras with a sequential model.

After training the model, it can be used to predict the type of skin lesion on new skin lesion images.

## Dataset

The dataset used for this project is the [HAM10000](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T) ("Human Against Machine with 10000 training images") dataset. It is a large collection of multi-source dermatoscopic images of pigmented lesions. Feel free to download it from the link and use it for your local setup.

## Model

The sequential model includes several layers, including Convolutional 2D, MaxPooling 2D, Dropout, Flatten, and Dense. The model uses 'relu' activation function for the Conv2D layers and 'softmax' for the final Dense layer. The model is compiled using 'categorical_crossentropy' loss function, 'adam' optimizer, and 'accuracy' as the metric.

## License

This project is licensed under the MIT License.
