## Analysis: What will be the top global Netflix movie this week?

- **Category**: Quantitative
- **Cyclicality**: High - The event exhibits a weekly pattern, as Netflix updates its global Top 10 TV movies list every Tuesday, reflecting viewership from the previous week (Monday to Sunday).
- **Automation**: Yes - The outcome data can be automatically retrieved via a static page (top10.netflix.com) or potentially via a public API if available.
- **Suitability Score**: 9
- **Reasoning**: This event meets both criteria, with a clear weekly pattern and easily accessible data, making it highly suitable for trading.

Technical Note: To automate this, one could use a web scraping tool (e.g., BeautifulSoup, Scrapy) to extract the top movie from the Netflix Top 10 page on Tuesdays after 3:00 PM ET. Alternatively, if a public API is available, a simple API call could retrieve the necessary data. A script could be set up to run weekly, capturing the new top movie and updating the market accordingly.