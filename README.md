## Installation
* `Python version should be 3.6`
* Install thrid-party packages (In `Anacaonda` environment)
    * `pip install sklearn`
    * `pip install pandas`

## A quick start to run experiments
* Run `code\main.py` to get files about knee points identified by all six KPI methods. The files are stored by default in `code\results` after run `main.py`.
* Run `code\algorithms\KPITU.py` to observe the results of KPITU on the specified test problem separately. Other `.py` files in `code\algorithms` can be run separately like this to get the corresponding results.

## Examples of the search dynamics of KPITU for identifying knee point(s).
* Problems with only one knee point, such as PMOP1 with A=2 in 2D and 3D:
![image](https://github.com/JerryI00/KPI/blob/master/gif/PMOP1_M2_A2.gif)
![image](https://github.com/JerryI00/KPI/blob/master/gif/PMOP1_M3_A2.gif)
* Problems with more than one knee point, such as PMOP1 with A=4 in 2D and 3D:
![image](https://github.com/JerryI00/KPI/blob/master/gif/PMOP1_M2_A4.gif)
![image](https://github.com/JerryI00/KPI/blob/master/gif/PMOP1_M3_A4.gif)
