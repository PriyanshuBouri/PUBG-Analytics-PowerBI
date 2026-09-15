PUBG Player Performance Analytics Dashboard

An interactive Power BI analytics project built to explore PUBG player performance, match behavior, combat effectiveness, movement, survival, and unusual performance patterns.

The project demonstrates an end-to-end analytics workflow:

Data Preparation → KPI Development → Segmentation → Comparative Analysis → Relationship Analysis → Anomaly Analysis → Interactive Data Storytelling

🔗 Live Interactive Dashboard

View the Interactive Power BI Dashboard

The Power BI report is hosted on Power BI Service. The .pbix file is not included because of its file size. This repository provides the dashboard screenshots, project documentation, and live interactive report.

🎯 Project Objective

The objective of this project was to analyze PUBG gameplay data and understand the factors associated with player performance and match outcomes.

Rather than focusing on a single metric such as kills or wins, the analysis combines:

Combat performance

Damage, kills and assists

Headshot performance

Match placement

Survival duration

Movement behavior

Vehicle usage

Healing and boosting behavior

Performance across different game modes

Unusual or anomalous performances

The goal was to move beyond simply reporting numbers and investigate relationships, patterns, differences, and exceptions within the data.

📊 Dataset

The project is based on the PUBG Finish Placement Prediction dataset from Kaggle, using the train_V2 gameplay data.

Important fields used

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

The analysis focused on six major game modes:

squad-fpp

duo-fpp

squad

solo-fpp

duo

solo

🧹 Data Preparation

Before building the dashboard, the dataset was examined and prepared for analysis.

The preparation process included:

Reviewing available columns and their analytical relevance

Checking data quality and unusual records

Handling matches with insufficient player records

Identifying invalid or impossible gameplay values

Reviewing zero-duration and other anomalous records

Preparing the data for Power BI

Creating calculated measures using DAX

Structuring the analysis around meaningful gameplay questions

The objective was not simply to clean the data, but to ensure that the resulting analysis was based on records that made sense from a gameplay perspective.

🛠️ Tools & Technologies

Power BI

DAX

Power Query

Excel / CSV data preparation

KPI development

Data visualization

Data analysis

Interactive dashboard design

📈 Dashboard Structure

The report contains a landing page followed by six analytical pages.

1. Home

The landing page provides an introduction to the project and navigation to the different analytical sections of the dashboard.



2. PUBG Overview

Provides a high-level view of the dataset and overall gameplay performance.

The page focuses on:

Total matches

Total players

Average match duration

Match type distribution

Overall performance indicators

High-level gameplay patterns



3. Match Performance

Examines how performance varies across matches and game modes.

The analysis focuses on:

Match duration

Match type

Placement performance

Player performance patterns

Differences between game modes



4. Combat Analysis

Focuses on combat-related performance.

Key metrics include:

Kills

Damage dealt

Assists

Headshot performance

Kill-related statistics

Combat effectiveness

The objective is to understand whether stronger combat performance is reflected in better overall match outcomes.



5. Advanced Performance

This page goes beyond basic KPIs and investigates deeper relationships between gameplay variables.

It is designed to answer questions such as:

How are different performance metrics related?

Does stronger combat performance correspond to better placement?

Which combinations of gameplay behaviors appear alongside stronger results?

Are there meaningful differences between player performance patterns?



6. Movement & Survival

Analyzes movement behavior and survival-related performance.

The analysis includes:

Walking distance

Vehicle distance

Swimming distance

Match duration

Healing

Boost usage

Survival-related patterns

The objective is to understand how movement and survival behavior relate to overall performance.



7. Anomaly Analysis

The anomaly page looks beyond averages and identifies unusual performance patterns.

Instead of asking only:

"What is normal performance?"

the analysis also asks:

"Which matches or player performances behave differently from the normal pattern?"

This helps identify unusually high or low performance and provides another layer of analytical investigation.



🔍 Key Analytical Questions

The dashboard was designed around questions rather than simply creating visuals for every available column.

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

One of the most important lessons from the project was that player performance cannot be evaluated using a single KPI.

For example, high kills indicate strong combat performance, but they do not automatically indicate strong survival ability, consistency, or final placement.

Combining combat, movement, survival, and match-level metrics provides a more complete picture of performance.

The project also demonstrated the importance of segmentation. Different game modes have different gameplay dynamics, so comparing all matches together can hide meaningful patterns.

The anomaly analysis added another layer by moving beyond averages and investigating unusual observations.

🧠 Analytical Thinking Developed

This project changed the way I approach data analysis.

Instead of starting with:

"Which chart should I create?"

I learned to start with:

"What question am I trying to answer?"

The analytical process became:

What happened? → Why might it have happened? → Which variables are related? → Is the pattern consistent? → Are there exceptions? → What could the insight help us investigate or decide?

This helped me move from simply reporting numbers to investigating patterns and communicating insights.

💼 Business Relevance

Although the dataset is based on PUBG gameplay, the analytical methodology is directly transferable to business analytics.

The same workflow can be applied to:

Sales analytics

Customer analytics

Marketing analytics

Operations analytics

Employee performance analytics

Product analytics

For example, instead of analyzing player performance, the same approach could be used to analyze sales representative performance, customer behavior, product performance, or operational efficiency.

The transferable workflow is:

Raw Data → Cleaning → KPI Definition → Segmentation → Trend Analysis → Relationship Analysis → Anomaly Detection → Insights → Decision Support

This project helped strengthen not only my Power BI skills, but also my ability to approach an unfamiliar dataset, formulate analytical questions, investigate patterns, and communicate findings clearly.

🚀 Future Improvements

Possible future improvements include:

Adding more statistical analysis

Exploring predictive analytics

Building player-level performance scoring

Investigating additional game modes

Adding more advanced anomaly detection techniques

Exploring machine learning approaches for performance prediction

Connecting the dashboard to regularly refreshed data

These improvements would extend the project from primarily descriptive and diagnostic analytics toward more predictive analysis.

📸 Dashboard Preview

All dashboard pages are available in the repository under the screenshot files.

For the fully interactive experience, use the Live Power BI Dashboard.

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

Aspiring Data Analyst focused on Power BI, SQL, Excel, Python, data visualization, and business analytics.

This project was created as part of my portfolio to demonstrate practical data analysis, dashboard development, and analytical problem-solving skills.
