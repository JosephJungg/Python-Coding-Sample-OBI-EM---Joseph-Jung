# Project Title: New York Times Article Analysis
This project analyzes quarterly coverage trends and potential media bias in the New York Times across three distinct topics: New Year, Zoom Platform, and GPT Models.

By crossing-referencing article text with sentiment data, the project evaluates both the volume of coverage and the emotional framing (positive vs. negative) associated with each topic over time.

Data & Methodology:
- Primary Dataset (data/nyt_articles.txt): Used to isolate target topics and track their mention frequency on a quarterly basis.

- Secondary Dataset (data/nyt_sentiments.csv): Contains pre-evaluated sentiment scores for each article, allowing us to calculate the proportion of positive vs. negative coverage for each topic and identify potential journalistic bias.

# Python Libraries Used: 
NumPy, Pandas, Matplotlib, Seaborn, RegEx

# How to set up
### 1. Prerequisites
Ensure you have Python (version 3.8 or higher) installed on your system.

### 2. Clone the Repository
Clone this repository to your local machine using this git command:

```
git clone https://github.com/JosephJungg/Python-Coding-Sample-OBI-EM---Joseph-Jung.git
```
### 3. Set Up a Virtual Environment (Recommended)
Creating an isolated virtual environment prevents library version conflicts with other projects on your computer.

On macOS and Linux:

```
python3 -m venv env
```
```
source env/bin/activate
```
On Windows:

```
python -m venv env
```
```
.\env\Scripts\activate
```
### 4. Install Dependencies
Install the required external libraries (pandas, numpy, matplotlib, and seaborn) using this git command:

```
pip install -r requirements.txt
```
### 5. Launch the Notebook

You can run the notebook using either a standard browser-based Jupyter server or directly inside VS Code.

#### Option A: Run in VS Code (Recommended for IDE users)
1. Open the project folder in VS Code:
```
code .
```
Option B: Run in the Browser (Standard Jupyter)
Start the local Jupyter server:

```
jupyter notebook
```
