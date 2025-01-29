This directory contains all the datasets for the notebooks. 

### knee-provider-subset.csv

A subset of the NHS PROMs dataset about knee replacements from JADS (see [Github](https://github.com/dkapitan/nhs-proms/tree/master))
The dataset is used in notebook 1b. 

### knee-provider.parquet

The complete knee replacement dataset of the NHS PROMs dataset. 
The dataset is used in notebooks 2b, 4a and 4b, and 5. 

### sonar.csv

A toy machine learning dataset for classification of sonar signals. Originally released by [Terry Sejnowski](https://www.sciencedirect.com/science/article/abs/pii/0893608088900238) and 
hosted on https://datahub.io/machine-learning, but no longer accessible. 

### Patch Camelyon dataset

The [PatchCamelyon dataset](https://patchcamelyon.grand-challenge.org/) is used in the first Deep Learning notebook.
A subset of the original dataset is used for the course, which consists of the following files:
- `camelyonpatch_split_<train/valid/test>.h5.gz`: Training/validation/test dataset (features + labels). For the training set, 5% of the original dataset is randomly sampled. For the other datasets, a fixed subset of 1000 records is taken.
- `camelyon-tiles.zip`: A larger tile of an original image, used to demonstrate the Camelyon heatmap code.