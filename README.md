🎮 PUBG Player Performance Analytics Dashboard

An interactive Power BI analytics project built to analyze PUBG player performance, match behavior, combat effectiveness, movement, survival, and unusual performance patterns.

The project follows an end-to-end analytics workflow:

Data Preparation → KPI Development → Segmentation → Comparative Analysis → Relationship Analysis → Anomaly Analysis → Interactive Data Storytelling

🔴 Live Interactive Dashboard

👉 🚀 Open Interactive Power BI Dashboard

The dashboard is hosted on Power BI Service and can be explored interactively.

Note: The .pbix file is not included in this repository because of its large file size. The repository contains the project documentation and dashboard screenshots, while the live Power BI report provides the interactive experience.

🎯 Project Objective

The objective of this project was to analyze PUBG gameplay data and understand the factors associated with player performance and match outcomes.

Instead of evaluating performance using only one metric such as kills or wins, the analysis combines multiple dimensions:

⚔️ Combat performance

💥 Damage, kills and assists

🎯 Headshot performance

🏆 Match placement

⏱️ Survival and match duration

🚶 Movement behavior

🚗 Vehicle usage

❤️ Healing and boost usage

🎮 Performance across different game modes

🚨 Unusual or anomalous performances

The goal was to move beyond simply reporting numbers and investigate patterns, relationships, differences, and exceptions within the data.

📊 Dataset

The project uses the PUBG Finish Placement Prediction dataset from Kaggle, based on the train_V2 gameplay data.

Key fields used

matchId

groupId

matchType

kills

damageDealt

walkDistance

rideDistance

swimDistance

weaponsAcquired

heals

boosts

headshotKills

killPlace

longestKill

winPlacePerc

matchDuration

assists

revives

killStreaks

DBNOs

roadKills

teamKills

Game modes analyzed

To keep the analysis focused on the major standard modes, the project analyzed:

squad-fpp

duo-fpp

squad

solo-fpp

duo

solo

🧹 Data Preparation & Transformation

Before building the dashboard, the dataset was examined and prepared for analysis.

The preparation process included:

Reviewing available columns and their analytical relevance

Checking data quality and unusual records

Identifying matches with insufficient player records

Reviewing invalid or impossible gameplay values

Checking zero-duration and other anomalous records

Preparing the dataset for Power BI

Creating calculated measures using DAX

Structuring the analysis around meaningful gameplay questions

The objective was not simply to clean the data, but to ensure that the analysis was based on records that made sense from a gameplay perspective.

🛠️ Tools & Technologies

Tool / Technology

Purpose

Power BI

Interactive dashboard and data visualization

DAX

Measures, KPIs and analytical calculations

Power Query

Data cleaning and transformation

Excel / CSV

Data preparation and source data

Data Analysis

Pattern, comparison and relationship analysis

Data Visualization

Communicating insights through interactive visuals

📈 Dashboard Pages

The report contains a landing page followed by six analytical pages.

1. 🏠 Home

The landing page provides an introduction to the project and navigation to the different analytical sections.



2. 🎮 PUBG Overview

Provides a high-level view of the dataset and overall gameplay performance.

Focus areas

Total matches

Total players

Average match duration

Match type distribution

Overall performance indicators

High-level gameplay patterns



3. 📊 Match Performance

Examines how performance varies across matches and game modes.

Focus areas

Match duration

Match type

Placement performance

Player performance patterns

Differences between game modes



4. ⚔️ Combat Analysis

Focuses on combat-related performance.

Key metrics

Kills

Damage dealt

Assists

Headshot performance

Kill-related statistics

Combat effectiveness

The objective is to understand whether stronger combat performance is reflected in better overall match outcomes.



5. 🧠 Advanced Performance

This page goes beyond basic KPIs and investigates deeper relationships between gameplay variables.

Analytical questions

How are different performance metrics related?

Does stronger combat performance correspond to better placement?

Which combinations of gameplay behaviors appear alongside stronger results?

Are there meaningful differences between player performance patterns?



6. 🚶 Movement & Survival

Analyzes movement behavior and survival-related performance.

Focus areas

Walking distance

Vehicle distance

Swimming distance

Match duration

Healing

Boost usage

Survival-related patterns

The objective is to understand how movement and survival behavior relate to overall performance.



7. 🚨 Anomaly Analysis

The anomaly page looks beyond averages and investigates unusual performance patterns.

Instead of asking only:

"What is normal performance?"

the analysis also asks:

