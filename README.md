This project is a web scraper built using Python, Selenium, and BeautifulSoup to extract product details from Amazon Turkey (amazon.com.tr). 
It scrapes product descriptions, prices, ratings, review counts, technical specifications from the search results and individual product pages. The results are saved to a CSV file.


Customization:

Call the main() function with the desired search term to scrape results for that product.
  main('laptop')  # Replace 'laptop' with any search term

Adjust the page range in the main() function:
  for page in range(1, 5):  # Change '5' to the number of pages you want to scrape / page count for the search term