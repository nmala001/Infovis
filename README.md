# Movie Insights of IMDB

This project was done as a part of course to visualize previous 25 years of IMDB data for Information Visualization course.

**Following is the link explaining the features of the project** - [Video](https://www.youtube.com/watch?v=KR-PofeezYI&feature=youtu.be)

**Click On the following link for** - [LiveDemo](http://www.cs.odu.edu/~nmalapati/Infovis/bubble_logic.html)


## Abstract

we present the visualization and analysis of the movies that have the total user votes more than 25,000. The data set for the movies are collected from the IMDB website by running the python script. A total of 22,000 movies are visualized and an analysis is made on the results obtained. Simple interactive system is developed for the user to make analysis between various movies. The statistics for different movie attributes are obtained and visualization of data is performed. Major insights are discussed.


## Data Collection:

the dataset is obtained by running the python script called beautiful soup which is an efficient way to crawl the data from any website. Besides, the dataset is refined enough, where potential duplicates are removed and a structured and cleaner data is used for the visualization purposes


## DATA SET PREPARATION

### Data Extraction:

The data has been extracted from the website http://www.imdb.com by running the python script. The library in python used for this purpose is called ‘beautiful soup’. The method adopted to extract the data from the subjected website is called as data crawling.

### Data Refining:

The data thus obtained from the above process (Data crawling) may have many redundancies and dirty data which may lead to faulty data visualization at times. Hence, the data set has to undergo a process of refining in order to find possible discrepancies in the data and also potential duplicates to avoid the redundancies. 

### Data Analysis:

The raw data thus obtained is converted into JSON format using the online JSON converter. The dataset consists of the movies between 1915 and 2017. All the anomalies in the data have been excluded. It should be noted that, only the movies which have received the user votes greater than 25000 votes have been collected. 

## Plots used to visualize data

This is a main view as most of the users consider genre as an important criteria to decide whether to watch it or not. Here we plot the Bubble chart for different genres based on the country filter provided at the top of the home page. All the data is in the file names “data.json” file. 

![Bubble Chart](https://raw.githubusercontent.com/username/projectname/branch/path/to/img.png)

