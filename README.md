Follow these steps to get the web app set up locally:

```
git clone https://github.com/beshup/PredictCovid.git
```

```
cd into the project directory
```

```
node app.js
```

# Welcome to COVID My Tweets! 

A platform for analyzing and visualizing the sentiment data from tweets based on geographical area.

## Homepage
On the homepage, you may SEARCH for a specific place, it could be a state, province, city, address etc. 
When you are satisfied with your search, press ENTER to select the appropriate heading. (Please do not directly click on the 
pop-up, we can't support this functionality yet).

## NLP Analysis
After navigating to your desired search in the suggestions and pressing ENTER. A button will appear called "GET DATA".
Upon Selecting this button you can scroll down on the page and view the NLP analysis performed on tweets from a variety of
COVID-based keywords produced about that region. These tweets include the terms "COVID, #socialdistancing" etc.

The "Score" field is the "average overall sentiment" of all tweets about the geographic area which you search for. 
The "Subjectivity" field is how speculative the tweets were. I.e. how much we felt their statements were based in fact,
based on NLP analysis.

The remaining fields give percentage breakdowns of how many of the tweets received were positive, negative or neutral.

## Second Page
To navigate to the second page click "DATA HEATMAP BY PROVINCE". 
Here at the TOP is a button that says Update Database. This button allows us to manually update our database (which takes about 30 mins, completely recalculating the sentiments based on the latest tweets for each state/province in North America". 
Otherwise, the database is automatically updated daily.

Within this map, you may HOVER over over top of each province/state to view the "Average Overall Sentiment" for that region. The data is 
also presented in an interactive heat map, where you may click on each desired region to zoom in. This makes for an interactive map experience. 

We hope you enjoyed looking around our project!
