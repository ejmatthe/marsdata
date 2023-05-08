# marsdata
This assignment composed 2 parts - scraping information from a Mars News website and scraping Mars weather information and analyzing it.

### Part 1 - Mars News
In this section, I was able to remotely navigate the provided website and create a BeautifulSoup object from the html. The article title and news preview were stored in dictionary format, and then combined into a list.

### Part 2 - Mars Weather
For the second part, I remotely navigated and scraped the information as a BeautifulSoup object. This was then manipulated into a Pandas DataFrame, and the datatypes were cast to the appropriate formats. Once constructed, I performed additional functions to analyze the data to answer the following questions. At the end, the dataframe was then exported to a csv file in the Output folder.
1. How many months exist on Mars?  
There are 12 months on Mars.
2. How many Martian days worth of data exist in the dataset?  
There are 1867 Martian days worth of data. 
3. What are the coldest and warmest months on Mars (where measured at Curiosity's location)?  
To help answer this question, I first plotted the data, sorted by numerical month, and then a second plot, organized from lowest temperature to highest temperature. I was then able to determine the coldest month to be 3, and the warmest to be 8 (however, they are both extremely cold compared to Earth!)
4. Which months have the lowest and highest atmospheric pressure on Mars?  
I only did the second plot like above - a plot sorted from lowest to highest. The month with the lowest pressure is 6, and the month with the highest pressure is 9.
5. About how many terrestrial days exist in a Martian year?  
Based on comparing the peaks, there are about 675 terrestrial days in a Martian year. 
