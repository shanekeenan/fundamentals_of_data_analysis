## Assessment repository for Fundamentals of Data Analsis module

***
Module: Fundamentals of Data Analsis with lecturer Dr Ian McLoughlin
Semester 2, Higher Diploma in Science in Data Analytics at ATU, Galway, 2023/24. 

Author: Shane Keenan 

***

## About 

This repository contains two jupyter notebooks for assessment - 

1. tasks.jpynb - contains answers to the five tasks detailed in the 2324_winter_fund_list_of_tasks.pdf file which can be found in the lecture_notes folder. 
- data file , penguin.csv, required for task 2,3 and 5 can be located in the data folder.

2. project.jpynb - contains code for the project which is an analysis of the Iris data set. Desription of which can be found in 2324_winter_fund_assessment_instructions.pdf which can be found the lecture_notes folder. 
- data files - iris.csv associated with this project can be located in the data folder 
additionally pictures of the iris flowers can be found in the img folder. 


## running the code 

Note all data (in both tasks and project) is linked using relative paths to the data folder in the repository. E.g. 
``current_directory = os.getcwd()`` gets the current directory the jupyter notebook is saved and 
``relative_path = "data\\iris.csv"`` defines the relative path from the notebook to the data file. which is then added to the current directory
``file_path = os.path.join(current_directory, relative_path)``

Therefore if the repository is cloned locally there should be no need to change file names to run the notebook.

steps to create:  

1. Install Anaconda 
2. Install visual studio code 
3. create a github account 
4. create public repository "fundamentals_data_analysis" with README.md and .gitignore file
5. Sign into github using VScode 
6. Clone repository to PC 
7. Create necesary notebooks and folders
8. Commit all and push to repo 


## required python packages

for project 

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import random 
from PIL import Image
import os


for tasks 

import numpy as np 
import pandas as pd 
import matplotlib.pyplot as plt 
import seaborn as sns 
import random 
import os
from scipy.stats import norm