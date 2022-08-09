# Boston_House_Price_Prediction

#### Done EDA and feature-engineering on Boston House Dataset (sklearn database) and build a machine-learning model to predict house price on the basis of certain feature.


## How to access full code in your local

1. First fork this repositry by clicking on fork option in your Github account.

2. Go to Code -> Copy the github-repo-url

3. Wherever you want to clone this repo-directory in local travel to that location in command prompt.

4. Then in cmd-> type this command: 
```
git clone github-repo-url
```
> After this whole repo will get clone(will get copied) to your local.

5.  After this write this code in cmd(to open the code in vs code):
```
code .
```
> You can also open this to your any favourite ide from ide itself by open file/folder option in file menu and select this folder Boston_House_Price_Prediction.

## Environment setup for code to run in local.

```
conda create -p venv python==3.7 -y
```
```
conda activate venv/
```
```
pip install requirements.txt
```
> Note: If some import gives error then do pip install individually and again re-open ide after closing it.

## Steps to run the code on Heroku server

1. Go to Heroku website create account [https://www.heroku.com/home]
2. Create a new app and give any desired name.
3. Select the app in Personal -> go to Deploy -> Under deployment method select 2nd method 
Github(Connenct to github) -> Under manual deploy -> choose Deploy Branch
4. Finally click to see build log in More option at top right.

>If everything goes right you will get unique project url that can be accessed by anyone and on any platform.
