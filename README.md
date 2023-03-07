# Data-Curation-Jinwoo

Goal of this project: Analyze the correlation between vaccination population and COVID-19 cases/deaths in the state of Texas.

Links to any relevant API documentation: Instead of API, I used beautifulsoup, which ispython library. But the original source for the table is - https://en.wikipedia.org/wiki/COVID-19_pandemic_in_Texas#covid-19-pandemic-medical-cases-in-texas-by-county

The license of your data and any source data: The license for the data on the Wikipedia page I used is typically the Creative Commons Attribution-ShareAlike License, which allows for reuse and modification of the data as long as credit is given and any derivatives are also shared under the same license.

A data type and description for each attribute in your data: County - the name of the county in Texas (String) Confirmed Cases - the number of confirmed COVID-19 cases in the county (Float) Probable Cases - the number of probable COVID-19 cases in the county (Float) Total Cases - the number of total COVID-19 cases in the county (Float) Deaths - the number of COVID-19 deaths in the county (Float) Vaccine - the number of people vaccinated in the county (Float) Population - the number of population in the county (Float) Total Cases / 100k - Total cases divided by 100k (Float)

Any known issues or potential issues, such as sources of bias in collection: Since this is only data for Texas, it can be different in other states in US or other countries. Also, since this is the data from wikipedia, the data could be unreliable because it's written by anonymous. Lastly, this is data from recent month. So, it could be different whem the pandemic started.
