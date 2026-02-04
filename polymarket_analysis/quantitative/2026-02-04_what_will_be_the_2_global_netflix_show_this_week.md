## Analysis: What will be the #2 global Netflix show this week?

- **Category**: Quantitative
- **Cyclicality**: High - The event exhibits a weekly pattern, as Netflix updates its global Top 10 TV shows list every week on Tuesdays, reflecting viewership from the previous week (Monday to Sunday).
- **Automation**: Yes - The outcome data can be automatically retrieved via scraping the top10.netflix.com webpage, which is updated regularly by Netflix.
- **Suitability Score**: 9
- **Reasoning**: This event is highly suitable for trading due to its weekly cyclicality and the ability to automate data retrieval. The clear and well-defined resolution criteria make it an attractive option for quantitative analysis.

Technical Note: To automate data retrieval, one can use web scraping techniques (e.g., BeautifulSoup, Scrapy) to extract the ranking information from top10.netflix.com. A script can be set up to run at the specified update time (Tuesdays, 3:00 PM ET) to fetch the latest rankings and determine the #2 global Netflix show.