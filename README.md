# Sports-Analysis-using-Tableau
# FIFA Player Analysis Project

## Table of Contents
- [Introduction](#introduction)
- [Tools Used](#tools-used)
- [Dataset Description](#dataset-description)
- [Analysis and Results](#analysis-and-results)
  - [1. Top Countries by Number of Players](#1-top-countries-by-number-of-players)
  - [2. Yearly Player Enrollment Curve](#2-yearly-player-enrollment-curve)
  - [3. Skill Moves Analysis by Preferred Foot](#3-skill-moves-analysis-by-preferred-foot)
  - [4. Average Age of Players and Top 5 Youngest Countries](#4-average-age-of-players-and-top-5-youngest-countries)
  - [5. Contract Expiry in 2020](#5-contract-expiry-in-2020)
  - [6. Storyboard Analysis](#6-storyboard-analysis)
- [Findings](#findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)

## Introduction
This project analyzes a dataset of FIFA players to uncover insights about player demographics, contract details, and skill attributes. The analysis aims to provide valuable information for decision-makers in football management, such as identifying top countries by player count, analyzing player skills, and more.

## Tools Used
- **Tableau**: For data visualization and creating dashboards.
- **Pandas**: Data cleaning and preprocessing.
- **Python**: For data manipulation.

## Dataset Description
The dataset used in this project contains detailed information on FIFA players, including attributes like age, nationality, skill moves, contract details, and preferred playing foot. This dataset is crucial in understanding trends and making informed decisions in the football industry.

## Analysis and Results

### 1. Top Countries by Number of Players
- **Analysis**: A bar chart was created to display the top countries with the most players.
- **Result**: ![Players by country](https://github.com/user-attachments/assets/0b284910-6382-4679-a8fd-8bbab047884a)
  - England has highest number of players.
  - Players were spread across different countries,with multiple countries having 1 player.


### 2. Yearly Player Enrollment Curve
- **Analysis**: A line chart was plotted showing the trend of player enrollments per year.
- **Result**: ![Players joined by year](https://github.com/user-attachments/assets/1fd351b9-7838-449b-9b48-d86d774f398a)
  - The number of enrollment till 2013 can be seen as linear,after 2013 we can see steep rise in enrollment


### 3. Skill Moves Analysis by Preferred Foot
- **Analysis**: A tree map was used to represent the distribution of skill moves based on the preferred foot.
  **Result**: ![Skilled moves based on preferred foot](https://github.com/user-attachments/assets/29196cbe-362e-4b2b-8cb1-44d9f161f759)
  - Number of skilled moves on Right foot can be seen greater than on left foot


### 4. Average Age of Players and Top 5 Youngest Countries
- **Analysis**: A bar chart was created to display the countries with the youngest average player age.
 **Result**: ![Top 5 countries having youngest age players by average](https://github.com/user-attachments/assets/4aa08865-9fb7-4835-ac4a-829c7008e8a9)
  - Indonesia can be seen as having the youngest avergae player and zambia with oldest average player in the list. 


### 5. Contract Expiry in 2020
- **Analysis**: A filter was applied to find players with contract expiry in 2020, and the results were summarized.
 **Result**: ![Players whose contract expire in 2020](https://github.com/user-attachments/assets/deb9078a-632b-4d98-834b-74d55cece138)
  - Contract of 4027 player can been as expiring in 2020.


### 6. Storyboard Analysis
- **Story Points**:
  - **Body Type-Wise Distribution**: Analyzed the distribution of players based on their body type.
    ![Story board](https://github.com/user-attachments/assets/34d43b98-5bec-45c6-8150-e15c98c8b29a)
    - The majority of players fall into the "Normal" category, followed by "Lean". There are fewer players in the "Skinny" and "Shaggy" categories, with minimal representation for other body types.

  - **Position Wise Average Wages**: Evaluated the average wages of players based on their playing position to find the highest-paid position.
    ![Story board (1)](https://github.com/user-attachments/assets/6b268618-7339-40d3-8158-b9073b16a240)
    - Highest-Paid Position: The "LF" (Left Forward) position is the highest-paid, with an average wage of 52,688 (units not specified in the image).
    - Top-Earning Positions: Positions like "LAM" (Left Attacking Midfielder) and "RAM" (Right Attacking Midfielder) also command high average wages.
    - Wage Distribution: There is a significant disparity in wages between different positions. While some positions earn substantially more, others like "GK" (Goalkeeper) and "ST" (Striker) have relatively lower average wages. 

  - **Average Value of Players and Wages Over Time**: Analyzed how the average value of players and wages have varied over the years using a dual-axis graph.
  - ![Story board (2)](https://github.com/user-attachments/assets/a6dba3ff-95aa-4311-aee1-a51f965d0d30)
    - Similar Trends: Both the average wages and average values of players seem to follow the same general pattern over the years.
    - Peak in Value: There is a significant peak in the average value of players around the year 2005.
    - Wage Growth: Average wages have been steadily increasing over the years, with a more pronounced growth period from 2005 to 2010.
    - Correlation: The statement suggests a correlation between the average wages and average values of players.


## Findings
- Country Dominance: England is the country with the highest number of players, followed by Germany and Spain. This suggests that these countries have strong football infrastructures and popular domestic leagues.
- Enrollment Trends: The number of player enrollments has increased significantly over the years, particularly after 2013. This may indicate growing interest in football and increased accessibility to training and development opportunities.
- Skill Move Preference: Right-footed players tend to have a slightly higher number of skill moves compared to left-footed players. However, both groups demonstrate a wide range of skill move abilities.
- Age Demographics: Indonesia has the youngest average player age, while Zambia has the oldest. This suggests that some countries prioritize youth development, while others may have older player bases.
- Contract Expiry: A significant number of players had contracts expiring in 2020, highlighting the need for clubs to plan for contract renewals and potential transfers.

## Recommendations
- Talent Development:Countries with a large number of players should invest in developing youth football programs to nurture young talent and ensure a sustainable pipeline of players.
- International Cooperation: Collaborate with countries with strong football infrastructures to share knowledge, expertise, and resources in player development.
- Skill Development: Focus on developing both offensive and defensive skills for players, as well as a balance of physical and technical abilities.
- Contract Management: Clubs should proactively manage player contracts to avoid contract expirations and potential losses due to free transfers.
- Data-Driven Decision Making: Utilize data analytics to identify emerging talent, assess player performance, and inform transfer strategies.

## Limitations
- The dataset may not include all active FIFA players.
- Some player attributes might be missing or inaccurately reported.
- Analysis is limited to the available data and may not reflect the most current player information.

