# Hygiene-App
An iOS app I developed to display hygiene ratings for restaurants using JSON for the users location within a certain radius.

Installing

Click on 'Clone or download'===>'Open with Xcode'. Save the file and clone the application.
Once the application has loaded onto Xcode, click on 'No Scheme'===>'Manage Schemes...' which is located to the right of the STOP button at the top.
A window will appear, click on 'Autocreate Schemes Now' and then close the window.

Building

To build and run, choose what sort of iPhone simulator you would like to use and Xcode should build and compile the application onto the simulator.
If the application does not load, click the home button on the iPhone simulator and change privacy settings to allow access to the users location. After altering these settings, STOP and RUN the application again.

How it works

Whilst on the simulator you will need to use a custom location which can be located on the toolbar. Click on 'Debug'===>'Location'===>'Custom Location...'. I have given some Latitude and Longitude coordinates below for testing purposes.
The First View Controller is in a table view, where each cell has the business name and postcode with an image displaying their food hygiene rating. On the navigation bar starting from the left, there is a bar button which refreshes the page to show restaurants within a 50 metre radius of the users location. In the middle is a segmented control where you can type the name or postcode in the search bar to find restaurants, and request by clicking on the Search button on the right.
The Second View Controller can be found by selecting one of the cells which displays more information about the restaurant, and a map view which you can click on and get directions to the venue via Apple Maps.
I have created a Tab Bar Controller which will take the user to a map.
The Final View Controller is a map view and for testing purposes I have added a button which allows the user to locate their position (this is useful if you change the custom locations). At the top left, a bar button is used to show restaurants in the surrounding areas of the users location.
The Main.storyboard shows the layout of the Tab Bar Controller, Navigation Controller and the three View Controllers.

Testing

#1

Latitude- 51.5074

Longitude- 0.1278

#2

Latitude- 53.480759

Longitude- -2.242631

#3

Latitude- 54.978252

Longitude- -1.617780

#4

Latitude- 50.719166

Longitude- -1.880769

#5

Latitude- 53.408371

Longitude- -2.991573

