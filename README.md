# Analyzing American baby name trends

This project analyzes American baby name trends using PostgreSQL and Python. The dataset encompasses over a century of baby names, enabling us to uncover fascinating patterns and trends in naming practices across the United States.

## Project Overview

In this project, we:
- Set up a PostgreSQL database to store and query the baby name data.
- Use advanced SQL queries to analyze trends and patterns.
- Leverage Python and Jupyter Notebooks for data visualization and further analysis.

## Dataset

The dataset used in this project contains information on baby names in the United States over a period of more than 100 years. Each record includes the year, the name, the gender of the baby, and the number of babies given that name.

## Project Structure

- `datasets/`: Contains the dataset and SQL scripts for setting up the database.
- `trends_analysis.ipynb`: Jupyter Notebook with the full analysis and visualizations.

## Getting Started

### Prerequisites

- PostgreSQL installed and running.
- Python and Jupyter Notebooks.
- Required Python packages: `sqlalchemy`, `psycopg2`, `ipython-sql`.

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/YOUR_GITHUB_USERNAME/Analyzing-American-Baby-Name-Trends.git
    cd Analyzing-American-Baby-Name-Trends
    ```

2. Set up the PostgreSQL database:
    ```sh
    psql -U postgres -d names -f datasets/createdb.sql
    ```

3. Install the required Python packages:
    ```sh
    pip install sqlalchemy psycopg2 ipython-sql
    ```

4. Open the Jupyter Notebook:
    ```sh
    jupyter notebook trends_analysis.ipynb
    ```

## Usage

Run the cells in the Jupyter Notebook to see the analysis and visualizations of the baby name trends.
