# Assignment 4: Interviewing a Data Set

**Hannah Schoenbaum**

## Step 1: A link to the dataset, your questions, as well as the answers to those questions.
 
I searched for data sets on kaggle.com and decided on this [set that details worldwide COVID-19 vaccination data](https://github.com/hschoenbaum/datavisualization-fall2021/blob/main/country_vaccinations%20copy.csv). When I downloaded the data set and took my first glance at the categories and data available to me, I decided to explore the following three questions:
 
  * Which country was the first to report fully vaccinated individuals?

  * Which company’s vaccine was administered by the most countries worldwide?

  * Which country currently has the fewest number of fully vaccinated individuals per hundred residents?

After analyzing the data in Excel, I found that Israel was the first country to report a fully vacinated individal. I also found that the COVID-19 vaccine produced by Oxford/AstraZeneca was administered by highest number of countries worldwide. Finally, I found that Mexico has the fewest number of fully vaccinated individuals per 100 residents, out of the counties that reported data in the last month (October 2021). 

## Step 2: Write down all steps used to clean and analyze the data, including any Excel formulas.
I downloaded the data as a .csv file. Then, to begin, I looked through the spreadsheet to pinpoint any irregularities and determined whether any blank boxes needed to be filled in. I also cleaned up the column headings to make sure there wasn't any overlap that would interfere with how I planned to filter the data.

To answer my first question, I clicked the filter button then clicked the dropdown arrow on the Date column and unchecked the 2021 box so that I was only seeing data from 2020, which would give me the earlier recorded vaccination dates. I filtered the data in the Date column in ascending order so I would see the earliest dates at the top of my spreadsheet. I then looked at the People Fully Vaccinated column and compared that with my Date and Country columns to determine the answer to my question. I found that Israel was the first country to report a fully vaccinated individual. Israel reported one fully vaccinated person on Dec. 19, 2020. Close behind were Germany, Ireland, Switzerland, Belgium, Canada and Estonia, all of which reported fully vaccinated individuals by the end of 2020.

Filtering the data for my second question was more difficult because many countries use multiple vaccine providers, so there were many instances of multiple vaccine providers listed in the Vaccine field next to a country, just separated by commas. This made it challenging to isolate specific vaccines in my filtering criteria. I decided to place the data in a pivot table and see what I could do from there. I clicked command + a to copy all the data and hit Insert -> Pivot Table to create a pivot table in a new sheet. I sorted my data in the pivot table so that countries made up the Rows field and I put Total Vaccinations in the Values/Sum category (because there were several entries per country that I wanted to consolidate). I set my filter as Vaccines, then I clicked the drop down arrow on the filter and wrote down the name of each vaccine manufacturer. I typed the name of each individual vaccine manufacturer into the filter search bar and deselected the other manufacturers to find the list of all countries that administered vaccines from that provider. The provider that had the most countries show up when I filtered the data (largest number of rows of countries) was the answer to my second question. I found that the Oxford/AstraZeneca vaccine had been distributed to the highest number of countries (180), followed by Pfizer/BioNTech (140).

For my third question, I wanted to pull from the most recent data, so I started by clicking the filter tool, then the drop down arrow on the Date column. I selected 2021 and put the data in descending order, which gave me the most recent data first at the top of my spreadsheet. To stick to timely observations, I decided to only look at the month of October, 2021. I placed the October data in a separate sheet then filtered the People Fully Vaccinated Per Hundred category in ascending order to determine which country had the fewest number of vaccinated individuals per hundred residents as of October 2021. I found that, of the countries that reported data on fully vaccinated individuals in October 2021, Mexico was the country with the fewest number of fully vaccinated individuals per hundred residents (41.34 people per hundred). I think this is the most interesting data I found, but because several countries, particularly poorer countries, did not report data in the month of October, I don't think this data can be used to make assertions on the global scale as I had hoped it would.

I had planned to use the answer to my third question to write my sample headline and nut graf, but because of the lack of recently reported data on fully vaccinated individuals, I don't think the data I found is the most representative. I've decided to instead write my sample headline and nut graf about the answer to my second question for Step 3.

## Step 3: Write a sample headline and nut graf based on the most interesting of the three questions.

**AstraZeneca distributes COVID-19 vaccine to more countries than any other manufacturer**

The COVID-19 vaccine manufactured by the University of Oxford and the pharmaceutical firm AstraZeneca has been distributed in more countries than the vaccines produced by other manufacturers, according to global vaccination data from Our World in Data. Oxford–AstraZeneca distributes its vaccine to 180 countries, followed by Pfizer-BioNTech, which dristributes to 140 countries. The Oxford–AstraZeneca vaccine is unlike other vaccines in that it can be stored in conventional refrigerators, with a shelf life of up to six months, and only costs $3 per dose to produce. This vaccine is also the only one available in many developing countries, particularly in Africa, where AstraZeneca has arranged to sell the vaccine at production price to support low- and middle-income nations.
