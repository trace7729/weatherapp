# weatherapp
This app uses the free OpenWeatherMap.org REST web services to obtain a specified city’s 16-day weather forecast.

This app consists of three classes:<br/>
Class **Weather** represents one day’s weather data as one object. Class MainActivity will convert the JSON weather data into an ArrayList<Weather>.<br/>
Class **WeatherArrayAdapter** defines a custom ArrayAdapter subclass for binding the ArrayList<Weather> to the MainActivity’s ListView. ListView items are indexed from 0 and each ListView item’s nested views are populated with data from the Weather object at the same index in the ArrayList<Weather>.<br/>
Class **MainActivity** defines the app’s user interface, the logic for implementing method RobotCallback, and the logic for interacting with the OpenWeatherMap.org daily forecast web service.<br/>
Key in the name of City
![hippo](https://media3.giphy.com/media/aUovxH8Vf9qDu/giphy.gif)
*Deitel, Pau J., and Harvey M. Deitel. Android, How to Program. Boston: Pearson, 2017. p.270-300
