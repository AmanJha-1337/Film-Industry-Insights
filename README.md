# Movie Industry Analysis

## Project Overview

A hypothetical company plans to enter the movie industry by launching its own production studio. However, it lacks prior experience in film production and distribution.

The objective of this project is to collect, clean, and analyze movie industry data from multiple sources to identify the factors that drive commercial and critical success. Based on the analysis, strategic recommendations are provided regarding movie budgets, genre selection, release timing, talent acquisition, award strategies, and industry benchmarking.

---

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Datetime
- Web Scraping
- Jupyter Notebook

---

## Data Sources

The dataset was collected through web scraping from the following sources:

1. https://www.the-numbers.com/movie/budgets/all/1
2. https://www.imdb.com
3. https://www.boxofficemojo.com
4. https://www.moviefone.com
5. https://en.wikipedia.org/wiki/List_of_Academy_Award-winning_films

---

## Business Questions

This project investigates the following questions:

1. What are the most profitable movies and how much should you spend?
2. Which movie genres are most commonly produced and does quantity translate into higher profits?
3. What is the best time of the year to release a movie?
4. Which actors and directors consistently add value?
5. How much should be spent to produce an Oscar-winning movie?
6. What impact do runtime and movie ratings have on profitability?
7. What profitability targets should a new studio aim for?
8. Which existing studios should be used as benchmarks for success?

---

# Analysis & Key Findings

---

## 1. Budget vs Profit Analysis

The relationship between production budgets and profitability was analyzed to identify an optimal spending range.

### Key Insight

- Movies with budgets around **$82.25 Million** generated the strongest overall returns.
- Target profit margin: **80%**

### Visualizations

#### Budget vs Profit

![Budget vs Profit](visuals/BudgetVProfit.png)

#### Budget vs Profit Margin

![Budget vs Margin](visuals/BudgetVMargin.png)

#### Top 25 Most Profitable Movies

![Top 25 Profitable Movies](visuals/ProfitBudgetTop25.png)

### Recommendation

A production budget near **$82 Million** provides the best balance between investment and profitability.

---

## 2. Genre Performance Analysis

This analysis evaluates genre popularity, net profits, and profit margins.

### Visualizations

#### Number of Movies by Genre

![Count Genre](visuals/CountGenre.png)

#### Net Profit by Genre

![Net Profit Genre](visuals/NetProfitGenre.png)

#### Profit Margin by Genre

![Profit Margin Genre](visuals/ProfitMarginGenre.png)

#### Percent Profit Contribution by Genre

![Percent Profit Genre](visuals/PercentProfitGenre.png)

### Key Insight

Top-performing genres include:

- Animation
- Adventure
- Sci-Fi
- Horror
- Musical

### Recommendation

Focus production investments on Animation, Adventure, and Sci-Fi projects while maintaining selective exposure to Horror and Musical genres.

---

## 3. Release Timing Analysis

Movie release timing was evaluated to identify periods associated with stronger financial performance.

### Visualizations

#### Number of Releases by Month

![Count by Month](visuals/CountbyMonth.png)

#### Profit Margin by Month

![Margin by Month](visuals/MarginByMonth.png)

#### Profit by Month

![Profit by Month](visuals/ProfitbyMonth.png)

#### Profit by Month Across Genres

![Profit by Month by Genre](visuals/ProfitbyMonthbyGenre.png)

### Key Insight

Movies released during **May, June, and July** consistently achieve stronger performance.

### Recommendation

Prioritize summer releases, particularly for Animation and Adventure titles.

---

## 4. Actor & Director Value Analysis

A Value Above Replacement (VAR) metric was developed to identify actors and directors who consistently contribute to profitability.

### Visualizations

#### Actor VAR

![VAR Actor](visuals/VARActor.png)

#### Director VAR

![VAR Director](visuals/VARDirector.png)

### Key Insight

Actors and directors with VAR scores above **1.0** consistently outperform industry averages.

### Recommendation

Prioritize talent with strong historical profitability metrics when building production teams.

---

## 5. Oscar-Winning Movie Analysis

The relationship between movie budgets and Academy Award success was examined.

### Visualizations

#### Oscar-Nominated Movies

![Oscar Nominated](visuals/Oscar_Nominated.png)

#### Movies with Three or More Nominations

![3 Nominations](visuals/3_Nominations.png)

### Key Insight

Movies with budgets above **$35.46 Million** are significantly more likely to win Academy Awards.

### Recommendation

Allocate at least **$35 Million** when pursuing award-oriented productions.

---

## 6. Rating & Runtime Analysis

This analysis explores how movie ratings and runtime affect financial performance.

### Visualizations

#### Profit by Genre and Rating

![Profit by Genre by Rating](visuals/ProfitbyGenrebyRating.png)

#### Profit by Rating

![Profit by Rating](visuals/ProfitbyRating.png)

#### Runtime vs Profit Correlation

![Runtime Correlation](visuals/CorrProfitRuntime.png)

### Key Insight

- PG-13 movies consistently produce the strongest returns.
- Runtime has minimal influence on profitability.

### Recommendation

Align ratings with target audiences and prioritize PG-13 releases when appropriate.

---

## 7. Studio Benchmark Analysis

Leading movie studios were analyzed to establish realistic profitability targets.

### Visualization

#### Net Profit by Studio

![Net Profit Studio](visuals/NetProfitStudio.png)

### Key Insight

Top-performing studios achieve:

- Profit Margin: **66%**
- Net Profit: **$50 Million+ per movie**

### Recommendation

Use these figures as baseline performance targets for long-term studio success.

---

## 8. Competitor Analysis

Industry leaders were compared based on theater reach and revenue generation.

### Visualizations

#### Domestic Gross per Theater

![Domestic Per Theater](visuals/DomesticPerTheater.png)

#### Theaters vs Gross Revenue

![Theaters vs Gross](visuals/TheatersVGross.png)

### Key Insight

Disney demonstrates the strongest overall performance across:

- Revenue generation
- Theater efficiency
- Award success


---

## Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning & Transformation
- Statistical Analysis
- Data Visualization
- Business Intelligence
- Web Scraping
- Feature Engineering
- Strategic Decision-Making
- Python (Pandas, NumPy, Matplotlib, Seaborn)

---

## Connect With Me

<p align="left">
  <a href="mailto:2023ugce055@nitjsr.ac.in">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/aman-kumar-jha-13211027b/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
</p>

## License

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
