# Final projects (Fall 2022)
### ISTA 421/ INFO 521
------

We have trained a CNN sequential model with keras to classify seven types of skin lesions. This is a multi-class classification model, and these are the seven skin lesions that are either cancerous already like the Melanoma which is the most serious type of skin cancer, or have a really high chance of turning cancerous like the Actinic keratoses, or is a benign skin lesion like the Benign keratosis-like lesions.

Dataset - https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T

Our dataset consists of over 10,000 image data, and each image has got a cereal number which acts as the image ID. The image names are stored in the metadata as the image ID, and has a unique lesion ID, age, sex, localization, but most importantly dx (pigmented lesion name), and lesion type. This is a multiclass dataset, 7 different classes which are-
● Melanoma (mel)
● Benign keratosis-like lesions (bkl)
● Basal cell carcinoma (bcc)
● Actinic keratoses (akiec)
● Vascular lesions (vas)
● Dermatofibroma (df)

Setup Instructions - 
1. Download the .ipynb file in jupyter notebook
2. pip install all necessary libraries and packages
3. run the code one cell at a time
