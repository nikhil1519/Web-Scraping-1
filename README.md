# Web-Scraping-1
Task to Scrape  iPhone 12 link: https://www.amazon.in/Apple-New-iPhone-12-128GB/dp/B08L5TNJHG/
# Approach:
    1. Import required Packages/modules: requests, bs4, txtblob, mysql.connector, html5lib
    2. Get html content from given link
    3. Use parser to parse the html tree (html5lib)
    4. Get link of review page (Here, 100 pages traversed)
    5. Scrape the required text from html tags using find/final method of bs4
    6. Scraped data stored in respective lists (Review Title, Review Text, Colour, Size, Star Rating)
    7. Review text is cleaned during appending to list
    8. Create Database server connection using MySQL connector
    9. Create Database and table using MySQL cursor.execute() method
    10. Store data one by one to Database
    11. Fetch result using MySQL command passed to cursor.execute()
