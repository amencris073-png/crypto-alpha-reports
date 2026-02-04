## Analysis: What will be the top global Netflix show this week?

- **Category**: Quantitative
- **Cyclicality**: High - The event exhibits a weekly pattern, as Netflix updates its global Top 10 TV shows list every week on Tuesdays, reflecting viewership from the previous week (Monday to Sunday).
- **Automation**: Yes - The outcome data can be automatically retrieved via the public Netflix webpage (top10.netflix.com), which is updated regularly.
- **Suitability Score**: 9
- **Reasoning**: This event is highly suitable for trading due to its predictable weekly pattern and easily accessible outcome data. The only potential issue is the reliance on Netflix updating its webpage on time, but the event description provides a clear resolution rule in case of delays.

Technical Note: To automate data retrieval, a simple web scraper can be set up to fetch the top show from the Netflix webpage (top10.netflix.com) at the scheduled update time. The scraper can be implemented using popular libraries like BeautifulSoup (Python) or Cheerio (JavaScript), and can be run as a scheduled task using tools like cron jobs or cloud-based scheduling services.