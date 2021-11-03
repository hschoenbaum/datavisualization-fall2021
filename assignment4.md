# Assignment 4: Interviewing a Data Set

## Step 1: A link to the dataset, your questions, as well as the answers to those questions.
 
 I searched for data sets on kaggle.com and decided on this set that details worldwide COVID-19 vaccination data. When I downloaded the data set and took my first glance at the categories and data available to me, I decided to explore the following three questions:
 
  * Which country was the first to report fully vaccinated individuals?

  * Which company’s vaccine was administered by the most countries worldwide?

  * Which country has the fewest number of vaccinated individuals per hundred residents?

After analyzing the data in Excel, I determined that Israel was the first country to report a fully vacinated individal. I also found that the COVID-19 vaccine produced by Oxford/AstraZeneca was administered by highest number of countries worldwide. Finally, I found that BLANK had the fewesr number of vaccinated individuals per 100 residents. In assessing the answers I found, I have decided that the third answer is probably the most newsworthy and should be the one I write about for Step 3. 

I was interested in the other two questions as well, but I think there are additional unanswered questions that make those two options less concrete. For instance, I'm not sure I could use the first answer to accurately determine which country had the very first fully vaccinated individuals because there were a lot of discrepancies between countries when it came to collecting and reporting vaccination data. As for the seconf answer, it's interesting to see which vaccine manufacturers had distribution deals with the most countries, but this question does not answer which manufacturer distributed the highest total number of vaccines. If I thought this question was more newsworthy, I would analyze that and ask some additional follow-up questions.

## Step 2: Write down all steps used to clean and analyze the data, including any Excel formulas.
I downloaded the data as a .csv file. Then, to begin, I looked through the spreadsheet to pinpoint any irregularities and determined whether any blank boxes needed to be filled in. I also cleaned up the column headings to make sure there wasn't any overlap that would interfere with how I planned to filter the data.

To answer my first question, I clicked the filter button then clicked the dropdown arrow on the Date column and unchecked the 2021 box so that I was only seeing data from 2020, which would give me the earlier recorded vaccination dates. I filtered the data in the Date column in ascending order so I would see the earliest dates at the top of my spreadsheet. I then looked at the People Fully Vaccinated column and compared that with my Date and Country columns to determine the answer to my question. I found that Israel was the first country to report a fully vaccinated individual. They reported one fully vaccinated person on Dec. 19, 2020. Close behind were Germany, Ireland, Switzerland, Belgium, Canada and Estonia, all of which reported fully vaccinated individuals by the end of 2020.

Filtering the data for my second question was more difficult because many countries use multiple vaccine providers, so there were many instances of multiple vaccine providers listed in the Vaccine field next to a country, just separated by commas. This made it challenging to isolate specific vaccines in my filtering criteria. I decided to place the data in a pivot table and see what I could do from there. I clicked command + a to copy all the data and hit Insert -> Pivot Table to create a pivot table in a new sheet. I sorted my data in the pivot table so that countries made up the Rows field and I put Total Vaccinations in the Values/Sum category (because there were several entries per country that I wanted to consolidate). I set my filter as Vaccines, then I clicked the drop down arrow on the filter and wrote down the name of each vaccine manufacturer. I proceeded to type the name of each vaccine manufacturer into the filter search bar and deselected the other manufacturers to find the list of all countries that administered vaccines from that provider. The provider that had the most countries show up when I filtered the data (highest number of rows of countries) was the answer to my second question. I found that the Oxford/AstraZeneca vaccine had been distributed to the highest number of countries (180), followed by Pfizer/BioNTech (140).


## Step 3: Write a sample headline and nut graf based on the most interesting of the three questions.