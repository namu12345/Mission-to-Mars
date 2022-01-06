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

In the result section I can mention by saying that after the scraping has been completed, the web app contains all the information from this module and the full-resolution images and titles for the four hemisphere images. The **[scrapping.py](https://github.com/namu12345/Mission-to-Mars/blob/main/Mars_Scraping/scraping.py)** file contains code that retrieves the full-resolution image URL and title for each hemisphere image. **The Mongo database** is also updated to contain the full-resolution image URL and title for each hemisphere image. The **[index.html](https://github.com/namu12345/Mission-to-Mars/blob/main/Mars_Scraping/templates/index.html)** file **contains that code** which will display the full-resolution image URL and title for each hemisphere image. And so in all by running **[app.py](https://github.com/namu12345/Mission-to-Mars/blob/main/Mars_Scraping/app.py)** file we can see following web app :

![image](https://user-images.githubusercontent.com/92283185/148243677-e6ed0714-f90d-41ab-9863-ea4ea3c41941.png)
![image](https://user-images.githubusercontent.com/92283185/148243874-fa2ba7cc-fcbc-49c5-b72a-2c7399eb66c6.png)

In Deliverable 3 it required us to check if webpage is mobile responsive which is as shown below :

![image](https://user-images.githubusercontent.com/92283185/148322423-e1629bf1-1fbf-4c4a-a37b-5314a091d632.png)

I also tried to manage to **use Bootstrap components** by adding class **thumbnail** and class **col-md-3** to mars hemisphere images which gave me the images in horizontal : 
![image](https://user-images.githubusercontent.com/92283185/148324706-daecef96-fadf-4790-b9ed-94b0d84a8bf3.png)

Also I tried to style **Scrape New Data button** by using form style of Bootstrap:
![image](https://user-images.githubusercontent.com/92283185/148324917-85f4e1d2-6bd1-4634-9c9e-09fec0d27f85.png)

Further I changed the Mars Facts table class to **table-dark**  which gave clean look to my **Mars Facts table**

![image](https://user-images.githubusercontent.com/92283185/148324965-d5f150f1-1521-48fb-b9e8-d02359b02bc8.png)


