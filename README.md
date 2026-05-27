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



>  ## 📌 Dashboard Features

 1. Dynamic Season Filter  : - A season slicer is provided at the top-right side of the dashboard.

 2. Functionality :
  
     a.  Users can select any IPL season from 2008–2025.
   
     b.  Once the season changes:
   
        1.Champion team changes dynamically
   
        2.Runner-up team changes dynamically
    
     c.  Team logos update automatically
  
     d.  KPIs update based on selected season
  
     e.  Orange Cap and Purple Cap holders update
  
     f.  Top fours and sixes statistics change

     g.  Points table updates for that season
 
     h.  Power BI Concepts Used

     i.  Slicers
 
     j.  Dynamic filtering

     k.  Relationships

     l.  Context transition  using  DAX CALCULATE()   and   FILTER()   functions

  
>  ## 📌 2. Champion and Runner-Up Cards

At the top section of the dashboard, two dynamic cards display =

   1.  IPL Champion
  
   2.  IPL Runner-Up
  
   3.  Dynamic Features
  
   4.  Team name changes according to selected season
  
   5.  Team logo changes dynamically using image URLs
  
   6.  Final match result determines champion and runner-up
  
   7.  DAX Logic Used  : -         1 .  SELECTEDVALUE(),             2 .  CALCULATE(),             3 .  FILTER(),               4.  LOOKUPVALUE(),                   5. RELATED()

   8.  The team logo changes dynamically using a team logo table connected through relationships.


>  ## 📌 3. KPI Cards

The dashboard contains multiple KPI cards that provide season summary statistics.

  * KPIs Included =
  
    1. Total Sixes  : - Displays total sixes hit in the selected IPL season.

    2. Total Fours : - Displays total boundaries (4s) in the selected season.

    3. Total Matches : - Shows total matches played in that season.

    4. Total Teams : - Displays number of teams participating in the season.

    5. Total Half Centuries : - Shows total 50+ scores in the selected season.

    6. Total Centuries : - Shows total centuries scored in the selected season.

    7. Total Venue : - Shows total venues on which matches are played.



>  ## 📌 4. Orange Cap Statistics

This section displays the player with the highest runs scored in the selected IPL season.

 Information Displayed =
   
  *  Player Name
   
  *  Total Runs
   
  *  Team Name
   
  *  Player Image
   
  *  Dynamic Functionality
   

When the season changes =
 

   *  Orange Cap holder changes automatically

   *  Runs update dynamically

   *  Team name changes

   *  Player image changes dynamically

   *  DAX Concepts Used : -           1.   TOPN(),           2. SUMMARIZE(),             3. RANKX(),               4.CALCULATE(),             5.FILTER()



>  ## 📌 5. Purple Cap Statistics

This section displays the highest wicket taker of the selected IPL season.

Information Displayed =
 
   *  Player Name

   *  Total Wickets

   *  Team Name

   *  Player Image

   *  Features

   *  Updates dynamically based on season

   *  Excludes run-outs and retired hurt dismissals

   *  Shows actual bowling wickets only

   *   DAX Concepts Used  : -             1.FILTER(),             2.CALCULATE(),              3.GROUPBY(),             4.MAXX()


>  ## 📌  6 . Most Fours in a Season


This section identifies the player who hit the most fours in the selected season.

Information Displayed =
  
   *  Player Name
  
   *  Number of Fours

   *  Team Name

   *  Player Image

   *   Dynamic Features

   *  Automatically updates with season selection

   *   Team details update dynamically

   *  Player image changes automatically
  
   *  DAX Used  :-        1 . COUNTROWS(),       2 .  FILTER(),      3 .  TOPN(),         4.   SUMMARIZE()


>  ## 📌 7 .  Most Sixes in a Season

This section displays the player with the highest number of sixes in the selected season.

Information Displayed =
 
   *  Player Name
 
   *  Total Sixes
 
   *  Team Name
 
   *  Player Image
 
   *  Dynamic Features
 
   *   Changes according to selected season
 
   *  Dynamically updates player and team details
 
   *  Player images are linked dynamically


>  ## 📌 8. Dynamic Points Table

The points table is one of the major features of the dashboard.

It displays complete team standings for the selected IPL season.

   Information Included =

          1. Team Logo
  
          2. Team Name
  
          3. Matches Played
  
          4. Wins
  
          5. Losses
  
          6. No Result
  
          7. Tie
  
          8. Total Points

  
  
## 🧾 Dynamic Features : -

When season changes :

   *  Teams update automatically
   
   *  Match statistics update dynamically
  
   *  Points table ranking changes
  
   *  Logos update automatically
   
   *  DAX Concepts Used    : -   1 . USERELATIONSHIP(),    2.  CALCULATE(),  3  .  SUMX(),   4  .  FILTER(),    5 . RANKX()  ,   6 .  DISTINCTCOUNT() 



>  ## 📌 9. Dynamic Team and Player Images

