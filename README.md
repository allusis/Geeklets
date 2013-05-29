My Geeklets
========
| Desktop | Laptop |
|:--------|:-------|
|<a href="https://raw.github.com/allusis/geeklets/master/Screenshot.png" target="_blank" style="float:left">![picture target](https://dl.dropboxusercontent.com/u/1621719/Demos/Github/Geeklets/Screenshot_sm.jpg)</a>|<a href="https://raw.github.com/allusis/geeklets/master/Screenshot_laptop.jpg" target="_blank" style="float:left">![picture target](https://dl.dropboxusercontent.com/u/1621719/Demos/Github/Geeklets/Screenshot_laptop_sm.jpg)</a>|



Everything should load up all pretty as long as you have [GeekTool 3.0.3](http://itunes.apple.com/us/app/geektool/id456877552?l=fr&ls=1&mt=12) installed and working properly. Chances are these will work with most versions, but I haven't tested. 

## Features
| Name          | Description   |
| :------------ | :------------ |
| Weather       | Displays condition, temperature, and a flat weather icon |
| System Uptime | Displays days, hours:minutes for system uptime |
| Memory Usage  | Displays Free, Inactive, Total Free, Wired, Active, and Total Used RAM |
| Wireless Devices | Displays battery percentage for Bluetooth Keyboard, Mouse, or Trackpad |
| Volumes          | Displays mounted volumes and shows a percentage bar for used space |







## Some things you might want to know:
* The files named *_Label.glet are the labels for each section. "System Uptime", "Memory Usage", "Wireless Devices", and "Volumes".
* The weather geeklets are in the /weather folder.
* In order to make sure you're pulling the right weather, you'll want to edit WeatherText. You can edit the geeklet file before you run it, or edit the script once opened.
* In order to use the conditions for your local area, you'll want to change <code>http://xml.weather.yahoo.com/forecastrss?p=90210&amp;u=c</code> to your zip code. If your zip code is 13041 you should use the following: <code>http://xml.weather.yahoo.com/forecastrss?p=13041&amp;u=c</code>.
* In order to get the weather icon to work you will have to change the path to your local icon folder in WeatherText geeklet. The image path by default looks like: <code>~/PATH/TO/Weather/$wtheme/$n.png</code>. You'll want to change it to reflect the local path to your icons. Assuming <code>/Documents/Geektool/Weather</code> is your local path, you should use the following: <code>~/Documents/GeekTool/Weather/$wtheme/$n.png</code>



