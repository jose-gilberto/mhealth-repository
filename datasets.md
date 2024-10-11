
# Raw Datasets

This table includes all the datasets in raw format. Without any transformation or pre-processing applied.

|Name|Records|Subjects|Length|Dimensions|Missing Values|Metadata|Version|
|--|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|[PPG Guilin](https://drive.google.com/file/d/1J8SfMelyFFhgWfpW46gj2iFf6bgAmp7Z/view?usp=sharing)|657|219|2100|3*|No|Yes|v1.0|
|[PPG Dalia](https://drive.google.com/file/d/118aloUJGD69Hz8utf9N1Ukgpu3FLsIHE/view?usp=sharing)|15|15|6448400|5|No|Yes|v1.0|
|BIDMC||53|
|CapnoBase|
|MIMIC PERform AF Dataset|
|WESAD|
|BRNO PPG|
|[PTB-XL-500Hz](https://drive.google.com/file/d/19irJEAeYAuvUEzOv3jI4tbVOoz9OLQd_/view?usp=sharing)|21799|18869|5000|12|No|Yes|v1.0| 

*In this case the number of dimensions represent three independent segments with one dimension for each subject.

## PPG Guilin

Liang Y, Chen Z, Liu G, Elgendi M. A new, short-recorded photoplethysmogram dataset for blood pressure monitoring in China. Sci Data. 2018 Feb 27;5:180020. doi: 10.1038/sdata.2018.20. PMID: 29485624; PMCID: PMC5827692.

## PPG Dalia

signals.tsv include the 5 dimension signals, the PPG, ECG and ACC (XYZ).  

Reiss, A., Indlekofer, I., & Schmidt, P. (2019). PPG-DaLiA [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C53890.

## PTB-XL-500Hz

The PTB-XL ECG dataset is a large dataset of 21799 clinical 12-lead ECGs from 18869 patients of 10 second length with a sampling rate of 500Hz. 
The dataset is already stratified on 10-fold and splited on train, validation and test based on the original paper recommendation (e.g. all records of a particular patient were assigned to the same fold and split).
We utilized the pytorch format (`.pt`) for the data (signals and labels) and `.csv` for metadata.

Wagner, P., Strodthoff, N., Bousseljot, R., Samek, W., & Schaeffter, T. (2022). PTB-XL, a large publicly available electrocardiography dataset (version 1.0.3). PhysioNet. https://doi.org/10.13026/kfzx-aw45.