# WMScore
A Jupyter notebook that turns the game scores of #WM2018 into a musical score with music21

## Latest Score

29.6.2018:

![wmscore_matchday_3](https://user-images.githubusercontent.com/21059419/42101483-7a82aeda-7bc3-11e8-8cea-bca194cac441.png)

## Prerequisites
- Jupyter: http://jupyter.org/
- music21: http://web.mit.edu/music21/

also:
- requests: http://docs.python-requests.org/en/latest/ (to fetch the data from the API)

## Data
- uses the free football-data API: http://api.football-data.org/

## Usage

### Run notebook locally

Make sure you have installed the following:
1. Python (Version 3.6): https://www.python.org/downloads/
    follow the instructions of the installer

2. Jupyter Notebook (http://jupyter.org/install)
    
    After installation of Python, open terminal and type:
    ```
    python3 --version
    python3 -m pip install --upgrade pip
    python3 -m pip install jupyter
    ```
    If needed, change „python3“ to „python“.

3. music21 (http://web.mit.edu/music21)
    
    Also in terminal type:
    ```
    pip --version
    pip install music21
    ```
    If needed, change „pip“ to „pip3“.


After installation, fork this repo and clone your fork or download a copy of the notebook file to your local machine. 

To start the notebook server, go to the directory of your local clone/copy in terminal and type:
    
```
jupyter notebook
```

The server should now be running and the jupyter dashboard should open automatically in your browser.

To learn more about Jupyter notebooks, see this detailed tutorial: https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook#WhatIs

