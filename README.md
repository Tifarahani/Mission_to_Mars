##  Mission_to_Mars
### Overview
---
The mission to Mars project enable us to use our knowlwdge of web scrapping extract information from the NASA Science Mars Exploration website using Chrome Developer tools to identify HTML components, Beautiful Soup/Splinter to automate a web browser and perform the scrape, MongoDB to store the data, and finally Flask to create a web application to display the data. Through the process, the goal was to develop an appt to scrape the following information about the planet Mars:

* Latest News
* Featured Image
* Facts about the planet
* Images of the hemispheres
---
### Resources
* Jupyter Notebook
* Python
* MongoDb
---

###  Deliverable 1: 
* Scrape Full-Resolution Mars Hemisphere Images and Titles

<p align="center">  
<img src="https://github.com/Tifarahani/Mission_to_Mars/blob/main/img/D1.1.png">
</p>
<p align="center">  
<i>Figure 1:Use browser to visit the URL </i>
</p>
<p align="center">  
<img src="https://github.com/Tifarahani/Mission_to_Mars/blob/main/img/D1.2.3.png">
</p>
<p align="center">  
<i>Figure 2: Creating list and retrieve the image urls and titles for each hemisphere </i>
</p>
<p align="center">  
<img src="https://github.com/Tifarahani/Mission_to_Mars/blob/main/img/D1.4..png">
</p>
<p align="center">  
<i>Figure 3:Print the list that holds the dictionary of each image url and title and quiting browser </i>
</p>

### Deliverable 2:
* Update the Web App with Mars Hemisphere Images and Titles
Using the database in Mongo, we create a Flask app to connect to the information and create our app routes. These routes help to display the information on the home page and will perform the scraping of new data using the codes that we wrote in the Python script.



Next, we integrate Mongo into the web app so that the data stored is updated every time the script, "Scraping.py" is run.
### Deliverable 3: 
* Add Bootstrap 3 Components
