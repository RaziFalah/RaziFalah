***Currently working on***


<h1>(1) Outstageed.com</h1>

![Screenshot from 2023-07-10 01-55-13](https://github.com/RaziFalah/RaziFalah/assets/92949627/850204c7-6223-4e5d-a3b2-597e47b9cab8)

```py

razi@razi:~$ Su -
root@razi:~# Make A-change



```

Email: i@razifalah.com<br>
Phone number: +972-52-3075200<br>
You can also contact me via [Chat](http://razifalah.com/) or [email address](mailto:i@razifalah.com)


<h1>About outstageed</h1>
Outstageed is an open source web-based project that aims to let users upload articles and create their own portfollo. <br>
Outstageed is a free to use web app with no limitations what so ever, as long as you have some morals and a proper internet connection
you can come make a free account. Outstageed can also act as a host for articles you can request to customize your own html, css page, you can even add scripts.

[Subscribe to outstageed news letter](https://razifalah.github.io/Outstageed.com/)


Project is indevelopment by razifalah.com Team


<h1>Screenshots and gifs</h1>

<h3>Basic studio for posting articles</h3>

<img src="https://github.com/RaziFalah/Outstageed.com/blob/main/snaps/studio.gif" alt="Basic studio outstageed">
<p>You will also have the option to customize your own page with html, css and scripts might be possible.</p>

<h3>Friendly sign up proccess</h3>
<img src="https://github.com/RaziFalah/Outstageed.com/assets/92949627/b87934c8-5496-419e-b6cb-0a2525c30db9" alt="friendly sign up proccess outstageed">
<p>After signing up, you will be presented with this page on the first login in order to customize your public profile.</p>


<h3>Feed page</h3>
<img src="https://github.com/RaziFalah/Outstageed.com/assets/92949627/8504f5a0-f76a-4776-9696-1ebc657045de" alt="feed page outstageed">
<p>Please be aware this is a beta feed page for testing and will not be officially released</p>


<h1>Introduction to the smart argiculture house</h1>
<p>This agriculture project is powered by arduino ESP32 micro-controller, this projects aims towards building a smart agriculture house containing a handful amount of sensors in order to achieve a smarter way of monitoring plants. it's equipped with state-of-the-art security measurements and immediate alarms and protective actions.</p>
<br>  

***The following image contains a prototype describing how the system works.***

<br>
<center><image src="https://raw.githubusercontent.com/RaziFalah/agriculture-project/main/digrams/prototype.png"></image></center>
<h1>Features</h1>
<h4>Water supplying:</h4>
Like the name this feature will supply water to the plants in the agri-house, there will be a connected water supply tube to every plant in the system, the water will be supplied depending on many factors like whether the soil is dry or not.<br>As well as weather status, a working API will provide us with information, based on them, the system will supply water. for instance, when the day is rainy the water supplying will be skipped, low humidiy equals more water is needed.
<h4>Humidity monitoring</h4>
The system will counduct a humidity check as frequently as we choose, if the humidity level happens to be abnormal there will be a warning, which can be viewed in the web interface, a sonic warning might be triggred in extreme cases. (Humidity checks will be powered by OpenWeather API).
<h4>Temperature monitoring</h4>
Same as mentioned earlier regarding the humidity monitoring the system will conduct a temperature check automatically, in case of abnormal temperature a warning will pop up on the web interface a sonic alarm might be triggred in cases where immediate action is required. (Temp check are powered by a sensor for indoors accuracy as well as an API mostly used for outdoor temp monitoring).
<h4>Fire and gas alarm</h4>
If a fire or a gas leak was detected by the system, there will be an immediate sonic alarm and also a pop up on the web interface asking for immediate intervention, in extreme cases, the system will initiate a flood protocol which means the water pump will work at high capacity and fans will shut off.
<h4>Web interface</h4>
Responsible for handiling pop-up alarms as well as API manipulations (for testin).
<h4>LCD display system</h4>
Responsible for outputting basic data.
<h4>Artificial lighting system</h4>
Responsible for providing plants with lights if needed, determined using a photoresistor and a time-table, in case of weather changes, the time-table will be overrode or ajusted. <br>
<br><hr>

***Exampe of the code running in the ESP32 based on the API data***

<image src="https://raw.githubusercontent.com/RaziFalah/agriculture-project/main/digrams/esp32_prototype.png">

<h1>Components</h1>
<h4>Needed components</h4>
<p>Most components was already provided at my expense</p>
<ul>
  <li>ESP32 Board</li> <a href="https://www.aliexpress.com/item/1005004879572949.html?spm=a2g0o.order_list.order_list_main.9.5c471802ypflOP">View on aliexpress</a>
  <li>Power supply</li> <a>Not yet decided.</a>
  <li>Moisture sensor</li> <a href="https://www.aliexpress.com/item/1005004961237192.html?spm=a2g0o.order_list.order_list_main.4.5c471802ypflOP">View on aliexpress</a>
  <li>Photoresistor</li> <a href="https://www.aliexpress.com/item/1005005009839541.html?spm=a2g0o.order_list.order_list_main.29.5c471802ypflOP">View on aliexpress</a>
  <li>Gas sensor</li> <a href="https://www.aliexpress.com/item/1005001666186214.html?spm=a2g0o.order_list.order_list_main.24.5c471802ypflOP">View on aliexpress</a>
  <li>Sonic alarm</li> <a href="https://www.aliexpress.com/item/1005003274011049.html?spm=a2g0o.order_list.order_list_main.34.5c471802ypflOP">View on aliexpress</a>
  <li>Water supplier motor (Water pump) </li> <a href="https://www.digikey.co.il/he/products/detail/adafruit-industries-llc/4547/11627730?utm_adgroup=&utm_source=google&utm_medium=cpc&utm_campaign=PMax_Product_High%20Volume%20Products&utm_term=&productid=11627730&gclid=EAIaIQobChMIpsvF8YXIgQMVfJqDBx09aAxGEAQYASABEgJ-jfD_BwE">View on digikey</a>
  <li>Light supplier (LED orange)</li> <a href="https://www.aliexpress.com/item/1005003323707856.html?spm=a2g0o.order_list.order_list_main.50.5c471802ypflOP">View on aliexpress</a>
  <li>Alarm ligh (LED Red)</li> <a href="https://www.aliexpress.com/item/1005003323707856.html?spm=a2g0o.order_list.order_list_main.49.5c471802ypflOP">View on aliexpress</a>
  <li>5mm fans</li> <a href="https://www.aliexpress.com/item/1005003878734109.html?spm=a2g0o.order_list.order_list_main.44.5c471802ypflOP">View on aliexpress</a>
  <li>4*20 LCD Display</li> <a href="https://www.aliexpress.com/item/4000863723154.html?spm=a2g0o.order_list.order_list_main.39.5c471802ypflOP">View on aliexpress</a>
</ul>



<h1>Functions</h1>
<h4>API Connection</h4>
<p>ESP32-WIFI connection code with openweather API using http request</p>
<a href="https://raw.githubusercontent.com/RaziFalah/agriculture-project/main/code/main.cpp">View API http call code & init wifi at the main file here.</a><br>
<a href="https://raw.githubusercontent.com/RaziFalah/agriculture-project/main/tests/API_testing.md">View API http call sandbox test here (Not a real API).</a>
<hr>

***Exampe of the code running in the ESP32 according to the API data with LCD display***<br>
<image src="https://raw.githubusercontent.com/RaziFalah/agriculture-project/main/digrams/esp32_lcd.png"><br>
<a href="https://raw.githubusercontent.com/RaziFalah/agriculture-project/main/code/main_lcd.cpp">View LCD display containing weather and alarm data code here.</a><br>

<hr>


**No need for testing, device is operating successfuly and same as the pervious test**
<br><image src="https://raw.githubusercontent.com/RaziFalah/agriculture-project/main/digrams/lcd_prototype.gif.gif"><br>

<hr>

***Example of the demo alarm system***

<image src="https://raw.githubusercontent.com/RaziFalah/agriculture-project/main/digrams/led_lcd_esp32.gif"><br>

<p>This alarm system is not yet finished and waiting for a speaker alarm and more extra leds to be added.</p>
<a href="https://raw.githubusercontent.com/RaziFalah/agriculture-project/blob/main/video%20log/2023-09-18_14-13-18.mp4">Download video here</a>

<hr>

***example of light supplier***

<image src="https://raw.githubusercontent.com/RaziFalah/agriculture-project/main/digrams/light_supplier.gif"><br>

<p>This light supplier works only in the day, it determines if it should run or not based on Openweather API to get night/day status and also a light sensor.</p>


