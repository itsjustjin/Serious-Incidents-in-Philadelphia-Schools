# Philadelphia Schools Data Analysis

This is my personal project in my journey in learning R and R Markdown. I will be using official School District of Philadelphia (SDP) data, much of which is already clean but will require joining datasets. Thus my goals for this project will be to practice data visualization techniques, syntax, and analysis.
I will primarily be using the tidyverse, dplyr, and ggplot2 packages. 

The techniques applied in this project will primarily be from:

  1. [Richard Landers's Data Science for Social Scientists course](http://datascience.tntlab.org/)
  2. [Sharon Machlis's Practical R for Mass Communication and Journalism Textbook](https://www.routledge.com/Practical-R-for-Mass-Communication-and-Journalism/Machlis/p/book/9781138726918?utm_source=crcpress.com&utm_medium=referral)
  3. [Adam Fleischhacker's A Business Analyst's Introduction to Business Analytics](https://www.causact.com/index.html#welcome)
  4. [Andrew Heiss's Masters level Data Visualization course](https://datavizf18.classes.andrewheiss.com/)

Although I have a background in SQL and Excel VBA, learning R has been especially difficult because there are just so many different ways to do a single thing. Thus I often confuse myself of which syntax to use and whether that's base R or tidyverse. It can be overwhelming at times, but can also be extremely rewarding because of the broad applications of R to research, analytics, and data science. I hope to one day get to a point where I can spit out code for an hour instead of spending an hour figuring out how to do a single task. By being extremely focused on one skill at a time, I can eventually amass an arsenal of tools. As they say, there is only one way to eat an elephant: a bite at a time. 

**[7.22.2020 - Serious Incidents in Philadelphia Schools during SY18-19](https://github.com/itsjustjin/Philly_Schools/blob/master/outputs/serious_incidents.md)**

I performed an initial analysis into one data file of Serious Incidents of which the SDP defines as "incidents reported to School District Police". Skills used in this analysis were:

  1. Downloading and importing an Excel File
  2. dplyr's grouping and summarizing functions
  3. ggplot's geom_bar
  
![image of final output](https://github.com/itsjustjin/Philly_Schools/raw/master/outputs/serious_incidents_files/figure-gfm/Graph%20it-1.png)

**[7.27.2020 - Schools with the Most Incidents](https://github.com/itsjustjin/Philly_Schools/blob/master/outputs/serious_incidents_part2.md)**

I joined the Serious Incidents dataset with Schools Information to analyze which schools have the most incidents. I then graphed it using ggplot. Skills used in this analysis were:

  1. Joining datasets with dplyr
  2. Graphing with ggplot
  
![image of final output](https://github.com/itsjustjin/Philly_Schools/raw/master/outputs/serious_incidents_part2_files/figure-gfm/unnamed-chunk-2-1.png)