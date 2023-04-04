
# EbayProductDataScraper

This workflow takes a product name as input, scans eBay for the top 25 products sold with that name, and creates a spreadsheet sorted by price with additional details. The workflow consists of the following steps: 1. Obtain the eBay App ID/API Key. 2. Use the eBay Finding API to search for the top 25 sold products matching the given product name. 3. Parse the response and extract relevant product details: title, price, link, and image. 4. Sort the products by price in ascending order. 5. Create a spreadsheet (.xlsx format) with the columns: Title, Price, Link, and Image, containing the extracted product details. 6. Save the spreadsheet file to the local file system.
## Initial generation prompt
a workflow that takes a product name, scans eBay for the top 25 products sold with that name, and creates a spreadsheet sorted by price with additional details.

## Authors: 
- yWorkflows
- Johnathan#2005
        