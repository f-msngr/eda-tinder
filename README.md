![Tinder](assets/img/Tinder-Symbole.png)

# Speed Dating with Tinder

## Company's description 📇

<a href="https://tinder.com/" target="_blank">Tinder</a> is an online dating and geosocial networking application. In Tinder, users "swipe right" to like or "swipe left" to dislike other users' profiles, which include their photos, a short bio, and a list of their interests.

Tinder was launched by Sean Rad at a hackathon held at the Hatch Labs incubator in West Hollywood in 2012.

As of 2021, Tinder has recorded more than 65 billion matches worldwide.

[⬆ Table of Contents](#table-of-contents)

## Project 🚧

The marketing team needs help on a new project. They are experiencing a decrease in the number of matches, and they are trying to find a way to understand **what makes people interested into each other**. 

They decided to run a speed dating experiment with people who had to give Tinder lots of informations about themselves that could ultimately reflect on ther dating profile on the app.

Tinder then gathered the data from this experiment. Each row in the dataset represents one speed date between two people, and indicates wether each of them secretly agreed to go on a second date with the other person.

[⬆ Table of Contents](#table-of-contents)

## Goals 🎯

Use the dataset to understand what makes people interested into each other to go on a second date together:
* You may use descriptive statistics
* You may use visualisations

## Scope of this project 🖼️

Data was gathered from participants in experimental speed dating events from 2002-2004. During the events, the attendees would have a four minute "first date" with every other participant of the opposite sex. At the end of their four minutes, participants were asked if they would like to see their date again. They were also asked to rate their date on six attributes: Attractiveness, Sincerity, Intelligence, Fun, Ambition, and Shared Interests.

The dataset also includes questionnaire data gathered from participants at different points in the process. These fields include: demographics, dating habits, self-perception across key attributes, beliefs on what others find valuable in a mate, and lifestyle information. See the Speed Dating Data Key document below for details.

[Dataset](data/Speed+Dating+Data.csv)

[Dataset Description](data/Speed+Dating+Data+Key.doc)

# Table of Contents

- [Speed Dating with Tinder](#speed-dating-with-tinder)
  - [Company's description 📇](#companys-description-)
  - [Project 🚧](#project-)
  - [Goals 🎯](#goals-)
  - [Scope of this project 🖼️](#scope-of-this-project-️)
- [Table of Contents](#table-of-contents)
  - [Tech Stack ⚙️](#tech-stack-️)
  - [Key Features ✨](#key-features-)
- [Installation](#installation)
  - [Requirements ☑](#requirements-)
  - [Quick install 🔧](#quick-install-)
- [License 📜](#license-)


## Tech Stack ⚙️

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange)]()
![pandas](https://img.shields.io/badge/pandas-2.x-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-1.26-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.8-11557C?logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-4C9A2A?logo=seaborn&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-5.x-3F4F75?logo=plotly&logoColor=white)

## Key Features ✨

- **Data Cleaning** : Handled missing values and removed irrelevant columns.  
- **Feature Engineering** : Created demographic, attractiveness, and shared interest features.  
- **Exploratory Analysis** : Visualized distributions, correlations, and decision patterns.  
- **Behavior Insights** : Identified key factors influencing positive responses.  
- **Model Prep** : Structured dataset for predictive modeling and further analysis.


[⬆ Back to top](#table-of-contents)

# Installation

## Requirements ☑

- python3
- pip
- Virtual environment (`venv` recommended)

[⬆ Back to top](#table-of-contents)

## Quick install 🔧

```bash
# 1. Clone the repository
git clone https://github.com/fabthenabab/eda-tinder.git
cd eda-tinder

# 2. Create and activate a virtual environment
python3 -m venv .venv-tinder
source .venv-tinder/bin/activate   # Linux/macOS

# 3. Upgrade pip
pip install --upgrade pip

# 4. Install dependencies
pip install --no-cache-dir -r requirements.txt

# 5. Install Jupyter environment (for running notebooks in VSCode for example)
Install Jupyter environment
pip install ipykernel
# Open notebook in VSCode for example
code eda.ipynb

# 6. Optional: Launch Jupyter Lab if you want to run the notebooks in a browser
pip install jupyterlab
# Open notebook eda.ipynb in jupyterlab
jupyter lab
```

[⬆ Back to top](#table-of-contents)

# License 📜

This project is licensed under the GPL3 License — see the [LICENSE](./LICENSE) file for details.

[⬆ Back to top](#table-of-contents)