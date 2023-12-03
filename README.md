# Module 11 Challenge Web Scrapping


## Part 1: Mars News Web Scraping
I started by exploring the Mars News website to scrape the latest news articles. Using Python, along with libraries such as **Splinter** for automated browsing and **BeautifulSoup** for parsing HTML, I extracted the titles and preview text of the latest news related to Mars exploration.

Each news article's title and preview text were stored in a Python dictionary with `title` and `preview` keys. I then gathered these dictionaries into a list to maintain a structured collection of the current happenings around Mars exploration missions.


## Part 2: Mars Weather Data Analysis
The next phase involved visiting the Mars Temperature Data Site to scrape temperature and atmospheric pressure data. This data gives insights into the Martian climate and helps us understand the conditions faced by rovers and, potentially, future human missions.

The scraped data from the HTML table was neatly organized into a **Pandas** DataFrame, aligning with the original table's structure. I made sure the DataFrame's columns matched the website's table headings and converted data types where necessary for accurate analysis.

With the data ready, I proceeded to analyze it using Pandas functions to answer some intriguing questions about Mars, such as the number of Martian months, the range of Martian days covered in the dataset, and the coldest and warmest months at Curiosity's location. The analysis included plotting the average minimum daily temperature and atmospheric pressure for all months as bar charts.

Lastly, I estimated the number of Earth days in a Martian year by visually plotting the daily minimum temperature and using the relationship between Earth days and Martian sols.

**The analyzed data was then exported to a CSV file for easy accessibility and sharing.**

## Conclusion
This project was a deep dive into the environmental patterns on Mars, made possible through web scraping and data analysis. The insights gained pave the way for more informed discussions about Mars's climate and enhance our preparedness for future explorations.
