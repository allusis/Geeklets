My Geeklets
========
![picture](https://raw.github.com/allusis/geeklets/master/Screenshot.png)    
    


[![picture target](https://dl.dropboxusercontent.com/u/1621719/Demos/Github/Geeklets/Screenshot_laptop_sm.jpg)](https://raw.github.com/allusis/geeklets/master/Screenshot_laptop.png blank)

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
* To find out what your local URL is go to [http://weather.yahoo.com](http://weather.yahoo.com/) and type in your zip code. Use the URL in your address bar after your search to update your geeklet. 
* In order to get the weather icon to work you will have to change the path to your local icon folder. Choose either /weather/black or /weather/white folders depending on which color icons you'd like to use. 
* The image path should look something like this in the Geeklets image URL field: 


        file://PATH/TO/FOLDER/Geeklets/Weather/White/ 



