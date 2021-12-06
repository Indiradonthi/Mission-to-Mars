# Mission-to-Mars

Mission to Mars was a project to scrape data about Mars from the websites below using Python and MongoDB and to use Flask, HTML, and CSS to display the latest scraped news articles, facts, and images on one customized website.

The links below were scraped to pull the data for the website:

News: https://mars.nasa.gov/news/?page=0&per_page=40&order=publish_date+desc%2Ccreated_at+desc&search=&category=19%2C165%2C184%2C204&blank_scope=Latest

Mars Facts: https://space-facts.com/mars/

Weather: https://space-facts.com/mars/

Hemispheres: https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars

# Resources

- Data Source: Mission_to_Mars.ipynb, app.py, scraping.py and index.html
- Data Tools: Jupyter Notebook, Python and MongoDB
- Software: MongoDB, Python 3.8.3, Visual Studio Code 1.50.0, Flask Version 1.0.2


# Results

The website was created through the index.html file to run app.py and scraping.py which scraped through all the websites above to retrieve the information. The Mission to Mars Website shows the latest Mars news article title and subtitle, the latest featured Mars image, Mars Facts, and images of Mars' Hemispheres. There is also a button available to scrape new data. The website was customized using Bootstrap.
