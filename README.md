Solar Energy Sentiment Analyzer

Installation

1.  Clone this repo ( git clone ... )
2.  cd sentiment_analyzer
3.  edit docker-compose.yml and add the OPEN_AI_KEY
4.  enter "docker-compose pull"
5.  enter "docker-compose up"
6.  navigate to "http://localhost:3000" in your browser

To add urls from project
1.  Click on "Bulk Upload" and choose "test-urls.xlsx" from this repo
2.  Import urls
3.  Click on "Analyze All"

To stop the application
1.  docker-compose down
