# cricket-analytics

Created a Power BI Dashboard which helps to review and compare performances of all the players in tournament. The dashboard also enables us to select best eleven of the tournament based on their performance based on some selection criteria

## Steps:
- ### Data Collection:
    Scrapped all the data regarding match and world cup from www.espncricinfo.com and all details about players career from cricbuzz.com using Beautifull Soup library of Python.
    
- ### Data Transformation:
    Performed initial data cleaning after scrapping such as player name correction, match id linking etc. using Pandas.
    Then, transformed the final data for dashboard using Power Query of Power BI.

- ### Data Modelling:
    Connected all the datasets with based on some defined primary keys sucha s team and match ids. Also, created many measures, calculated columns and parameters for data analysis and dashboarding using DAX.
 
- ### Dashboarding:
    Craeted final dashboard using Power BI visuals.
    | ![Screenshot 1](https://github.com/nickel-28/cricket-analytics/assets/84437844/a6fcf141-3c6a-43df-8d66-cec2ef15b4f6)    | ![Screenshot 2](https://github.com/nickel-28/cricket-analytics/assets/84437844/133df831-f6f0-47d8-bdef-8f2a7fb9b323) |
    | -------- | ------- |
    | ![Screenshot 3](https://github.com/nickel-28/cricket-analytics/assets/84437844/3a49afeb-1fdb-48eb-a120-c3078f615a28)  | ![Screenshot 4](https://github.com/nickel-28/cricket-analytics/assets/84437844/033e4d1b-a963-426b-9e54-06cf124af85f)    |
    | ![Screenshot 5](https://github.com/nickel-28/cricket-analytics/assets/84437844/01b73b9a-8393-473b-9829-fe6c04da5348) | ![Screenshot 6](https://github.com/nickel-28/cricket-analytics/assets/84437844/d29f6b52-0556-4f45-9e35-1177c096746e)     |
    | ![Screenshot 7](https://github.com/nickel-28/cricket-analytics/assets/84437844/6b72427b-f2de-4668-92cf-faca270c6530)    | ![Screenshot 8](https://github.com/nickel-28/cricket-analytics/assets/84437844/1cca0efe-16b8-4a34-8475-9d5d1ba02232)    |

## Tools used:
- Python -> Beautiful Soup, Pandas
- Power BI -> Power Query, DAX

