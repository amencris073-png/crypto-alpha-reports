## Analysis: Will Moderna (MRNA) beat quarterly earnings?

- **Category**: Monitoring
- **Cyclicality**: This event exhibits a quarterly pattern, as earnings reports are typically released on a quarterly basis. However, the exact date of the earnings release may vary, and the event is not recurring daily or weekly. Therefore, the cyclicality is relatively low.
- **Automation**: The outcome data can be automatically retrieved via public APIs or static pages, such as SeekingAlpha or the company's official earnings documents. This is because the resolution source is clearly defined, and the data is publicly available.
- **Suitability Score**: 7/10
- **Reasoning**: This event is suitable for trading, but its cyclicality is relatively low due to the quarterly pattern of earnings releases. However, the automation of outcome data retrieval is possible, making it a monitoring-type event.

Technical Note: To automate this event, one can use web scraping techniques or APIs to retrieve the GAAP EPS figure from SeekingAlpha or the company's official earnings documents. The script can be set to run at a specific time interval (e.g., every hour) to check for updates and resolve the event accordingly. Additionally, the script can be designed to handle exceptions, such as the company not releasing earnings within 45 calendar days of the estimated earnings date, and resolve the event to "No" in such cases.