# A2: U.S. COVID Trends

## Overview
In many ways, we have come to understand the gravity and trends in the COVID-19 pandemic through data. Regardless of media source, people are consuming more epidemiological information than ever, primarily through reported figures, charts, and maps.

This assignment is your opportunity to work directly with the same data used by the [New York Times](https://github.com/nytimes/covid-19-data/). While the analysis is guided through a series of questions, it is your opportunity to use programming skills to ask more detailed questions about the pandemic.

## Getting Started
You should start this assignment by opening up the `analysis.R` script. The script will guide you through an initial analysis of the data.

* **Coding prompts.** Complete the coding prompts in `analysis.R`. You MUST use the `dplyr` package.

* **Reflection prompts.** Throughout `analysis.R`, there are prompts labeled `"Reflection"`. Please write at least 1-3 sentences for each of these prompts below in this `README.md` file. As appropriate, provide evidence, give justification for your opinions, or genuinely reflect on your views. Please strive for concise, clear, and interesting writing.

## Reflection 1
Before actually calculating the total number of COVID cases and deaths, record your guesses for the following questions.

Guess: How many total COVID cases do you think there have been in the U.S.?

-There might be millions of cases in the U.S.

Guess: How many total COVID-related deaths do you think there have been in the U.S.?

-There might be thousands of deaths in the U.S.

Guess: Which state do you think has the highest number of COVID cases, and which state do you think has the lowest?

-I think CA has the highest number of COVID cases, and Alaska has the lower COVID cases. 

## Reflection 2
Did the number of COVID cases and deaths surprise you? Why or why not? What about the states with the highest and lowest number of cases? How did your guesses line up with the actual results? Answer in at least 1-3 sentences
-The number of COVID cases and deaths did surprise me, as they were higher than I expected. The states with the highest and lowest number of cases were also surprising, especially Alaska having the lowest cases instead of the state I initially guessed. The actual data differed from my expectations.

## Reflection 3
Which county has the highest number of cases in the state of Washington, and does it surprise you? Why or why not? (You may need to google this county to learn about it) Answer at least in 1-3 sentences

-King County has the highest number of COVID-19 cases in the state of Washington. This does not surprise me since  King County has large population county in Washington and includes major cities like Seattle.

## Reflection 4
Why are there so many observations (counties) in the variable `lowest_deaths_in_each_state`? That is, wouldn't you expect the number to be around 50? Why is the number greater than 50? Answer in at least 1-3 sentences

-The number of observations in lowest_deaths_in_each_state is greater than 50 because there are multiple counties in some states with the same lowest number of COVID-related deaths, resulting in multiple same answer for those states.

## Reflection 5
What do you think about the number and scale of the inconsistencies in the data? Does the fact that there are inconsistencies mean that people should not use this data? Why or why not? Answer in at least 1-3 sentences

- I think those inconsistencies in the data are worth to study. We should use this Data instead of disregard them, because we can use those data to make data more reliable to use in the future.

## Reflection 6
Why were you interested in this particular question? Were you able to answer your question with code? What did you learn? Answer in at least 1-3 sentences
-I was interested in exploring the average number of new COVID cases per day in the most recent data. With the code provided, I was able to answer the question and calculate the average new cases per day for the entire country. I learned that the average number of new cases per day can be a useful to understand the current COVID situation in the U.S.

## Reflection 7
What, if anything, made you curious about this COVID analysis? What, if anything, surprised you? What might you do the same or differently on your next data wrangling project? Answer in at least 1-3 sentences
-I was curious to see how the COVID data would evolve over time and how different states would be affected. The different various variable in the data sets surprise me. On my next data wrangling project, I would continue to use the tidyverse and dplyr packages for efficient data manipulation, because it is easy to seattle the data with those package.
