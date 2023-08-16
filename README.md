# Mars_Module_11

This Repo consists of 2 notebooks ( parts 1 & 2), in which the codes for data scraping can be found. It also consists of a .csv file of the dataframe in response to question 6..

## Analysis

In addition to the responses in the notebooks, please see below the summary of the analysis.

5 -  How many months exist on Mars? : 12
  -  How many Maritan days worth of data exists in the scraped dataset? 1867
  - What are the coldest and warmest months on Mars? The 'warmest' month is month 8. The coldest month is month 3.
  
    - Which months have the lowest and highest atmospheric pressure? Month 9 has the highest pressure and Month 6 has the lowest.
    - See bar chart in jupyter notebook.
    
    -About how many terrestrial days are in a Martian year? A visual assessment of the peaks and troughs in the recorded temperatures (above), indicates: 3 peaks, and two troughs, which can be used to estimate the Earth days in a Martian year of around 680-690 days.



I had assistance from an AskBCS tutor to help me identify why my for loop wasn't churning out the expected results, (in creating mars_temps, the nested for line, "strip_data = [td.text.strip() for td in data]" was causing issues since I hadn't got the parentheses correctly ordered.
I also referred to stack overflow for groupby and sort_values (callpete's answer on https://stackoverflow.com/questions/27018622/pandas-groupby-sort-descending-order, gave me insight into why my code was not working, along with a discussion with my partner, Philip Brown, who correctly identified that I should run the grouby, then mean, then sort_values, to ensure that the values would sort. As usual, I have also used the course materials extensively.
