---
layout: posts
permalink: /change-dates/
repository: https://github.com/saud-learning-services/canvas-batch-change-dates
syzygy: https://ubc.syzygy.ca

title: Canvas Batch Change Dates

summary: A Python script for the function of batch changing the start and end dates for courses listed in a CSV using Jupyter notebook interface
---

1. List of courses to change with corresponding start and end dates are entered in ./src/csv/input/start_end_courses.csv
2. Jupyter Notebook interface will guide user through script, asking for relevant user input when necessary
3. Errors will be shown when necessary by the interface

## To Run

1. Open up Anaconda Prompt
2. `$ conda env create -f environment.yml`
3. `$ conda activate CBCD_env`
4. `$ jupyter notebook`
5. The previous command will have opened up a tab in your browser, select 'Canvas Batch Change Dates.ipynb' and follow the instructions listed.

## Inputs for Module

1. Canvas API Token
2. start_end_courses.csv (edit file as needed)

## Contribution Guidelines:
**These guidelines assume you have a basic understanding of Git. If you do not please look at this resource here.**
1. If you wish to contribute, clone the repository.
2. Switch the branch to **CBCD_dev** or make your own branch if you prefer.
3. Make your changes. Commit them with a proper message.
4. Make a pull request from your branch or dev branch into the master branch. Someone will review these changes. If anything needs to be changed, you will be contacted through GitHub.

**Contributions are always welcomed, but please follow the guidelines**