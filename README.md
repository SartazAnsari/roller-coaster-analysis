# Roller Coaster Analysis

## Overview
This project conducts an analysis of a roller coaster dataset obtained from Kaggle. The dataset used can be found [here](https://www.kaggle.com/datasets/robikscube/rollercoaster-database). It covers various aspects of data manipulation, cleaning, exploration, and visualization to derive insights about roller coasters.

## Dataset
The dataset contains information about roller coasters, including their names, locations, manufacturers, opening dates, speeds, heights, types, and more.

## Viewing the Notebook
For better readability due to custom client display functionality, use [nbviewer](https://nbviewer.org/). This provides an improved display as GitHub's notebook viewer does not execute the code.

* [RollerCoasterAnalysis.ipynb](https://nbviewer.org/github/SartazAnsari/roller-coaster-analysis/blob/main/RollerCoasterAnalysis.ipynb)

## Prerequisites
* Python 3.x: Download and install from [python.org](https://www.python.org/).

## Setup

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/SartazAnsari/roller-coaster-analysis.git
   cd roller-coaster-analysis
   ```

2. **[ CHOOSE ANYONE ] Environment setup**
    * Using **Python**
        1. If you prefer Python’s built-in virtual environment
            ```bash
            python -m venv roller-coaster-analysis-env
            ```
        2. Activate the environment:
            * Windows:
                ```bash
                roller-coaster-analysis-env\Scripts\activate
                ```
            * Unix or MacOS:
                ```bash
                source roller-coaster-analysis-env/bin/activate

                ```
        3. Install the required packages:
            ```bash
            pip install notebook
            pip install ipykernel
            pip install kaggle
            pip install pandas matplotlib seaborn
            ```
    * Using **Conda**
        1. Install **Miniconda/Anaconda**: Download and install from [conda.io](https://conda.io).
        2. Create a new Conda environment:
            ```bash
            conda create --name roller-coaster-analysis-env python=3.12
            ```
        3. Activate the environment:
            ```bash
            conda activate roller-coaster-analysis
            ```
        4. Install the required packages:
            ```bash
            conda install -c conda-forge notebook
            conda install -c conda-forge ipykernel
            conda install -c conda-forge kaggle
            conda install pandas matplotlib seaborn 
            ```

3. **[ IF NOT SET BEFORE ] Setting up the Kaggle API**
    * Sign in to **Kaggle** and navigate to the **Account** tab of your user profile.
    * Scroll down to the **API** section and click on **Create New API Token**. 
    * This will download a file named ```kaggle.json``` containing your API credentials.
    * Place the ```kaggle.json``` file in the ```~/.kaggle/``` directory. If the directory does not exist, create it.
    * You're all set up! You can now use the Kaggle API to download datasets directly to your project.

## Analysis
1. **Data Cleaning:**
    * Clean and preprocess the dataset, handling missing values and duplicates.
2. **Exploratory Data Analysis (EDA):**
    * Explore various aspects of the roller coaster dataset:
        * Top years of coaster introduction.
        * Distribution of coaster speeds.
        * Fastest roller coasters.
        * Tallest roller coasters.
        * Types of materials used in  coasters.
        * Correlation between coaster attributes.
        * Average coast speed by location.
3. **Data Visualization:**
    * Visualize the findings using Matplotlib and Seaborn to create informative plots and charts.

## Usage
1. Ensure the dataset is available in the project directory.
2. Import the necessary libraries and functions.
3. Run the provided Python script to perform the analysis and generate visualizations.