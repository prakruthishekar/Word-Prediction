# Next Word Prediction
A web app that is capable of predicting next word on it's own.


## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Installation](#installation)
  * [Run](#run)
  * [Bug / Feature Request](#bug---feature-request)
  * [Contribution](#contribution)
  * [Technologies Used](#technologies-used)
  * [Team](#team)


## Demo

![](https://i.imgur.com/NV6eqfX.jpg)




## Overview
A web application that has a pretained model uncased BERT  that will be loaded when they will be selected only once . After that they will serve fast as they are cached. You can select n number of next words that should come after given text.

## Installation
1. Windows user can double click on activation.bat file to install required package
2. Linux User type following command in commnand line
a) First create a virtual environment 
```bash
python -m venv env

```
b) Move to venv directory and activate environment
```bash
source env/bin/activate

```
c) Clone this project 
```bash
git clone https://github.com/prakruthishekar/Word-Prediction.git
```

d) Move into cloned directory
```bash
cd Word-Prediction
```
e) Now install all requirements
```bash
pip install -r requirements.txt
```
## Run
1. After successfull installation windows user can directly open the link that will be appeared
2. After successful installation open type
```bash
streamlit run next_word.py
 ```
and then open link 

## To Do
1. Add More Architecture Options
2. Trigger prediction on each time when space is pressed




## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://i.imgur.com/jAyHARm.png" width=170>](https://www.streamlit.io/)
[<img target="_blank" src="https://i.imgur.com/TDYScZd.png" width=170>](https://pytorch.org/) 




 