The project uses dynamic image URLs to display : 

          Team Logos

          Player Images

          Features

          Images update automatically with season change

          Logos are connected through relationships

          Player images are dynamically fetched using player tables

  

>  ## 📦 Power BI Features Used : - 

Image URL data category
  
   Relationships
  
   LOOKUPVALUE()
  
   Conditional filtering



>  ## ⭐ 10. Navigation Buttons : -

Interactive buttons are added on the left sidebar.

Buttons Included =
  
   *  IPL Official Website
  
   *  IPL Cricbuzz Website
  
   *  IPL ESPN Cricinfo Website
  
   *  IPL Facebook Website
  
   *  IPL Instagram Website
  
   *  IPL Twitter/X Website
  
   *  IPL YouTube Channel
  
  

> ## 📂 Users can : - 

   1. Press Ctrl + Click on the button

   2. Navigate directly to the official website

   3. Check latest IPL updates and live cricket information

   4. Power BI Features Used

   5. Buttons

   6. Web URL Actions

   7. Custom Icons

   8. Tooltip Configuration

   9. Data Sources



> ## 🧩 The project uses IPL datasets including :-

 Main Tables

 IPL Matches Data

  * Contains =

       1.  Match ID
  
       2.  Season
  
       3.  Teams
  
       4.  Winner

       5.  Venue

       6.  Toss Details
      
       7.  Match Results
   
       8.  Ball-by-Ball Data


 * Contains =

      1.  Ball events
     
      2.  Runs
     
      3.  Wickets
   
      4.  Batting information
     
      5.  Bowling information
       
      6.  Teams Table


 * Contains =

      1.  Team names
  
      2.  Team logos
  
      3.  Team details
  
      4.  Players Table

 * Contains =

      1. Player names

      2. Player images

      3. Team associations

      4. Data Modeling

    A proper star schema model is used in the project.
   

## 📈 Relationships

Relationships are created between:

   1.  Matches table

   2.  Ball-by-ball table

   3.  Teams table

   4.  Players table
 
   5.  Key Power BI Modeling Concepts

   6.  One-to-many relationships

   7.  Active and inactive relationships

   8.  USERELATIONSHIP()

   9.  Cross filtering

   10. DAX Functions Used in the Project

The project heavily uses advanced DAX measures for dynamic calculations.



>  ###  Major DAX Functions Used : - 

   1.  CALCULATE()
  
   2.  FILTER()
  
   3.  SUMX()
  
   4.  COUNTROWS()
  
   5.  DISTINCTCOUNT()
  
   6.  TOPN()
  
   7.  RANKX()
  
   8.  GROUPBY()
  
   9.  RELATED()
  
  10. LOOKUPVALUE()
 
  11. USERELATIONSHIP()
 
  12. SELECTEDVALUE()
 
  13. MAXX()
 
  14. VAR
 
  15. RETURN




###  Power BI Features Used : - 

   1. Visualization Features
   
   2. KPI Cards
   
   3. Tables
   
   4. Slicers
   
   5. Buttons

   6. Dynamic Images

   7. Custom Icons

   8. Conditional Formatting

   9. Advanced Features

   10. Dynamic filtering

   11. Drill-through concepts

   12. Interactive navigation

   13. URL Actions

   14. Dynamic ranking

   15. Context transition

   16. Key Insights from Dashboard



>  Users can analyze : -

     1. Best performing teams season-wise
   
     2. Highest run scorers
   
     3. Highest wicket takers
   
     4. Boundary hitters
   
     5. Team standings
   
     6. Overall season statistics
   
     7. Comparative season performance
   
     8. Tools & Technologies Used
   
     9. Power BI Desktop
   
     10. DAX (Data Analysis Expressions)
  
     11. Power Query
  
     12. Data Modeling
  
     13. Excel/CSV IPL datasets
  
     14. Project Highlights
  
     15. Fully Dynamic Dashboard  : - Every visual updates automatically according to selected season.

     16. Interactive User Experience : - Users can explore different IPL seasons with a single click.

     17. Advanced DAX Calculations : - Complex DAX measures are used for rankings, filtering, and dynamic visuals.

     18. Real Cricket Insights : - Provides meaningful cricket statistics and performance analysis.




> ## 🛠️  Possible future improvements:

   1.  Venue-wise analysis
   
   2.  Player career analysis
   
   3.  Team head-to-head analysis
   
   4.  Match prediction visuals
   
   5.  Win percentage analysis
   
   6.  Toss impact analysis
   
   7.  Interactive drill-through pages




## ⭐ Conclusion : -

This IPL Analysis Dashboard is a complete end-to-end Power BI project designed for cricket analytics and visualization.

The project demonstrates : -

   1. Advanced Power BI dashboard development
   
   2. Dynamic DAX calculations
   
   3. Interactive visual design
   
   4. Data modeling concepts
   
   5. Real-world analytics implementation

It provides users with a professional and interactive platform to analyze IPL statistics from 2008–2025.

  
> ## Author : -

 [Ashwini Suryakar](https://www.linkedin.com/in/ashwini-suryakar/)

