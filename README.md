# User Journey Analysis in Python

This project focuses on analyzing user behavior data from 365's online subscription-based learning platform. By examining the sequence of pages visited by users, we aim to identify key pages and sequences that influence users to subscribe to the platform. The insights gained can guide businesses in optimizing their marketing strategies and user experience.

## Project Overview

The project explores real-world user journey data, which includes the pages users visited before subscribing. The goal is to:

- Preprocess and analyze the user journey data.
- Extract insights about user behavior.
- Visualize the most common paths taken by users.

## Key Tasks

1. **Data Preprocessing**:
   - Clean and format the data.
   - Split the user journey into individual page visits.

2. **Data Analysis**:
   - Analyze the most common pages and sequences visited by users.
   - Identify the key steps that lead to subscription.

3. **Visualization**:
   - Create visualizations to present the analysis, such as bar charts for page counts.

## Requirements

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

You can install the required libraries using:

```bash
pip install pandas numpy matplotlib seaborn
```

## Data Description

The dataset consists of the following columns:
- `user_id`: Unique identifier for each user.
- `session_id`: Unique identifier for each user session.
- `subscription_type`: The type of subscription the user purchased (Monthly, Quarterly, or Annual).
- `user_journey`: A string of pages visited during a session, separated by dashes (e.g., `Homepage-Log in-Log in-Log in`).

## Steps Involved

1. **Load the dataset**: Read the provided `user_journey_raw.csv` file.
2. **Preprocess the data**: Clean the data and split the `user_journey` column into individual pages.
3. **Analysis**: Count the occurrences of each page and sequence.
4. **Visualization**: Plot the most visited pages and analyze user behaviors.

## Insights

The analysis helps businesses understand:
- Which pages are most likely to lead to conversions.
- How users navigate through the platform.
- Which pages may need optimization to improve the user experience.

## Usage

Clone the repository and run the Jupyter Notebook to start analyzing the data. The analysis is split into cells, and each step is well-commented for clarity.

```bash
git clone https://github.com/yourusername/user-journey-analysis.git
cd user-journey-analysis
```


---
