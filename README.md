#  Netflix Movies & TV Shows Analysis

An exploratory data analysis (EDA) project using Netflix’s public dataset to uncover content trends, platform growth, and insights by content type, genres, and countries.

---

##  Project Overview

Netflix has grown to become the world's leading streaming service. This project analyzes the available data on movies and TV shows to explore trends, genre popularity, and global reach. The analysis answers questions like:

- How has Netflix's content grown over time?
- Which countries contribute the most content?
- Are movies or TV shows more dominant?
- What are the most common genres?
- Are there any seasonal trends?

---

##  Data Cleaning

- Loaded dataset from `netflix_titles.csv`
- Converted `date_added` to datetime using flexible parsing
- Created new columns: `year_added`, `month_added`
- Handled missing values (e.g., `country`, `director`, `cast`)
- Extracted the first genre from multi-genre entries

---

## 🔍 Exploratory Data Analysis

###  Key Questions Explored:
- Year-wise content additions
- Type of content (Movies vs. TV Shows)
- Top countries producing content
- Most common genres
- Duration analysis
- Monthly trends in content release

---

##  Key Insights

- **Content growth** peaked between 2018–2020, showing Netflix’s aggressive expansion.
- **Movies dominate**, but TV shows are steadily increasing.
- The **United States** produces the most content, followed by India and the UK.
- Most frequent genres include **Dramas**, **Comedies**, and **Documentaries**.
- Seasonal patterns show **spikes in content additions around November and December**.

---

## 🛠 Tools Used

- Python
- Jupyter Notebook
- Pandas & NumPy
- Plotly & Seaborn
- Matplotlib
- Git & GitHub

---

## 💡 How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/vanessa1543/Netflix-Analysis.git
    cd Netflix-Analysis
    ```

2. Install required libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Launch the notebook:
    ```bash
    jupyter notebook Netflix_EDA.ipynb
    ```

---

##  Visuals

> Netflix Content Growth Over Time  
![Content_growth](Content_growth.png)

>  Movie vs. TV Show Distribution  
![Distribution_count](Distribution_count.png)

>  Titles added overtime  
![Titles_per_year](Titles_per_year.png)

> Top 10 countries
![Top_10_countries](Top_10_countries.png)

---

##  Let’s Connect!

Made with ❤️ by **Vanessa Oye Ayensu**  
🔗 [LinkedIn](www.linkedin.com/in/vanessa-ayensu)  
 

---

##  Acknowledgments

- Dataset: [Kaggle - Netflix Titles](https://www.kaggle.com/datasets/shivamb/netflix-shows)
