# news-star

## News Scraper with Mongo DB and Cheerios 

**The fully deployed app can be found at:**<br>
-https://news-star-mongodb.herokuapp.com/

### Program Logic

* Used following packages:

    express<br>
    express-handlebars<br> 
    mongoose<br>
    body-parser<br>
    cheerio<br>
    request<br>
    axios
 

+ Succesfully used mongoDB and the Mongoose npm package to store articles scraped from NPR.org.

+ Used MongoDB and the Mongoose npm package to Store notes for each individule article that users input and display them on a modal.

+ All articles can be deleted from the saved status.

+ Every article will store its own notes and each note can be deleted separately. 

This code should connect mongoose to your remote mongolab database if deployed, but otherwise will connect to the local mongoHeadlines database on your computer

## This app accomplishes the following:

* Whenever a user visits the site, this app will scrape stories from a news outlet (NPM news) and display them for the user. Each scraped article will be saved to the application database. The app Will scrape and display the following information for each article:

    -> Headline - the title of the article<br> 
    -> Summary - a brief summary of the article<br>
    -> URL - the url to the original article

* Users can leave comments on the articles displayed and revisit them later. The comments will be saved to the database as well and associated with their articles.

* Users can delete comments left on articles. All stored comments are visible to every user.

* users can delete the saved articles


