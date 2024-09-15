# Netflix Movies EDA - 1990s Decade

This repository contains a project focused on performing **Exploratory Data Analysis (EDA)** on a dataset of Netflix movies from the 1990s decade. The primary goal is to gain insights into movies from this era, particularly focusing on their durations and genre-specific analysis (like action movies). This project is inspired by a DataCamp assignment.

## Project Overview

The project involves:
1. **Analyzing Netflix movies from the 1990s decade.**
2. **Identifying the most frequent movie duration during this period.**
3. **Counting the number of short action movies (movies less than 90 minutes) released in the 1990s.**

## Dataset

The dataset used for this project is `netflix_data.csv`, which contains information about various movies, including:
- Movie title
- Release year
- Genre
- Duration (in minutes)

### Key Objectives

- **Find the most frequent movie duration** in the 1990s decade and store the result as an integer called `duration`.
- **Count the number of short action movies** (less than 90 minutes) released in the 1990s and store the result as an integer called `short_movie_count`.

## Installation

To run this project locally, you need to set up the environment and install the required dependencies. Here’s a step-by-step guide:

### 1. Clone the repository

```bash
git clone https://github.com/DavidBatoDev/netflix-eda-1990s.git
```

### 2. Navigate to the project directory
```bash
cd netflix-eda-1990s
```

### 3. Install the following dependency using pip
The major dependencies include:
- pandas
- numpy
- matplotlib
