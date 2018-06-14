## Overview
Taarifa [link](http://dashboard.taarifa.org/#/dashboard) is a waterpoints dashboard that aggregates data from the Tanzania Ministry of Water. This project is a recurring competition from DrivenData [link](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/) and the goal is to predict the operating condition of a waterpoint for each record in the dataset. The primary programming languages we use are **Python** and **R**.

## Team Members & Results
Zili Li [GitHub](https://github.com/lzl1103)\
Junxiong Liu[GitHub](https://github.com/junxiongliu)\
Yiwei Sun [GitHub](https://github.com/yiweisun)\
Our team (Boomshakalaka) is ranked at 427/5278 (**top 8%**) and our best model (Random Forest) achieves 81.80% accuracy where the leaderboard accuracy is 82.85% as of 06/13/2018.

## File structure
* `data` folder contains the raw data, cleaned data, as well as our submission files. We do not upload data directly to the repository and add a layer of .gitkeep to keep the folders.
* `scripts/preprocessing` folder contains the scripts to clean and preprocess the data. Scripts for this step is written in Python.
* `scripts/modeling` contains the models we experimented. Scripts for this step is written in Python and R.