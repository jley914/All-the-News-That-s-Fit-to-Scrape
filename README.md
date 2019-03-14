# All-the-News-That-s-Fit-to-Scrape
`All the News That's Fit to Scrape` is an application that lets users scrape news articles from (website) Users can then view and leave comments on saved articles. This app uses Cheerio to scrape news from (website name.com) and stores them in MongoDB using Mongoose.
Please Click on this [link](https://my app.herokuapp.com) to Check the App out.

## Technologies

| Frontend  | Backend |
| ------------- | ------------- |
| HTML | Nodejs |
| CSS (SASS) | Express |
| Javascript (jQuery) | MongoDB (Mongoose)|
| Materialize | Cheerio (Web Scrapper) |
|Handlebars (Templating Engine)|


Deployed on: `Heroku`

## Usage



## Requirements
- Web Browser
- Nodejs
- Mongo DB

## Installation

After installation, open node, navigate to the file and run `npm install`.

To run `All the News That's Scrape` locally, Please Ensure that MongoDB is Running.

- Proceed to `controller/scrapperController.js` and Update the Following Code
```
var MONGODB_URI = process.env.MONGODB_URI || "mongodb://localhost/mongoHeadlines";

mongoose.connect(MONGODB_URI);

```