# Time
A full-screen digital clock displaying user location.

## Main challenges

* Use CSS Grid and JavaScript to display each digit

  As digits change with time, the space occupied by each digit changes and causes the others to move. In order to prevent this, a Date instance is sliced into individual digits with JavaScript and inserted into HTML. Each digit lays in its own column in the grid with a fixed size. 
  
* Geolocate user

  The user is geolocated with the JavaScript *navigator.geolocation* property. The user is prompted to give access. If no access to geolocation data is given, the process stops and no city is displayed. The freeCodeCamp Weather API is then called with the given coordinates to find the city.
  
* Display full-screen

  The user can toggle full-screen on and off, thanks to JavaScript functions requesting the browser to either enter or exit full-screen mode.

## Coming features

* Ability to customize UI

  The background color, font color and size will be editable by the user at any time with a discrete panel on the side of the screen.
