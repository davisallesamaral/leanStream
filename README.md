# leanStream
# LeanStreamTask
TASK:

Create a basic News website based on Laravel 5.8 that will have the following sections:

    •    News from Toronto
    ⁃    Grab the 10 latest news from an API via a cron job, every 10 minutes
    ⁃    By using database migrations, save the results to a MySQL database (if they aren't in there yet)
    ⁃    On page load, load the news from the database, latest first
    ⁃    An example of source: https://newsapi.org/


    •    Weather report for Toronto, Montreal, Vancouver and Edmonton
    ⁃    After the page load, make an AJAX call:
    ⁃    if the weather info is cached locally in Laravel, show it from there
    ⁃    otherwise grab the weather info for these cities and cache them locally for 5 minutes
    ⁃    the API calls would be preferably parallel to speed up loading
    ⁃    An example of source: https://openweathermap.org/api


    •    Exchange rate information
    ⁃    Show the exchange rate between CAD and USD and vice versa
    ⁃    An example of source: https://www.alphavantage.co/documentation/#currency-exchange

Use Bootstrap for creating a basic layout.

Add a search box to the news section which has autocomplete, should search for matches in the news titles and content.
