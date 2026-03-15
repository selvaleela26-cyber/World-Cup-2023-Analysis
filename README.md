# World-Cup-2023-Analysis
## Project Overview

The ICC Cricket World Cup 2023 generated a large amount of match data involving multiple teams, players, and venues. Analyzing this data can reveal important insights about player performances, match outcomes, and stadium conditions.

This project focuses on analyzing the World Cup 2023 match dataset using Python. The main goal is to transform raw match data into meaningful insights that highlight top performers, venue behavior, and match result patterns.

By performing data cleaning, exploratory data analysis (EDA), and visualization, this project identifies key trends that help understand how players and teams performed during the tournament.

---

## Problem Statement

The primary objective of this project is to analyze match data from the ICC Men's Cricket World Cup 2023 and answer important analytical questions such as:

- Who were the top performers in terms of batting and bowling?
- Which stadiums favored batting first or bowling first?
- Which players won the most Player of the Match awards?
- What patterns can be observed in match outcomes such as wins by runs or wickets?
- How did different player roles (batsmen, bowlers, all-rounders) influence match results?

Understanding these patterns helps provide insights into tournament dynamics and team strategies.

---

## Dataset Information

The dataset used for this analysis is:

**World-Cup-2023-Schedule.csv**

The dataset contains match-level information including:

- Match Number
- Teams Playing
- Stadium / Venue
- Best Scorer
- Best Bowler
- Player of the Match
- Match Result
- Winning Method (Runs or Wickets)

This data allows us to analyze player performances, team success patterns, and venue behavior.

---

## Tools and Technologies Used

The analysis was performed using the following tools and technologies:
- **Python** – Main programming language used for analysis
- **Pandas** – Data manipulation and cleaning
- **Matplotlib** – Data visualization
- **Plotly** – Interactive visualizations
- **Google Colab** – Development environment for running Python notebooks
- **Excel** – Initial inspection and basic cleaning of the dataset
- **MySQL** – Used for querying and organizing structured match data

---

## Data Preparation

Before performing analysis, the dataset was cleaned and prepared to ensure data accuracy.

The following steps were carried out:

### Data Loading
The dataset was loaded into the Python environment using the Pandas library.

### Handling Missing Values
Missing or incomplete entries were identified and handled appropriately to avoid incorrect analysis results.

### Removing Duplicates
Duplicate records were removed to ensure that each match was represented only once in the dataset.

### Data Formatting
Column names were standardized and data types were corrected to maintain consistency across the dataset.

These steps ensured that the dataset was reliable and suitable for further analysis.

---

## Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to uncover patterns and insights from the dataset.

### Top Performer Analysis

The analysis identified the most consistent batting and bowling performers.

Key findings:

- **Daryl Mitchell** appeared as the best scorer in **three matches**
- **Adam Zampa** appeared as the best bowler in **five matches**

This indicates strong individual performances during the tournament.

---

### Player of the Match Analysis

The Player of the Match awards were analyzed to determine the most impactful players.

Key findings:

- **Travis Head** won **3 Player of the Match awards**
- **Mohammad Shami** also won **3 Player of the Match awards**

These players had significant contributions in multiple matches.

---

### Player Role Distribution

The distribution of Player of the Match awards based on player roles was also analyzed.

Results show that:

- **Batsmen received 15 awards**
- **All-rounders also received 15 awards**

This suggests that players contributing both offensively and defensively often have greater match impact.

---

### Stadium Analysis

Venue-based analysis was performed to determine which stadiums favored certain playing conditions.

Key findings:

- **Wankhede Stadium** favored teams batting first
- **Ekana Stadium** favored teams bowling first

Pitch conditions and stadium characteristics influence match strategies and outcomes.

---

### Match Outcome Analysis

The analysis also examined how teams won matches during the tournament.

Key observations:

- **India won five matches by runs and five by wickets**
- **Australia won four matches by runs and five by wickets**

This reflects balanced performance in both defending scores and chasing targets.

---

## Data Visualization

Visualizations were created to better communicate insights discovered during the analysis.

Several charts were used, including:

- Bar charts showing top scorers and best bowlers
- Distribution charts for Player of the Match awards
- Venue-based visualizations to analyze stadium performance
- Match outcome comparisons for different teams

These visualizations help present complex data patterns in an easy-to-understand format.

---

## Key Insights

From the analysis, several important insights were identified:
- Daryl Mitchell and Adam Zampa were among the most consistent performers in the tournament.
- Travis Head and Mohammad Shami received the highest number of Player of the Match awards.
- All-rounders and batsmen dominated Player of the Match awards.
- Stadium conditions influenced match outcomes, with some venues favoring batting while others favored bowling.
- India and Australia showed balanced performance by winning matches through both runs and wickets.

---

## Conclusion
This project demonstrates how Python-based data analysis techniques can be applied to sports data to generate meaningful insights.

By combining data cleaning, exploratory analysis, and visualization, the project successfully transformed raw tournament data into clear insights about player performances, team success patterns, and stadium behavior.

Such data-driven analysis can support better understanding of cricket tournaments and provide valuable insights for analysts, teams, and fans.

---

## Future Improvements
Future analysis could include:
- Ball-by-ball match analysis
- Player performance trends across multiple tournaments
- Predictive models for match outcomes
- Advanced visual dashboards using Power BI or Tableau

These enhancements could provide even deeper insights into cricket performance analytics.
