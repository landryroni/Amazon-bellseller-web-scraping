# Amazon-bellseller-web-scraping
web scraping amazon best seller with Using Python,  Requests and BeautifulSoup.

Amazon.com is an American multinational technology company specialized in e-commerce, cloud computing, artificial intelligent. The platform is among the best in the industry, where many variety of items can be purchase.

Amazon has listed best sellers in alphabetic order that could be found in Amazon Best Sellers. The page provides a list of items categories regrouped in department(about 40 variety). In this project, we are going to retrieve amazon best seller items in a variety of categories using web scraping. To achieve that we will use Python libraries resquests and BeautifulSoup to fetch, parse and extract the information we need from the web page.

Here is an outline of the steps we will follow:

- Install and import libraries
- Download and Parse the Bestseller HTML page source code using request and Beautifulsoup to get item categories topics URL.
- Repeat step 2 for each item topic obtained using the corresponding URL
- Extract information from each page
- Combine the extracted information Extract information from each page's data in a Python Dictionaries
- Save the information data to CSV file Using Pandas library

By the end of the project, we’ll create a CSV file in the following format:

Topic,Topic_url,Item_description,Rating out of 5,Minimum_price,Maximum_price,Review,Item Url

Amazon Devices & Accessories,https://www.amazon.com/Best-Sellers/zgbs/amazon-devices/ref=zg_bs_nav_0/131-6756172-7735956,Fire TV Stick 4K streaming device with Alexa Voice Remote | Dolby Vision | 2018 release,4.7,39.9,0.0,615699,"https://images-na.ssl-images-amazon.com/images/I/51CgKGfMelL._AC_UL200_SR200,200_.jpg"
Amazon Devices & Accessories,https://www.amazon.com/Best-Sellers/zgbs/amazon-devices/ref=zg_bs_nav_0/131-6756172-7735956,Fire TV Stick (3rd Gen) with Alexa Voice Remote (includes TV controls) | HD streaming device | 2021 release,4.7,39.9,0.0,1844,"https://images-na.ssl-images-amazon.com/images/I/51KKR5uGn6L._AC_UL200_SR200,200_.jpg"
Amazon Devices & Accessories,https://www.amazon.com/Best-Sellers/zgbs/amazon-devices/ref=zg_bs_nav_0/131-6756172-7735956,"Amazon Smart Plug, works with Alexa – A Certified for Humans Device",4.7,24.9,0.0,425090,"https://images-na.ssl-images-amazon.com/images/I/41uF7hO8FtL._AC_UL200_SR200,200_.jpg"
Amazon Devices & Accessories,https://www.amazon.com/Best-Sellers/zgbs/amazon-devices/ref=zg_bs_nav_0/131-6756172-7735956,Fire TV Stick Lite with Alexa Voice Remote Lite (no TV controls) | HD streaming device | 2020 release,4.7,29.9,0.0,151007,"https://images-na.ssl-images-amazon.com/images/I/51Da2Z%2BFTFL._AC_UL200_SR200,200_.jpg"

check out the jupyter notebook here https://jovian.ai/landryroni/amazon-best-seller-web-scraping
