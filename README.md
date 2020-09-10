# UFOs

## Overview of Project

In this assignment, we are helping an individual, who is passionate about UFO research, to create a web filter that can scrap information of recent UFO observation from a given dataset and demonstrate those data that fit in certain criteria. 

In the initial dataset, 6 information about each UFO observation are given. Those information includes: date of the observation, city, state, country , shape of the UFO and duration of the observation( in minutes). Those valuable information will be used as the filters later for us to select the information row that we are looking for. In addition to the above information, for each row we are also given a comment of the UFO observation 

## Result

In order to demonstrate how to properly use this web filter, we will first give a brief introduction about what this web page looks like.

!()[]
As the above image shows, there are five filters that are listed on the left section of the webpage: Date, City, State, Country and Shape. In each filter, users are allowed to input text. This filter section is designed to perform multitask, which means users can input single filter or multiple filters at the same time, depending on their own preference.

On the right side of the webpage, you will see a full list of data that is imported from the initial dataset. Before any filter is actioned, this section shows the full information of the dataset. For each row of UFO observation, all 6 information and 1 comment are presented in each row.

It is very easy to use this webpage as it is designed to be user-friendly. Some key functions it has as the following:

It allows the users filter information based on the data they input in the filter search. This is the basic function that this webpage has and it is very straightforward. When user input data in the filter search section, the data table will automatically give the data that fit in the criteria.
It allows the user to perform multiple search at the same time. When user input multiple filters, the table will show the data information that fits in any of the criteria.
It allows the user to remove some of the filter. This is specific function that we design for the user to use it friendly. When user input multiple filters and want to remove one of it, the table will show the data that was previously filtered out and shows the information that only fits in the rest of the filter.



## Drawback and Recommendations

## One drawback
This webpage filter doesn’t demonstrate to the user how many observation and the frequency of each observation under certain criteria. In the current design, this web filter acts more like a data scrapping tool. We hope this web filter can provide more insights or data analysis when the user is inputting information. 

## Two recommendations 
I will suggest to include addition feature that counts the total number of observation that fits in certain criteria. For example, when the user input the state as “ca”, the webpage can show how many observation in total in “ca”. This will help the user to understand better the number and frequency of each state.
Further more, we can add introduce pie plot feature in this webpage. This can be more complex and sophisticated than the previous feature. The ideal outcome is that when the user input a certain criteria, the plot can demonstrate the percentage of each sub-criteria under this criteria. For example, when the user input state “ca”, the pie plot can demonstrate how each city in “ca” accounts for in the total. 
