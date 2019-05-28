# weatherVSlatitude

## We take 500+ random cities and see the impact of latitude on various factors using OpenWeatherMap API

#### Sample run : 500+ Cities selected
![map](https://user-images.githubusercontent.com/46534353/58493208-47cf8200-8127-11e9-9016-15311e6204f8.png)

## Temperature (F) vs. Latitude
### Strong correlation as seen from the below plots. Closer to the latitude sees higher temperatures.

-Scatter plot below shows the rise in temperature as the location in question gets closer to the equator
![Lats_vs_Temps(Tue May 28 08:53:31 2019)](https://user-images.githubusercontent.com/46534353/58493271-69306e00-8127-11e9-80ab-2064da7f47d6.png)

-Binned average temperature plot by latitude shows the same trend more clearly
![Lats_vs_Temps-Binned(Tue May 28 08:53:31 2019)](https://user-images.githubusercontent.com/46534353/58493916-d7296500-8128-11e9-97af-e4c64dbbbd4d.png)

-A quick plot shows how the spread is more visually

<img width="741" alt="Screen Shot 2019-05-28 at 9 24 23 AM" src="https://user-images.githubusercontent.com/46534353/58494693-8adf2480-812a-11e9-836b-b5330a9faa86.png">

## Humidity (%) vs. Latitude
### No real corelation between Humidity vs Latitude

-Humidity depends on additional factors rather than just latitude of the location
![Lats_vs_Humidity(Tue May 28 08:53:31 2019)](https://user-images.githubusercontent.com/46534353/58494800-c7128500-812a-11e9-92b2-644af4b0cebd.png)

-Plotting a heat map shows that Humidity looks to be higher in coastal areas and might need further evaluation
![map-7](https://user-images.githubusercontent.com/46534353/58495773-2a9db200-812d-11e9-9df0-0df0ec335ba1.png)

-Plotting the binned data shows a similar trend
![map-4](https://user-images.githubusercontent.com/46534353/58494990-2ec8d000-812b-11e9-8980-0dac068d5f83.png)

## Cloudiness (%) vs. Latitude
### No real corelation between Cloudiness vs Latitude

-Cloudiness depends on additional factors rather than just latitude of the location
![Lats_vs_Cloudiness(Tue May 28 08:53:31 2019)](https://user-images.githubusercontent.com/46534353/58495258-dcd47a00-812b-11e9-86b1-9fe2b16cc236.png)

-Plotting a heat map does not show any real relationship
![map-5](https://user-images.githubusercontent.com/46534353/58495341-1a390780-812c-11e9-8412-a2f4eaadc88d.png)

## Wind Speed (mph) vs. Latitude
### No real corelation between Wind Speed vs Latitude

-Wind Speed depends on additional factors rather than just latitude of the location
![Lats_vs_WindSpeed(Tue May 28 08:53:31 2019)](https://user-images.githubusercontent.com/46534353/58495501-89aef700-812c-11e9-9147-98276dbd52fb.png)

-Plotting a heat map does not show any real relationship
![map-6](https://user-images.githubusercontent.com/46534353/58495597-c4b12a80-812c-11e9-9be6-3dd4dd0dce8d.png)


