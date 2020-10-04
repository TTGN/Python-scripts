# TTGN Python-scripts
python script for TreeTalkers Network
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/TTGN/Python-scripts/master)

I suggets to run the script on Anaconda or server. You can run the script on Binder or Colab but make sure you can handle the local data storage.
Anaconda users :
1. Install anaconda
2. Open Environments, root open terminal
2. write pip install ipyfilechooser
3. go back Home and launch jupyter lab ( in case you find some other error with librray please use the step before for loading other libraries)
4. open the script file (i.e.TT_analytics_ver1.9.ipynb)
5. Run the notebook cell one by one

Before running the script create a data directory in your local machine

At the ed of your process you will find for each TT a series of files :

              TTname (i.e. 52010014_xx.csv) 
              xx= raw (raw data)
              xx= transf (data transformed in physical unit)
              xx= elab (data elaborated with final data)
              
              TTcloudname (i.e C0200114_BAT_29.09.2020.csv)
              the file contains the list of TTs with last date of transmission and battery voltage
