# GoogleMaps_Coordinates

Function Name:
coordinates(st)

Functionality:
The function coordinates uses the Selenium WebDriver API to open the Google Maps website, search for an address passed as an argument to the function, extract the latitude and longitude coordinates from the website's URL and return them as a string.

Input Parameters:
The function takes a single parameter, st, which represents the address to be searched for on Google Maps.

Output:
The function returns a string representing the latitude and longitude coordinates of the address passed to the function. The string is in the format "latitude,longitude".

Libraries Required:
The function requires the following libraries to be installed and imported:

1. selenium - to automate web browser interaction
2. time - to introduce a delay in the program execution
3. webdriver - to initialize the Chrome browser instance and perform browser actions
4. Keys - to send the 'Enter' key to the search bar to initiate the search


Note:
The Chrome webdriver needs to be downloaded and added to the path before executing the code.
