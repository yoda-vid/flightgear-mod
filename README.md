# flightgear-mod


*Random Collection of Mods for FlightGear Flight Simulator*

This repo contains tweaks to a few existing FlightGear components as well as a few additions. Feel free to use them and to post any tweaks of your own as well.

## Aircraft

* PC-9M Wingman
  * Virtual wingman that follows engine speed, gear position, and flight path of the main simulator aircraft
  * Copy it to the `Aircraft/PC-9M/Models` folder to use with the `Virtual Wingman` scenario
* Saab JAS39 Gripen
  * Based on the [FGUK model](http://www.fgukmedia.co.uk/index.php/hangar/viewdownload/8-military-jets/75-saab-jas39-gripen), GPL license
  * Yasim flight model adjusted to increase flight stability, particularly at low speeds

## Scenario

* `Virtual Wingman`: Wingmen fan out from your main aircraft's position and follow your every move. Currently designed for PC-9M and working to generalize for other aircraft.

## Input

* Logitech Attack 3 joystick
	* Based on the configuration included in FlightGear
	* Added view, rudder, and flap controls, including modifier keys for more controls
	* See [here](https://github.com/the4thchild/flightgear-mod/blob/master/Input/Joysticks/Logitech/attack-3.xml) for button setup