# flightgear-mod


*Random Collection of Mods for FlightGear Flight Simulator*

This repo contains tweaks to a few existing FlightGear components as well as a few additions. Feel free to use them and to post any tweaks of your own as well.

## Scenario

`Virtual Wingman`: Wingmen fan out from your main aircraft's position and follow your every move.

  1. Copy `AI/virtual_wingman_scenario.xml` to your FlightGear AI folder and swap the `model-path` tag to your preferred wingman aircraft
  1. Copy `AI/virtual_wingman_model.xml` to the chosen aircraft's `Models` folder and swap the `PropertyList` tag for this aircraft
  1. See [here](https://github.com/the4thchild/flightgear-mod/blob/master/AI/virtual_wingman_scenario.xml) for more detailed instructions

## Aircraft

* Virtual Wingman
  * Model for a wingman that follows engine speed, gear position, and flight path of the main simulator aircraft
  * Currently tested with PC-9M and F-16 as wingmen
  * See "Scenarios" above for more info
* Saab JAS39 Gripen
  * Based on the [FGUK model](http://www.fgukmedia.co.uk/index.php/hangar/viewdownload/8-military-jets/75-saab-jas39-gripen), GPL license
  * Yasim flight model adjusted to increase flight stability, particularly at low speeds, but not much else modified yet

## Input

* Logitech Attack 3 joystick
	* Based on the configuration included in FlightGear
	* Added view, rudder, and flap controls, including modifier keys for more controls
	* See [here](https://github.com/the4thchild/flightgear-mod/blob/master/Input/Joysticks/Logitech/attack-3.xml) for button setup