# HTML-challenge
# MOD11-Data-Collection
Student:  Ryan Himes
Instructor:  Steven Greene
Bootcamp:  DU-VIRT-DATA-PT-06-2023
29 August 2023

## Table of Contents
- [About](#about)
- [Getting Started](#getting_started)
- [Contributing](#contributing)
- [Summary](#summary)

## About
This comprehensive project encompasses both web scraping and data analysis, encompassing the process of recognizing specific HTML components within a webpage, encompassing both ID and class attributes. We will delve into the techniques for automated data extraction using Splinter for browsing automation and Beautiful Soup for HTML content parsing. These versatile tools empower us to gather diverse data from websites. The scope of scraping extends to capturing HTML tables and recurrent elements, such as multiple news articles or weather updates found on a single webpage. Throughout this endeavor, we will leverage core proficiencies: data collection, data organization and storage, data analysis, and the subsequent visual depiction of insights.

## Getting Started
Jupyter Notebook is required to run this project.

## Contributing
- <a href="https://www.github.com/agostinger/" target="_blank">Adam Gostinger</a>
- <a href="https://www.github.com/jgrubb38/" target="_blank">Jennifer Grubb</a>


## Summary
Section 1: Extracting Mars News through Web Scraping
In the first segment, we embarked on a web-scraping journey centered around the <a href="https://static.bc-edx.com/data/web/mars_news/index.html" target="_blank">Mars News</a> website. Employing a combination of Splinter, the Chrome driver, and the robust capabilities of BeautifulSoup, we diligently dissected the website's content. By meticulously extracting the captivating array of article titles and their succinct summaries, we curated a dictionary for each article, ingeniously amassing them into a Python list.

Section 2: Unveiling Martian Weather Insights via Web Scraping
The second phase delved into the intriguing realm of Martian weather, with our focus intently fixed on the <a href="https://static.bc-edx.com/data/web/mars_facts/temperature.html" target="_blank">Mars Weather</a> webpage. Our tools of the trade remained consistent: Splinter, the Chrome driver, and the unparalleled parsing capabilities of BeautifulSoup. Our meticulous efforts were rewarded as we successfully extracted a comprehensive trove of weather data encompassing a substantial temporal span from Mars.

With this rich dataset at hand, we seamlessly transposed it into the versatile realm of a Pandas dataframe, a potent vessel for structured data. This integration included the assimilation of the extracted titles, further enhancing the context. The data was methodically partitioned based on months, ushering forth insights into the average temperature and atmospheric pressure trends throughout Martian months.

Our scrutiny illuminated intriguing patterns. Months 3 and 4 emerged as the chilly outliers, while the zenith of warmth graced Months 8 and 9. In the domain of atmospheric pressure, Month 6 assumed the role of the nadir, while the barometer scaled its pinnacle during Month 9.

Lastly, our analytical prowess found expression in visual form, as we charted the trajectory of daily minimum temperatures across elapsed days. This meticulous endeavor allowed us to unveil the Martian year's duration. Notably, our plot indicated an approximate Martian year of 675 days, closely aligned with NASA's verified figure of 687 Earth days for a complete Martian orbit.

Through these explorations, this project underscores the synergy between web scraping, data curation, analysis, and visualization, painting a vivid picture of Mars' news landscape and enigmatic weather phenomena.
