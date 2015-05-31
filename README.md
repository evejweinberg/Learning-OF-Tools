# Using Add-ons from the ofxAddons library
http://www.ofxaddons.com/

## INSTALL ADDONS

STEP 1: INSTALL OFPLUGIN - This makes it easy to add all the addons you want

* 1) install OFPlugin: https://github.com/admsyn/OFPlugin (restart XCode affter install)
  Video Turorial: https://vimeo.com/79061998


STEP 2: CHOOSE AN ADDON, ADD IT TO YOUR OF_FOLDER, and PROJECT

* 1) Find the addon you want from http://www.ofxaddons.com/categories
* 2-option1) Drag the downloaded folder into your "of_v0.8.4_osx_release / ofXAddons" folder
  Gif above in github
* 2-option2) Use terminal and clone the addon to your "of_v0.8.4_osx_release / ofXAddons" folder
* 3) In Xcode (my IDE of choice) Open OF dropdown in the top toolbar, select your new addon. Watch it populate in the addons folder on the left. Notice how it also adds them to the "Build Phase" "Compile Sources" list
* 4) Add the header file to the #include list in the main.cpp of your project:  <#include "ofxNameofAddon.h">

STEP 3: RUN THE EXAMPLES

* 1) If you cloned the addons folder (Step2 option2) you can find an examples folder in the "of_v0.8.4_osx_release / ofXAddons/your specific addon / examples". Move that folder to "of_v0.8.4_osx_release/examples/addons"
* 2) Open the example xcode project (or whatever IDE you have); add the Add-on to the project, and run it.
* 

## WRITING ADDONS

- Always include a thumbnail and ReadMe
- 



