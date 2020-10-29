# AMS_Project_Svetlana_Alex
### Project Amsterdam IHDAFT 2020

The purpose of this project is to check if there is a correlation between increase in population of Amsterdam and increase in bikes in Amsterdam.

Programming part of the project is done on Python 3.

**Data sources:**
- https://data.amsterdam.nl/
- https://opendata.cbs.nl/statline/#/CBS/nl/navigatieScherm/thema
- https://www.verderfietsen.nl/
- https://www.timetomomo.com/nl/
- Meerjarenplan fiets 2017-2022

**Project structure:**
- main.ipynb
- confiscated.ipynb
- Population.ipynb
- Purchased.ipynb
- stolen.ipynb

Each source of data has been processed in a separate Jupyter notebook and then consolidated in one data frame in main.ipynb.

**Calculations and assumptions:**
1) No data has been found regarding purchased bikes in Amsterdam so pro rata as per population ratio had been taken.
2) No data has been found regarding stolen bikes destroyed so assumption that 100% of stolen bikes return to the market has been used, hence
    this data can be ignored for the purpose of this project.
3) No exact data has been found regarding confiscating bikes been destroyed so average ratio of 1/3 had been used.
4) No exact annual data has been found regarding bikes fished out of the canals so average amount of 6000 had been used.
