# Projects
Code Overview
The first part of this code (web crawling) takes the starting url (direct link of seller page). From there it determines how many pages of listings there are. It then goes through each page, and from each page it collects all product links.

The second part of this code (web scraping) goes through each of product links collected in part 1, and scrapes them for 11 points of data: Artist name, album name, year released, country released, genre, rating, have count, want count, low price, median price, high price
It stores all this data into list variables.

Third part of the code (data visualization) creates a panda data frame using the data collected in part 2. From there, there are multiple charts that it creates to visualize the data.


Why did I pick this website?
This is a website that is in my niche. During covid I picked up selling vinyl records and CDs. Discogs is the #1 website used by record enthusiasts to purchase vinyl records (from people like me who sell them). Only people that are into records probably know about this website, though it does come up if you search google for a specific vinyl record. Despite this, Discogs is an extremely large website and has an equally large database and user base. Currently there are close to 75 million listings on Discogs.

More about the website:
Discogs is both a database and marketplace. It catalogs information for just about every vinyl record that was released including their variants. You can also sell on Discogs. On each release page, there is information about the release as well as listings from everyone that is selling that item on discogs.

Example release page: https://www.discogs.com/release/12833670-Freddie-Gibbs-Freddie

What is the purpose of this web scraper?
The purpose of this webscraper is to allow the user to get insights on any seller on Discogs including themselves and to source records that are doing well in the market. Most physical record stores also sell on Discogs. Therefore, this tool can be used by record store owners to get insight on their own store as well as others AND to source products from other stores as well.
