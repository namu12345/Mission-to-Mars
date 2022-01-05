# Mission-to-Mars
![image](https://user-images.githubusercontent.com/92283185/147867528-e5916acd-1abc-4c6d-ab64-9b30ca604c15.png)

## Overview 
The mission with this project was to learn web scraping methods to extract information from the [NASA Science Mars Exploration](https://mars.nasa.gov/news/?page=0&per_page=40&order=publish_date+desc%2Ccreated_at+desc&search=&category=19%2C165%2C184%2C204&blank_scope=Latest) website using Chrome Developer tools to identify HTML components, Beautiful Soup/Splinter to automate a web browser and perform the scrape, MongoDB to store the data, and finally Flask to create a web application to display the data. I used all this tools and imported the required libraries in [Mission to Mars.ipynb](https://github.com/namu12345/Mission-to-Mars/blob/main/Mars_Scraping/Mission_to_Mars_Challenge.ipynb). Through the process, the goal was to develop an app to scrape the following information about the planet Mars:

- Latest News
- Featured Image
- Facts about the planet
- Images of the hemispheres

## Resources 
### Data Sources:
- [Mars News](https://redplanetscience.com/)
- [Featured Images](https://spaceimages-mars.com/)
- [Mars Facts](https://galaxyfacts-mars.com/)
- [Mars Hemisphere](https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars)

### Environment:
- Python 3.7

### Dependencies:
- Beautiful Soup and Splinter

### Languages:
- HTML, Bootstrap 3 and Python

### Software:
- Jupyter Notebook, VS Code, MongoDB, Flask and Chrome

## Final Results:
As mentioned earlier the mission of this project was to scrape data using related tools which will automate the web browsing which I did in my [scrapping.py](https://github.com/namu12345/Mission-to-Mars/blob/main/Mars_Scraping/scraping.py). So, after the scraping has been completed, I did updated the **Mongo Database** that contains the information about full-resolution images and titles for the four hemisphere images. All this we can see in the following url which I initiated from my [app.py](https://github.com/namu12345/Mission-to-Mars/blob/main/Mars_Scraping/app.py) and I also styled my page using [index.html](https://github.com/namu12345/Mission-to-Mars/blob/main/Mars_Scraping/templates/index.html)


![image](https://user-images.githubusercontent.com/92283185/148243677-e6ed0714-f90d-41ab-9863-ea4ea3c41941.png)
![image](https://user-images.githubusercontent.com/92283185/148243874-fa2ba7cc-fcbc-49c5-b72a-2c7399eb66c6.png)

