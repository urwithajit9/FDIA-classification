# FDIA-classification
This repository will have pre-processed dataset and related scripts for building a Machine learning-based model for classification of False Data Injection Attack. 

# Power System Dataset
The dataset is based on a publically available dataset at the below link.

[Power System Datasets](https://www.sites.google.com/a/uah.edu/tommy-morris-uah/ics-data-sets)

[Detail about the dataset](http://www.ece.uah.edu/~thm0009/icsdatasets/PowerSystem_Dataset_README.pdf)


# Dataset creation steps

1. Convert .arff file to .csv (Scripts are available)
2. Iterate through each CSV file  and select set of events for FDI and NoFDI (detail is provided in paper)
3. Merge all events of each class
4. The resulting dataset will have all event with re-assigned class label 1 or 0 (FDI(1) and NoFDI (0)

# Scripts
 Note: Will be added after the publication of the manuscript.

