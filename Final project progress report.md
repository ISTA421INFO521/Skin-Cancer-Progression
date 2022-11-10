# Final project progress report
### ISTA421/INFO521

-------

Project: Skin Cancer Detection
Names:
- Harshvardhan Singh
- Nassim Sbai

-------


## Instructions

You report should be a short summary of your project progress. This report is relevant to to us, your instructors, and probably to the rest of the class.

Please use this report as a chance to organize your thoughts about what you are trying to do with your project, and to get feedback on your ideas, and the approaches that you have tried so far.

## Submission

Please commit this file to your GitHub repo (progress.md) AND to D2L.


-------

### GitHub repo usage
_We have provided a link to the original dataset, a text file explaining all the changes and updates we have made for our project since the original project proposal. Finally, we have also uploaded an .rmd file that contains the code for our SVM model. We are still working on our model and hope to make it up and running soon. We have made 11 commits so far but most of them were mostly just minor updates, nothing big. We will soon be uploading our Naive Bayes model, very shortly_


### Summarize your data
_Our dataset consists of over 10,000 image data, each image named as ISIC(number). The image names are stored in the metadata as the image ID, and has a unique lesion ID, age, sex, localization, but most importantly dx (pigmented lesion name), and lesion type. This is a multiclass dataset, and we will be implementing one v all classification in order to classify the skin lesions_



### Describe your initial analysis strategy
_So our initial aim for this project was to train a regression model that would predict how likely is a skin lesion, which is not cancerous at the moment to develop into something cancerous. However we have changed our project now, and we will be training a multiclass classifiers instead, and validate our models using k-fold cross validatation and compare the accuracies of the models. We are interested in comparing them using confusion matrix and ROC curves_


### What you have tried so far?
_So far we have spent alot of time on literature review. Each of our teammate is working on a different model for the classification (SVM and Naive Bayes), but we are thinking on shifting our focus to just Naive Bayes for now, for which we need to work on feature extraction of our dataset, all the way through till implementing k-fold cross validation before resuming work on any other model, which is a work in progress at this point in time_


### What worked and what did not
_We really wanted to implement this regression model because it would be great to be able to predict whether a non cancerous skin lesion had a high chance of developing into cancer. Cancer is awful already, but in my opinion it's the fear of a skin condition developing into cancer is what really troubles alot of people. But after completing our literature review we realised that our initial goal was a bit too ambitious, so we decided to implement multiclass classification on our dataset, analyse our models and compare their performances_


### What you plan to do next...
_Please define explicit goals for each of the remaining weeks (before the presentation is due)_

- Week 1:Once segmentation and feature extraction is complete, train the models to perform one v all multiclass classification to classify various skin lesions.
- Week 2: Implement k-fold cross validation and compare for the accuracy of the models. Also compare the ROC curves and confusion matrix.
- Week 3: Finish with the documentation and wind up the project.

### Author contributions
_Describe the contributions of each of the members to the current version of the project_


Student 1: Harshvardhan Singh
- [x] Development of question / hypothesis;
- [x] Data research: search for relevant data to contribute to question;
- [x] Literature review;
- [x] Analysis strategy;
- [x] Analysis code;
- [ ] Code review;
- [x] Work planning and organization;
- [x] Improving teamwork and collaboration;
- [ ] Testing code and procedures;
- [x] Writing report.
- [ ] Additional comments:

Student 2: Nassim Sbai
- [x] Development of question / hypothesis;
- [ ] Data research: search for relevant data to contribute to question;
- [x] Literature review;
- [ ] Analysis strategy;
- [x] Analysis code;
- [x] Code review;
- [x] Work planning and organization;
- [x] Improving teamwork and collaboration;
- [x] Testing code and procedures;
- [x] Writing report.
- [ ] Additional comments:
