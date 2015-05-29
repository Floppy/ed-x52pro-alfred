# ed-x52pro-alfred

An [Alfred 2](http://www.alfredapp.com/) workflow for configuring the lights on 
a Saitek X52 Pro, and launching Elite: Dangerous.

## Installation

Download [here](http://floppy.org.uk/ed-x52pro-alfred/Elite with X52 Pro.alfredworkflow), and double click the 
downloaded file to load into Alfred.

## Usage

There are two commands:

`elite`: Turns on all the lights, and launches Elite: Dangerous.

`x52off`: Once you're back in reality, turn off the lights.

## Configuration

To change the light config, go into the workflow editor in Alfred preferences, 
open up the Elite workflow, and configure the bash script attached to the `elite`
command. You can set the colour of each LED to either `red`, `green` or `amber`,
and edit the text on the throttle display however you like.

For more information see the [HotasCtrl](https://github.com/webbasan/HotasCtrl) README.

## Credits

This is just a simple wrapper around the excellent [HotasCtrl](https://github.com/webbasan/HotasCtrl)
program by [webbasan](https://github.com/webbasan), which was in turn based on code by Antony T. Curtis.

The HotasCtrl executable is included in the workflow, so you don't need to download it separately.