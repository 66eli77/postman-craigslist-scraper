# postman-craigslist-scraper
Search craigslist and post the result on slack in configurable interval. 

You will need Postman Pro subscription to run the monitor that schedules the Craigslist request and Slack post calls.

## The workflow
1. Send request to Craigslist(a search query).
2. Parse the html response to extract top 5 results.
3. Post to Slack with webhook.
4. Set a Postman monitor to run the collectoin everyday at noon.

\* All are acheived by using Postman collection and monitor services.