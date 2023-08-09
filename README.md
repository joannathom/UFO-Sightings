# UFO-Sightings
UFO Data 

![image](https://github.com/joannathom/UFO-Sightings-/assets/122498031/2809e186-510a-46bd-bbd7-e09c08a8a92a)

![image](https://www.silive.com/resizer/-P8L0yufsJgqGIgfWtM-3flUx1U=/1280x0/smart/cloudfront-us-east-1.images.arcpublishing.com/advancelocal/LB434LS5XVE2ZF4KFHTANR7NXI.jpg)

The image from video provided by the Department of Defense labelled Gimbal, from 2015, an unexplained object is 
seen at center as it is tracked as it soars high along the clouds, traveling against the wind.
(Department of Defense via AP)Department of Defense via AP

## UFO Data Sightings Around The World

My mission for this project is to make the public more aware of unidentified flying objects that are appearing more and more around the world. 
I am hoping that my research can give an overall view of stats on UFOs and if there are areas that are more frequently seen than other locations
around the world. The US and Alaska are the main two areas that my datasets have shown the most research.

![image](Visual #4 Country Mostly Sighted.pdf)


* Credit for research data is:
  Two CSV DATASETS retrieved from UFODATA and NUFORC websites;

`UFODATA = pd.read_csv('ufo_sightings.csv')`
`NUFORC = pd.read_csv('nuforc_events.csv')`

## Requirements to Run the Program:

* Open file Final-Project.ipynb and can be forked from repository

## Before you do any of the below please activate your terminal to be in a virtual enviroment:

`python -m venv venvfor Windows`

`Source venv/scripts/activate` for Windows Computers

`python3 -m venv venv` for Macs

`Source venv/bin/activate` for for Mac Computers

## Use this code to set up the requirements file:
* pip may need to be upgraded follow instruction that are given

`pip freeze > requirements.txt`
`pip install -r requirements.txt`

## Use these steps to save changes to the github repository:

## In Shell of Choice Gitbash or Powershell with linux

`git add 'File name'`
`git commit -m 'File name'`
`git push`

Refresh repository to view changes online:

Then to explore and analyze the data you will need to install these libraries listed in requirement.txt these below:

Use Pip to install the following in Gitbash or what ever Shell Terminal is being used: 

import pandas as pd
import numpy as np
import pathlib
import matplotlib 
install these:

* Gitbash or a Shell Terminal
* Pandas as pd
* Python 3.11
* Pip install Jupyter Notebook- this will be needed to run with Visual Studio to establish the kernel once
  installed type in Juypter Notebook and then give it a few seconds to load in a url. Do make sure you click on trusted
  in Jupyter Notebook in main project file.
* Download Visual Studio = Make sure venvpython3 is running the virtual environment.
* Tableau Public- You might need to create a user account to login into Tableau

Features: 
### Requirement 1: Loading two data sources 
`import pandas as pd`
`UFODATA = pd.read_csv('ufo_sightings.csv')`
`NUFORC = pd.read_csv('nuforc_events.csv')`
### Requirement 2: Analyze Data Sets
### Requirement 3: Clean and operate on the data while combining them.
  * I am going to look at the datasets by looking at shape, info, describing, 
  and the head. 
  ### Requirement 4: Creating Visualizations
  * Created Visualizations with sns and maplotlib and use Tableau. Tableau Public which is free with an account setup. CSV data sets will be needed
    for information to pull into different visual charts. 
  ### Requirement 5: Added README.md with information about the project and commands for running the program.

 
 