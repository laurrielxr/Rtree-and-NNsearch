Rtree-and-NNsearch
===========================
This is the  project of rtree construction and NN serach by Luo Xinrui. 
enviroment:
python 3.7
sklearn


packages:
import pandas as pd
import numpy as np
from matplotlib.patches import Rectangle
from matplotlib import pyplot as plt
import matplotlib.pyplot as plt
import matplotlib.patches as patches
import matplotlib.patches as patches
import math
import sys



Dataset:
--------
Data set download:
AllPOI Locatoion Only.csv
##### Run the program
How to run the program
Download the AllPOI Locatoion Only.csv.csv and run the code in the jupyter notebook

Experimental results
------------------------
For example
Input query point (116.83,	40.643)
Output result 
n	d	nearest neighbour	nearestdistance	visitednodes	calculatedpoint	prunedmbr
10	2	(116.808679, 40.647165)	0.021724002071442067	1229	523	934
10	6	(116.808679, 40.647165)	0.021724002071442067	569	640	1698
100	2	(116.808679, 40.647165)	0.021724002071442067	398	473	249
100	6	(116.808679, 40.647165)	0.021724002071442067	333	6277	757


