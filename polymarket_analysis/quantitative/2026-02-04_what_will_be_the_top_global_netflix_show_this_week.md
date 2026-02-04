## Analysis: What will be the top global Netflix show this week?

- **Category**: Quantitative
- **Cyclicality**: High - The event exhibits a weekly pattern, as Netflix updates its global Top 10 TV shows list every week on Tuesdays, reflecting viewership from the previous week (Monday to Sunday).
- **Automation**: Yes - The outcome data can be automatically retrieved via the public webpage top10.netflix.com, which is updated regularly by Netflix.
- **Suitability Score**: 9
- **Reasoning**: This event is highly suitable for trading due to its predictable weekly pattern and easily accessible outcome data. The market's resolution is based on objective data, reducing the risk of subjective interpretation.

Technical Note: To automate data retrieval, a web scraping script can be set up to extract the top-ranked show from top10.netflix.com on Tuesdays after 3:00 PM ET. The script can be written in a programming language like Python using libraries like BeautifulSoup or Scrapy. Additionally, a scheduler like cron can be used to run the script at the specified time every week.