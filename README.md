# Telecommunications customer churn

Problem source: [Telco customer churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data)

[Updated data from IBM](https://accelerator.ca.analytics.ibm.com/bi/?perspective=authoring&pathRef=.public_folders%2FIBM%2BAccelerator%2BCatalog%2FContent%2FDAT00148&id=i9710CF25EF75468D95FFFC7D57D45204&objRef=i9710CF25EF75468D95FFFC7D57D45204&action=run&format=HTML&cmPropStr=%7B%22id%22%3A%22i9710CF25EF75468D95FFFC7D57D45204%22%2C%22type%22%3A%22reportView%22%2C%22defaultName%22%3A%22DAT00148%22%2C%22permissions%22%3A%5B%22execute%22%2C%22read%22%2C%22traverse%22%5D%7D)


## Journal entry

Oct 2 2024


## Notebooks

`~/Dropbox/codes/mathematica/data science/customer churn.nb`: estimates lost annual revenue.

### Exploration

`eda`: Latest version

### Model

`model 0.4`: figuring out the preprocessing and writing the pipeline. Using a dumb way of dropping columns, better to do it in the pipeline with `ColumnTransformer` or something like it.

`model`: Latest version.