"Which matches or player performances behave differently from the normal pattern?"

This adds another layer of analytical investigation by focusing on exceptions and unusual observations.



🔍 Key Analytical Questions

The dashboard was designed around analytical questions, rather than simply creating visuals for every available column.

Overall Performance

What does overall player performance look like?

What are the major KPIs?

How does performance vary across game modes?

Match Performance

Which game modes show different performance patterns?

How does match duration relate to performance?

How does placement vary across different match types?

Combat

Does higher damage correspond with better placement?

How are kills, assists and headshots related to performance?

Does strong combat performance always result in strong match outcomes?

Advanced Performance

What relationships exist between multiple gameplay variables?

Can combinations of metrics provide a better understanding of performance than individual KPIs?

Movement & Survival

How does movement behavior differ between players?

How do walking and vehicle usage relate to performance?

What role does survival duration play in match outcomes?

Anomaly Analysis

Which performances are unusually high or low?

What characteristics make those performances different from the normal pattern?

💡 Key Analytical Learnings

1. Performance cannot be evaluated using a single KPI

High kills indicate strong combat performance, but they do not automatically indicate strong survival ability, consistency, or final placement.

Combining combat, movement, survival and match-level metrics provides a more complete picture of player performance.

2. Segmentation matters

Different game modes have different gameplay dynamics. Comparing all matches together can hide meaningful patterns.

Segmenting the analysis by game mode makes comparisons more meaningful.

3. Averages do not tell the whole story

The anomaly analysis adds another perspective by moving beyond average performance and investigating unusual observations.

4. Dashboard design should follow analytical questions

The project reinforced the idea that a dashboard should not simply be a collection of charts.

Each visual should contribute to answering a question or supporting a decision.

🧠 How This Project Improved My Analytical Thinking

The biggest change was learning to approach a dataset by asking questions before building visualizations.

Instead of starting with:

"Which chart should I create?"

I learned to start with:

"What question am I trying to answer?"

The analytical process became:

What happened? → Why might it have happened? → Which variables are related? → Is the pattern consistent? → Are there exceptions? → What could the insight help us investigate or decide?

This helped me move from simply reporting numbers to investigating patterns and communicating insights.

💼 Business Relevance

Although the dataset is based on PUBG gameplay, the analytical methodology is directly transferable to business analytics.

The subject could change from players and matches to:

Sales representatives

Customers

Products

Marketing campaigns

Business operations

Employee performance

But the analytical workflow remains similar:

Raw Data → Cleaning → KPI Definition → Segmentation → Trend Analysis → Relationship Analysis → Anomaly Detection → Insights → Decision Support

For example, instead of analyzing player performance, the same approach could be used to analyze:

Sales representative performance

Customer purchasing behavior

Product performance

Regional sales

Operational efficiency

The project therefore helped develop skills that are relevant beyond the gaming domain.

📚 Skills Demonstrated

Technical Skills

Power BI

Power Query

DAX

Data cleaning

Data transformation

KPI development

Data modeling

Interactive visualization

Dashboard development

Analytical Skills

Data exploration

Segmentation

Comparative analysis

Trend analysis

Relationship analysis

Anomaly investigation

Problem decomposition

Insight generation

Data storytelling

Translating data into decision-support information

🚀 Future Improvements

Possible extensions to the project include:

Adding more statistical analysis

Developing a player performance scoring system

Exploring predictive analytics

Investigating additional game modes

Implementing more advanced anomaly detection techniques

Exploring machine learning approaches for performance prediction

Connecting the dashboard to regularly refreshed data

These improvements would extend the project from primarily descriptive and diagnostic analytics toward more predictive analytics.

📸 Dashboard Preview

The complete dashboard is available through the screenshots above.

For the full interactive experience:

👉 🚀 Open Live Power BI Dashboard

📁 Repository Structure

PUBG-Analytics-PowerBI/
│
├── README.md
│
├── 01 - Home.png
├── 02 - PUBG Overview.png
├── 03 - Match Performance.png
├── 04 - Combat Analysis.png
├── 05 - Advanced Performance.png
├── 06 - Movement & Survival.png
└── 07 - Anomaly Analysis.png

👨‍💻 Author

Priyanshu Kumar Bouri

Aspiring Data Analyst focused on:

Power BI • SQL • Excel • Python • Data Visualization • Business Analytics

This project was created as part of my data analytics portfolio to demonstrate practical experience in data preparation, analytical thinking, dashboard development, visualization, and insight communication.
