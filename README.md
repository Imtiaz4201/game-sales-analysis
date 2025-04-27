# Video Game Sales Exploratory Data Analysis

This project performs an exploratory data analysis (EDA) on video game sales data to uncover trends and patterns related to game sales, platforms, genres, publishers, and regional preferences. The video game industry is a significant part of the entertainment sector, with global revenues estimated to exceed $180 billion in recent years, making this analysis relevant for understanding market dynamics.

## Dataset

The dataset used in this analysis is the ["Video Game Sales" dataset from Kaggle](https://www.kaggle.com/datasets/gregorut/videogamesales), which contains sales data for over 16,500 video games with sales greater than 100,000 copies, scraped from vgchartz.com. It includes 11 columns: Rank, Name, Platform, Year, Genre, Publisher, NA_Sales, EU_Sales, JP_Sales, Other_Sales, and Global_Sales, covering game titles, platforms, release years, genres, publishers, and sales figures for North America, Europe, Japan, other regions, and globally. The dataset is included in the `vgsales.csv` file.

## Installation

To set up and run the analysis, follow these steps:

1. Clone this repository to your local machine.
2. Ensure you have Python 3.x installed.
3. Install the required libraries:
   ```
   pip install pandas matplotlib seaborn jupyter
   ```
4. Start Jupyter Notebook:
   ```
   jupyter notebook
   ```
5. Open `game_sales_eda.ipynb` and run all cells to reproduce the analysis.

## Key Findings

The EDA reveals several insights into the video game sales market from 1980 to 2020:

- **Platform Distribution**: The PlayStation 2 (PS2) and Nintendo DS are the most distributed platforms, with PS2 being the most popular globally.
- **Genre Popularity**: Action is the most popular genre worldwide, followed by Sports. In Japan, Role-Playing games dominate.
- **Regional Markets**: North America is the largest market for video game sales, followed by Europe and Japan, with distinct regional preferences (e.g., Xbox 360 in North America, PS3 in Europe, DS in Japan).
- **Sales Trends**: Sales peaked in the late 1980s and early 1990s, stabilizing in later years, reflecting industry growth and market saturation.
- **Top Publishers**: Nintendo leads with approximately 1,760 million in global sales, followed by Electronic Arts, Activision, Sony Computer Entertainment, and Ubisoft.
- **Top Games**: Wii Sports is the best-selling game globally, with over 80 million copies sold, followed by titles like Grand Theft Auto V and Super Mario Bros.
- **Correlation Insights**: North America and Europe sales arehighly correlated, while Japan’s sales show distinct market dynamics.

For a comprehensive analysis, including visualizations like bar charts, histograms, boxplots, line plots, and heatmaps, refer to the Jupyter notebook `game_sales_eda.ipynb` and the PDF report `game_sales_EDA.pdf`.

## Project Structure

The repository is organized as follows:

| File/Folder            | Description                                      |
|------------------------|--------------------------------------------------|
| `data/vgsales.csv`     | The dataset used for analysis.                   |
| `game_sales_eda.ipynb` | Jupyter notebook with EDA code and visualizations. |
| `README.md`            | This file, providing project overview and instructions. |

