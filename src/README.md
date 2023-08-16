# Code and Models

This folder is intended to store the source code of the project. It should include all of the code needed to reproduce model results when paired with the relevant data.
This readme documents the provenance and information pertinent to the code stored in this folder, as well as instructions for how a new user or collaborator can set up and run this code. 

*NB: We have included a template [requirements.txt](https://learnpython.com/blog/python-requirements-file/) file as a suggestion for a python based project, and example instructions for a pip install of these requirements.
If these are not relevant to your project please delete them from your repository, and this line of text.*

## Code Considerations

A checklist of things to consider when beginning to develop models and code. 
Ticked boxes indicate these things have been considered and where relevant documented.

- [ ] Commercialisation potential: does this repository need to be private and access controlled? 
- [ ] Storage of logs and model results: What location and method of storage is being used for the documentation of ongoing model development?
    NB: ensure logs include data set details used as well as time stamp, accuracy and other relevant metadata. 
- [ ] Collaboration guidelines: Is this a collaborative project, if so are there guidelines in place for contributing, e.g. [pull request reviews](https://www.atlassian.com/blog/git/written-unwritten-guide-pull-requests) and [feature branches](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow)? If so where?
- [ ] Model provenance: are the models used pretrained, if so on what, or based on published work - include relevant links and citations in this readme. 
- [ ] End user consideration (who are you building this for?)
- [ ] Linting: are you using [code linting](https://towardsdatascience.com/come-on-lint-a-little-cleaning-up-your-code-with-linters-5d16b1bf19bd), or do you have any other guidelines around the development that need documenting here for collaborators to be aware of?

## Code or files included in this folder or subfolders

- [ ] Requirements or environment file for reproducability and automated installation
- [ ] Code for automated data cleaning and processing
- [ ] Code for model testing and evaluation
- [ ] Model training scripts
- [ ] Model files, pre and post training

## Requirements
What are the requirements and how to install?

*Example requirements and installation instructions below for a python project* 
#### List of requirements:

- Python version 3.9
- tensorflow==2.3.1

#### How to install:

1. Create a virtual environment with [conda](https://edcarp.github.io/introduction-to-conda-for-data-scientists/02-working-with-environments/index.html), [venv](https://docs.python.org/3/library/venv.html) or your [favourite environment, container provider](https://harvard-iacs.github.io/2020-AC295/lectures/lecture2/presentation/lecture2.pdf).
2. Activate your new environment/ container.
3. Ensure you are in this code directory
4. Run `pip install -r requirements.txt`




## Running this code

Instructions for how to set up and run this code!
These should be detailed enough that a new collaborator or user can read the instructions and succeed at running your models without the need to reach out for additional help.

