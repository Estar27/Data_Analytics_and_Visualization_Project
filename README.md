# Social Media Content Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools and Techniques](#tools-and-techniques)
- [Data Cleaning/Preparation](#data-cleaningpreparation)
- [Data Modelling](#data-modelling)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Visualization](#visualization)
- [Results/Findings](#resultsfindings)
- [Limitations](#limitations)
- [Recommendations](#recommendations)
- [References](#references)


## Project Overview

This data analysis project focuses on evaluating the content performance of a social media company over the months in a given year. By thoroughly analyzing diverse aspects of the content data, we aim to uncover significant trends and patterns that will inform our understanding of audience engagement and content efficacy. Our goal is to derive actionable, data-driven recommendations that will enable the company to optimize its content strategy and enhance overall performance. Through this comprehensive analysis, we aspire to provide valuable insights that will support decision-making and drive future growth.
![bar plot](https://github.com/Estar27/Data_Analytics_and_Visualization_Project/blob/main/Bar_plot.png?raw=true)

## Data Sources
### 1.Content Data (Content.csv)
This dataset represents content items along with user details and categorical information.
#### Key Columns:
- **ContentID** (Primary Key)
- **UserID** (ID of the user who created the content)
- **Type** (Type of content, e.g., article, video)
- **Category** (Categorical classification of the content, e.g., technology, entertainment)
- **URL** (Link to the content)

### 2.Reaction Data (Reaction.csv)
This dataset captures user reactions to the content, along with the type of reaction and the date/time it 
occurred.
#### Key Columns:
- **ContentID** (Foreign Key referencing Content.csv)
- **UserID** (ID of the user who reacted)
- **Type** (Type of reaction, e.g., like, dislike)
- **Datetime** (Date and time of the reaction)

### 3.Reaction Types Data (Reactiontypes.csv)
This dataset categorizes the reaction types, sentiment, and scores.
#### Key Columns:
- **Type** (Type of reaction)
- **Sentiment** (Sentiment associated with the reaction, e.g., positive, negative, neutral)
- **ReactionScore** (Numerical score representing the reaction)

## Tools and Techniques
- **Excel** - Using various excel features including filters, Vlookup, Pivot table and built custom charts. [Download here](https://microsoft.com)
- **Power point** - Using canva, design tools to create a presentation [Download here](https://microsoft.com)

## Data Cleaning/Preparation
In the initial data preparation phase, we performed the following tasks:
- Data loading and inspection.
- Handling null values and duplicates.
- Data cleaning and formatting of Data types

## Data Modelling
At this phase, the following steps were made:
- Merging the reactiontypes dataset with the reaction data using the merge function from the Power Editor.
-  Further integrated the combined dataset with the Content dataset to create a comprehensive data structure.
- Eliminated unnecessary columns from the complete dataset to enhance focus and reduce complexity.

## Exploratory Data Analysis
EDA involved exploring the comprehensive content dataset to answer key questions, such as:
- What is the top 5 performing Content Category?
- What month has the highest post?
- What is the best performing Content Category?
- Total number of Content category and Reaction?

![Line graph](https://github.com/Estar27/Data_Analytics_and_Visualization_Project/blob/main/Line_graph%20and%20Cards.png?raw=true)

![Pie chart](https://github.com/Estar27/Data_Analytics_and_Visualization_Project/blob/main/Pie_chart.png?raw=true)

## Visualization
Created various visualization including:
- Barchart to compare the various content categories
- Piechart to see the percentage difference among categories
- Line graph to show the trends of post over time

## Results/Findings
The analysis results can be summarized as follows:
- The top five performing content categories are Animals, Science, Healthy Eating, Technology, and Food, with Animals leading the way.
-  May saw the highest number of posts, but January, August and December are close by.
- The content is distributed across 16 categories, each generating reactions in 16 different types.

## Limitations 
- Data Scope: The analysis focused on the company's content categories, lacking comprehensive customer information.
- Lack of Customer Insights: Absence of customer demographics and feedback limited understanding of preferences and trends.
- Impact on Findings: As a result, findings may not reflect broader market trends, affecting analysis effectiveness.

## Recommendations
Based on the analysis, we recommend the following actions:
- Invest in promotions and campaigns that are related to your top perfoming categories in order to maxixmize revenue.
- Focus on making posts that are related to Animals 

## References

1. [Youtube](https://www.youtube.com/watch?v=aUMEx4in2iU)
2. [Udemy](https://www.udemy.com/course/dataanalysiswithexcelandpbi/learn/lecture/39816494?start=0#content)

😃 💻 
