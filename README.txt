CSCE 3420 Internet Programming
FALL 2015
Final Project : Chrome Extension
Isaias Delgado

*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*--*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*
* This extension plots the bus stops at the University of North Texas in order to greately reduce the need to  *
* open the UNT Transportation Website and shuffle through all of the pages to get the the bus stop maps.      *
* In my extension the user's location will be geolocated on the map using the IP address. The user will be      *
* able to toggle the bus routes using a drop-down check box menu and will also be able to see the traffic       *
* conditions, transit options, and bicycle routes around their location in order to find the fastest route           *
* to their desired bus stop.							                         *
*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*--*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*

LANGUAGES USED:
> HTML
> Javascript
> CSS
> Python
> JSON

GOOGLE API's USED:
> Google Maps
> Google Places
> Google Traffic/Bicycle/Transit
> Google Geolocation

HOW TO USE:

Since this extension is not published in the Chrome Web Store, the user will need to have Python installed in
their local computer to get the extension to work. This extension requires Python to give Chrome the permission
to gather the geolocation information needed to plot the user on the map.

1.) Extract the extension zipped folder into your desktop using 7ZIP or WINRAR:
	> Right click the zipped archive and extract the UNTBusMap folder to the desktop

2.) If Python is not already installed, follow this YouTube video instructions to set up the local server for Windows 7:
	> https://www.youtube.com/watch?v=L5t5U0XnSew 

3.) After python is installed on the computer, open the Windows Command Prompt:
	> (START) --> search --> cmd

4.) Next, change directories into the UNTBusMap extension on your computer
	For example:
	> C:\Users\Owner>     cd Desktop\UNTBusMap

5.) Once the user is in the extension directory, type the following into the command prompt to initialize the local server:
	> python -m SimpleHTTPServer

6.) Now upload the extension into Google Chrome:
	> In the search bar, type in: chrome://extensions
	> Check the DEVELOPER MODE checkbox
	> Click [Load unpacked extension]
	> Search for the UNTBusMap extension
	> Click OK

7.) Now click the UNTBusMap icon and click [Choose a Bus Route] to activate the extension

8.) Enjoy!