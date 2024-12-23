# Video Game Sales Analysis Project

This project involves analyzing a dataset of video game sales with over 16,000 records, including information on games sold across multiple regions from 1980 to 2020. The analysis focuses on understanding sales patterns, regional preferences, and platform success.

## Dataset Overview

- **Source**: vgchartz.com (scraped data)
- **Shape**: 16,698 rows x 11 columns
- **Columns**:
  - **Rank**: Game rank by global sales
  - **Name**: Game title
  - **Platform**: Gaming platform
  - **Year**: Release year of the game
  - **Genre**: Game genre
  - **Publisher**: Game publisher
  - **NA_Sales**: Sales in North America (millions)
  - **EU_Sales**: Sales in Europe (millions)
  - **JP_Sales**: Sales in Japan (millions)
  - **Other_Sales**: Sales in other regions (millions)
  - **Global_Sales**: Total global sales (millions)

## Cleaning & Preprocessing

The following data cleaning steps were performed:
- Dropped rows with null values in "Year" and "Publisher" columns.
- Removed games with release years from 2017 to 2020.
- Handled missing values (approximately 2% of data) by removing those rows.

## Key Findings

- **Popular Genres**: Action, Sports, and Shooter games dominate global sales.
- **Regional Preferences**: North America favors Xbox, while Europe and Japan prefer PlayStation. Handheld devices are more popular in Japan.
- **Platform Success**: PS2 stands out as a key platform due to its extensive game library and long market presence.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn

## Usage

Clone this repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/videogame-sales-analysis.git
cd videogame-sales-analysis
pip install -r requirements.txt
