# Mosquito_ID
Machine learning-based classifier to identify mosquito species from a recording of flight noise.

# Presentation
This repository offers a machine learning based classifier of mosquito species based on the data published by Dinarte Vasconcelos, Nuno Jardim Nunes and João Gomes in [Scientific Data: An annotated dataset of bioacoustic sensing and features of mosquitoes](https://www.nature.com/articles/s41597-020-00725-6) (https://doi.org/10.1038/s41597-020-00725-6). The main feature of the classifier is to classify an audio sample as belonging to one of three species of mosquito sampled in the D. Vasconcelos et al. study. Current top performance is over 99% with one sample being misclassified. This performance is achieved by various machine learning models including an SVM classifier, a KNN classifier and a multilayer perceptron.
![Confusion Matrix for KNN](https://github.com/FWijanto/Mosquito_ID/blob/main/Readme_Images/Confusion_Matrix_KNN.png)

# Contributing
There are two main fields of improvements: more mosquito recording, especially adding uncatalogued species but also reinforcing the existing database of species and improving the interface to access the models (eg. a UI that allows uploading a sample and which outputs a prediction). If you are able to contribute on these fields or another, please contact me or submit a pull request. Keep in mind the license of the repository which is quite permissive.
