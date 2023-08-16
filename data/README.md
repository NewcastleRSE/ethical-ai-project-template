### Data 

Depending on the size of your dataset this folder may be used to contain your raw and processed data, as per the default folders. 
However, with some datasets the data is too large or sensitive to be version controlled and put on github. 

In this case we would recommend updating the .gitignore to ignore this data folder and keep your data either locally or on a HPC/ cloud system as appropriate.
Please then rename and move this readme to the main folder so pertinant information about the data is still available and version controlled.

## Data Overview

Please include a brief overview of the dataset you are using, things to include in this:

- [ ] Storage location: if storing data outside of this repository, where is it, including backup locations.
- [ ] Data Access: How can a collaborator access the data, including permission requirements and security.
- [ ] Provenance:  where did the data come from orginally, and are there any citations needed for this. Include data gathering methods where relevant.
- [ ] Useage Permissions for the data (especially if included in a public repository).
- [ ] Potential Biases: please make note of any [potential biases](https://towardsdatascience.com/types-of-biases-in-data-cafc4f2634fb) in this dataset
- [ ] Label balance: make note of the [degree of imbalance](https://developers.google.com/machine-learning/data-prep/construct/sampling-splitting/imbalanced-data) in the dataset, if any.
      NB: If you do have an imbalanced dataset, there are [ways to account for this and minimise potential issues.](https://towardsdatascience.com/having-an-imbalanced-dataset-here-is-how-you-can-solve-it-1640568947eb)
- [ ] Age of dataset: Include the time period in which the data was gathered. This can be relevant in case there are potential issues with out of date data, or as a prompt for the future to retrain models and regather data.
- [ ] Size of dataset: e.g. number of images, or better yet a breakdown of the number of data points per class.
      NB: if you are dealing with a small amount of data there are [augmentation techniques that may be able to help artificially increase your dataset](https://research.aimultiple.com/data-augmentation-techniques/)

## Data Considerations

These are some prompts for additional things to consider when starting a project:
- [ ] Domain specific regulatory requirements: In certain domains there may be additional regulatory requirements to adhere to (e.g. working with personally identifiable data).
      Do you need to adhere to any additional requirements? If so here is a good place to make note of these and ideally how you are fulfilling them. 
- [ ] Cleanliness: does your data need to be cleaned?
      If so, please document the cleaning process, whether that is a tool like [open refine](https://openrefine.org/) or shell scripts (if so please include in src folder for reproducibility). 
