# Hygiene-App
An iOS app I made to display hyigene ratings for restaurants from the users location within a certain radius.

Installing

Click on 'Clone or download'===>'Open with Xcode'. Save the file wherever you want and clone the application.
Once the application has loaded onto Xcode, click on 'No Scheme'===>'Manage Schemes...' which is located to the right of the STOP button at the top.
A window will appear, click on 'Autocreate Schemes Now' then you can close the window.

Building

To build and run, choose what sort of simulator you want to use and RUN the application. Once Xcode has built and compiled the application onto the simulator, if the application doesn't load, click the home button on the iPhone simulator and a privacy settings to allow access to the users location will appear and 'Allow' access. STOP and RUN the application again and everything will work.

How it works

Whilst on the simulator you will need to use a custom location, this can be located on the toolbar, click on 'Debug'===>'Location'===>'Custom Location...'. I have given some Latitude and Longitude coordinates below for testing purposes.
The First View Controller is in a Table view, each cell has the business name and postcode with an image displaying their food hygiene rating. On the navigation bar starting from the left, there is a bar button which refreshes the page to show restaurants within a 50 metre radius of the users location. In the middle is a segmented control where you can type the name or postcode in the search bar to find restaurants and search by clicking on the Search bar button on the right.
The Second View Controller can be found by clicking onto one of the cells which displays more information about the restaurant and a map view in which you can click on and get directions to the venue through Apple Maps.
There is a tab bar at the bottom of the application which will take the user to a map.
The final View Controller is a map view and for testing purposes I added a button which allows the user to locate their position, (this is useful if you change the custom locations). At the top right, a bar button is used to show restaurants in the surrounding areas of the users location.
The Main.storyboard shows the layout of the Tab Bar Controller, Navigation Controller and the three View Controllers.
