# IPL-ANALYSIS(2008-25)

![Blinkit Dashboard](https://github.com/AshwiniSuryakar09/IPL-ANALYSIS-2008-25/blob/main/dashboard.png)

## 🧾 Project Overview

This project is an interactive IPL Analysis Dashboard developed in Power BI using IPL historical datasets from 2008 to 2025. The dashboard provides complete season-wise insights 
including:

  1. IPL Champion and Runner-Up details

  2. Dynamic team logos based on selected season

  3. Season KPIs

  4. Orange Cap and Purple Cap statistics

  5. Most fours and sixes statistics

  6. Interactive Points Table

  7. External navigation buttons to IPL and cricket-related websites

  The dashboard is fully dynamic. When the user changes the IPL season from the slicer, all visuals, KPIs, player statistics, team logos, and points table data update automatically   according to the selected season.

## 📌 Dashboard Features

1. Dynamic Season Filter

   A season slicer is provided at the top-right side of the dashboard.

   Functionality :
  
   a. Users can select any IPL season from 2008–2025.
   
   b. Once the season changes:
   
        1.Champion team changes dynamically
   
        2.Runner-up team changes dynamically
    
   c. Team logos update automatically
  
   d. KPIs update based on selected season
  
   e. Orange Cap and Purple Cap holders update
  
   f. Top fours and sixes statistics change

   g. Points table updates for that season
 
   h. Power BI Concepts Used

   i. Slicers
 
   j. Dynamic filtering

   k. Relationships

   l. Context transition  using  DAX CALCULATE()   and   FILTER()   functions

  
## 📌 2. Champion and Runner-Up Cards

At the top section of the dashboard, two dynamic cards display:

   IPL Champion
  
   IPL Runner-Up
  
   Dynamic Features
  
   Team name changes according to selected season
  
   Team logo changes dynamically using image URLs
  
   Final match result determines champion and runner-up
  
   DAX Logic Used  : -         1 .  SELECTEDVALUE(),             2 .  CALCULATE(),             3 .  FILTER(),               4.  LOOKUPVALUE(),                   5. RELATED()

   The team logo changes dynamically using a team logo table connected through relationships.


## 📌 3. KPI Cards

The dashboard contains multiple KPI cards that provide season summary statistics.

KPIs Included :
  
  1. Total Sixes  : - Displays total sixes hit in the selected IPL season.

  2. Total Fours : - Displays total boundaries (4s) in the selected season.

  3. Total Matches : - Shows total matches played in that season.

  4. Total Teams : - Displays number of teams participating in the season.

  5. Total Half Centuries : - Shows total 50+ scores in the selected season.

  6. Total Centuries : - Shows total centuries scored in the selected season.

  7. Total Venue : - Shows total venues on which matches are played.



## 📌 4. Orange Cap Statistics

This section displays the player with the highest runs scored in the selected IPL season.

Information Displayed :
   
  Player Name
   
   Total Runs
   
   Team Name
   
   Player Image
   
   Dynamic Functionality
   

 When the season changes:

   Orange Cap holder changes automatically

   Runs update dynamically

   Team name changes

   Player image changes dynamically

   DAX Concepts Used : -           1.   TOPN(),           2. SUMMARIZE(),             3. RANKX(),               4.CALCULATE(),             5.FILTER()


## 📌 5. Purple Cap Statistics

This section displays the highest wicket taker of the selected IPL season.

Information Displayed :
 
   Player Name

   Total Wickets

   Team Name

   Player Image

   Features

   Updates dynamically based on season

   Excludes run-outs and retired hurt dismissals

   Shows actual bowling wickets only

   DAX Concepts Used : -             1.FILTER(),             2.CALCULATE(),              3.GROUPBY(),             4.MAXX()


## 📌  6 . Most Fours in a Season

This section identifies the player who hit the most fours in the selected season.

Information Displayed
  
   Player Name
  
   Number of Fours

   Team Name

   Player Image

   Dynamic Features

   Automatically updates with season selection

   Team details update dynamically

   Player image changes automatically

   DAX Used  :-        1 . COUNTROWS(),       2 .  FILTER(),      3 .  TOPN(),         4.   SUMMARIZE()


## 📌 7 .  Most Sixes in a Season

This section displays the player with the highest number of sixes in the selected season.

Information Displayed
 
  Player Name
 
  Total Sixes
 
  Team Name
 
  Player Image
 
  Dynamic Features
 
  Changes according to selected season
 
  Dynamically updates player and team details
 
  Player images are linked dynamically


## 📌 8. Dynamic Points Table

The points table is one of the major features of the dashboard.

It displays complete team standings for the selected IPL season.

Information Included : - 

   Team Logo
  
   Team Name
  
   Matches Played
  
   Wins
  
   Losses
  
   No Result
  
   Tie
  
   Total Points

  
  
## 🧾 Dynamic Features : -

When season changes:

   Teams update automatically
   
   Match statistics update dynamically
  
   Points table ranking changes
  
   Logos update automatically
  
   DAX Concepts Used    : -   1 . USERELATIONSHIP(),    2.  CALCULATE(),  3  .  SUMX(),   4  .  FILTER(),    5 . RANKX()  ,   6 .  DISTINCTCOUNT() 



## 📌 9. Dynamic Team and Player Images

The project uses dynamic image URLs to display:

  Team Logos

  Player Images

  Features

  Images update automatically with season change

  Logos are connected through relationships

  Player images are dynamically fetched using player tables

  

## 📦 Power BI Features Used

  Image URL data category
  
  Relationships
  
  LOOKUPVALUE()
  
  Conditional filtering



## ⭐ 10. Navigation Buttons

Interactive buttons are added on the left sidebar.

  Buttons Included : 
  IPL Official Website
  
  Cricbuzz
  
  ESPN Cricinfo
  
  Facebook
  
  Instagram
  
  Twitter/X
  
  YouTube
  

## 📂 Users can:

Press Ctrl + Click on the button
Navigate directly to the official website
Check latest IPL updates and live cricket information
Power BI Features Used
Buttons
Web URL Actions
Custom Icons
Tooltip Configuration
Data Sources

## 🧩 The project uses IPL datasets including:

Main Tables
IPL Matches Data

Contains:

Match ID
Season
Teams
Winner
Venue
Toss Details
Match Results
Ball-by-Ball Data

Contains:

Ball events
Runs
Wickets
Batting information
Bowling information
Teams Table

Contains:

Team names
Team logos
Team details
Players Table

Contains:

Player names
Player images
Team associations
Data Modeling

A proper star schema model is used in the project.

## 📈 Relationships

Relationships are created between:

Matches table
Ball-by-ball table
Teams table
Players table
Key Power BI Modeling Concepts
One-to-many relationships
Active and inactive relationships
USERELATIONSHIP()
Cross filtering
DAX Functions Used in the Project

The project heavily uses advanced DAX measures for dynamic calculations.

Major DAX Functions Used
CALCULATE()
FILTER()
SUMX()
COUNTROWS()
DISTINCTCOUNT()
TOPN()
RANKX()
GROUPBY()
RELATED()
LOOKUPVALUE()
USERELATIONSHIP()
SELECTEDVALUE()
MAXX()
VAR
RETURN
Power BI Features Used
Visualization Features
KPI Cards
Tables
Slicers
Buttons
Dynamic Images
Custom Icons
Conditional Formatting
Advanced Features
Dynamic filtering
Drill-through concepts
Interactive navigation
URL Actions
Dynamic ranking
Context transition
Key Insights from Dashboard

Users can analyze:

Best performing teams season-wise
Highest run scorers
Highest wicket takers
Boundary hitters
Team standings
Overall season statistics
Comparative season performance
Tools & Technologies Used
Power BI Desktop
DAX (Data Analysis Expressions)
Power Query
Data Modeling
Excel/CSV IPL datasets
Project Highlights
Fully Dynamic Dashboard

Every visual updates automatically according to selected season.

Interactive User Experience

Users can explore different IPL seasons with a single click.

Advanced DAX Calculations

Complex DAX measures are used for rankings, filtering, and dynamic visuals.

Real Cricket Insights

Provides meaningful cricket statistics and performance analysis.

Future Enhancements

## 🛠️  Possible future improvements:

Venue-wise analysis
Player career analysis
Team head-to-head analysis
Match prediction visuals
Win percentage analysis
Toss impact analysis
Interactive drill-through pages



Conclusion

This IPL Analysis Dashboard is a complete end-to-end Power BI project designed for cricket analytics and visualization.

The project demonstrates:

Advanced Power BI dashboard development
Dynamic DAX calculations
Interactive visual design
Data modeling concepts
Real-world analytics implementation

It provides users with a professional and interactive platform to analyze IPL statistics from 2008–2025.
  
   

