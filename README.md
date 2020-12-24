# weatherapp
This app uses the free OpenWeatherMap.org REST web services to obtain a specified city’s 16-day weather forecast.

This app consists of three classes:<br/>
Class **Weather** represents one day’s weather data as one object. Class MainActivity will convert the JSON weather data into an ArrayList<Weather>.<br/>
Class **WeatherArrayAdapter** defines a custom ArrayAdapter subclass for binding the ArrayList<Weather> to the MainActivity’s ListView. ListView items are indexed from 0 and each ListView item’s nested views are populated with data from the Weather object at the same index in the ArrayList<Weather>.<br/>
Class **MainActivity** defines the app’s user interface, the logic for implementing method RobotCallback, and the logic for interacting with the OpenWeatherMap.org daily forecast web service.<br/>
  <div style="width:100%;height:0;padding-bottom:56%;position:relative;"><iframe src="https://giphy.com/embed/H5xCSvcx6Hi1m7M5JO" width="100%" height="100%" style="position:absolute" frameBorder="0" class="giphy-embed" allowFullScreen></iframe></div><p><a href="https://giphy.com/gifs/H5xCSvcx6Hi1m7M5JO">via GIPHY</a></p>
Key in the name of City![Image M1](<iframe src="https://giphy.com/embed/H5xCSvcx6Hi1m7M5JO" width="480" height="270" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/H5xCSvcx6Hi1m7M5JO">via GIPHY</a></p>)
*Deitel, Pau J., and Harvey M. Deitel. Android, How to Program. Boston: Pearson, 2017. p.270-300
