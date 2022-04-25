# Data-Science-Template

The goal of this repo is to provide a lightweight, no frills template for my data science projects. It is very much a work in progress and I plan to build up the template as I start using it and learn what else should be included. A few common packages are included in the requirements.txt file without specified versions. This allows the most recent versions to be installed in the project's venv. A basic file structure is also provided based off the cookie cutter template: https://github.com/drivendata/cookiecutter-data-science.

The structure includes a data directory for storing raw data (which is treated as immutable and is never changed), processing data, and storing the final processed data. Models are trained and used in a separate directory with the intent to pull the processed data from the data directory. 

Jupyter Notebooks are used for exploration and development and then "graduated" to .py scripts once complete. 

Once a project is complete, the requirements can be updated with pip freeze to ensure the project can be reproduced later.
