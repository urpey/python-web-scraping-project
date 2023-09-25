# python-web-scraping-project
In this analysis, I scraped Amazon data for vacuum cleaners, analyzing prices, discounts, and ratings, and classifying the vacuums into handheld, cordless, and robot types. The goal was to identify the best deals based on the price, discount, and user reviews.

First, I used Python and Beautiful Soup to scrape key data from Amazon - product titles, ratings, and current and original prices. For the search criteria, I used 'vacuum cleaner' and 'today's deal' for search keywords. Then I used pandas to process the product data, calculated the discount rate, and classified each vacuum as handheld, cordless, or robot based on keywords in the title.

Next, I plotted price versus rating to get a visual sense of the tradeoff between low price and high rating. I highlighted the vacuums with the lowest price, highest rating, and highest discount rate by annotating them on the plot.

 I create a weighting that balances three factors:
- Price: Favors lower prices 
- Discounts Rate: Favors higher discounts %
- Ratings: Favors higher customer ratings

According to the weighted score, I plot several plots to show the best deal for all vacuum cleaners and the best deal for different types of products.
