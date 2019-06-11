# -Cardiotocography-SVMClassification-Matlab
A Multi-Class SVM classifier implemented using MATLAB for the Cardiotocography dataset. 

The code prepares and processes the dataset from a csv file, it performs feature analysis and ranking of features then optimizes the SVM model using a bayesian optimizer. The model is evaluated using K-fold cross-validation, theres is no hold out validation performed. A confusion matrix is also generated to produce the recall,precision and F1 score of the model.

The code is properly structured, well commented and symbolic variables used allowing beginners too have an easy time understanding it.

Please also do cite or share my work if you like it :-)

# Dataset Description
This dataset is used to train prediction models to identify the status of fetal health in a pregnant woman. The data is obtained from 2126 fetal cardiotocograms that were generated from an Electronic Fetal Monitor (EFM).  The data was automatically processed and the respective diagnostic features measured. The dataset thus has a total 2126 samples and a total of 21 features. Each sample is classified into 1 of 10 different classes which describe the fetal current state and 1 of 3 classes which describe the overall health status of a fetus from normal, suspect and pathological. Once a model is trained using this data it can correctly make decisions regarding fetal health status saving on diagnosis time and allowing for prompt action during an emergency. 

# References and Dataset source  
J. Bernardes, J.P. Marques and D. Ayres. (2010). UCI Machine Learning Repository [ https://archive.ics.uci.edu/ml/datasets/cardiotocography ]. Irvine, CA: University of California, School of Information and Computer Science. 
