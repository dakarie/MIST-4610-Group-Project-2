# MIST 4610 Group 7 Project Two Submission

# Team Number and Members
- **Team Number:** Group 7
- **Members:**
  - Wilson Nguyen [@dakarie](https://github.com/dakarie/MIST-4610-Group-Project-2/tree/main)
  - Akshaya Ezhil [@githubhandle2](https://github.com/githubhandle2)
  - Justen Newsom [@githubhandle3](https://github.com/githubhandle3)
  - Shahil Patel [@githubhandle4](https://github.com/githubhandle4)
  - Josh Gershon [@githubhandle4](https://github.com/githubhandle4)


# Dataset Description

- **Dataset Source:** [kaggle.com](https://www.kaggle.com/datasets/sumitrodatta/nba-aba-baa-stats?resource=download&select=Player+Play+By+Play.csv)
- **Dataset Title:** _We used the `Team Stats Per Game` file from the full dataset available on Kaggle._
- **Dimensions:** _1876 rows × 28 columns_

**Key Columns and Data Types:**
- `season` – Integer (Year of the season)
- `lg` – String (League name, e.g., NBA)
- `team` – String (Full team name)
- `abbreviation` – String (Team abbreviation)
- `playoffs` – Boolean (True if team made playoffs)
- `g` – Float (Games played)
- `mp_per_game` – Float (Minutes per game)
- `fg_per_game` – Float (Field goals per game)
- `x3pa_per_game` – Float (3-point attempts per game)
- `x3p_per_game` – Float (3-point makes per game)
- `x3p_percent` – Float (3-point shooting percentage)
- `pts_per_game` – Float (Points per game)
*(Add more as needed)*




# Research Questions

1. **Question 1:** _blank_  
   - _Explain significance and how it connects to the dataset._
2. **Question 2:** _Did Stephen Curry's arrival to the league effect the amount of scoring and 3-pointers attempted in the NBA?​_  
   - _This question matters because Stephen Curry is widely credited with revolutionizing the NBA’s offensive style through his unprecedented 3-point shooting volume and accuracy. His influence is believed to have reshaped team strategies, player development, and even how fans engage with the game. By analyzing league-wide trends in scoring and 3-point attempts before and after his arrival (2009), we can objectively measure the impact of this shift. This question connects directly to our dataset, which includes per-game statistics such as x3pa_per_game (3-point attempts) and pts_per_game (points per game) for every NBA team across multiple seasons. By comparing team averages between the pre-Curry era (1992–2008) and the post-Curry era (2009–2025), we can assess how much the league has changed and how much of that change aligns with Curry’s influence._






# Analysis and Results

We used Tableau for visual analysis. The visualizations included:
- Bar charts
- Line graphs

## Question 1: [Insert your full research question here]

**Visualization:**  
_Description of the planned graph or chart goes here (e.g., "Scatter plot showing average team age vs. playoff rounds reached")_

**Key Insights:**  
- _Insight 1 goes here_  
- _Insight 2 goes here_


## Question 2: Did Stephen Curry’s Arrival to the League Affect the Amount of Scoring and 3-Pointers Attempted in the NBA?

**Visualization:**  
Two bar charts comparing average team 3PT attempts and points per game across two time periods:
- 1992–2008 (pre-Curry era)
- 2009–2025 (post-Curry era)

**Key Insights:**
- From 1992 to 2008, most teams averaged under 20 3PT attempts per game. Post-2009, nearly every team consistently averaged 25–35 attempts.
- Average scoring also increased, but the bigger shift was *how* teams scored — with a much greater reliance on 3-point shots across all franchises.







# Data Manipulations

- Cleaned null values (EXAMPLS)
- Filtered rows/columns
- Created calculated fields in Tableau
- Aggregated data by category/time/region as needed


# Deliverables

- ✅ `README.md`
- ✅ Tableau Packaged Workbook (`project2.twbx`)
- ✅ Dataset (`your_data.csv` or external link)

