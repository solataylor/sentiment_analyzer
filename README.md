Solar Energy Sentiment Analyzer

Installation

1.  Install docker desktop
2.  Clone this repo ( git clone https://github.com/solataylor/sentiment_analyzer.git )
3.  cd sentiment_analyzer
4.  edit docker-compose.yml and add the OPENAI_API_KEY
5.  enter "docker-compose pull"
6.  create db folder if doesn't exist ( mkdir db )
7.  copy data file to db folder ( cp production.sqlite3 db/. )

Starting the app
1.  enter "docker-compose up"
2.  navigate to "http://localhost:3000" in your browser

To add urls from project
1.  Click on "Bulk Upload" and choose "test-urls.xlsx" from this repo
2.  Import urls
3.  Click on "Analyze All"

To stop the application
1.  docker-compose down
