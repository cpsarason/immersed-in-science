## The problem

Sea level rise is an oft cited impact of global climate change. It can be hard, however, to 
determine the difference between Hollywood disaster movies and a more accurate representation. (pic)
This difficulty is understandable, as anyone who lives along the coast can attest. Perhaps you have
begun a nice walk down the beach that became a wet and wild adventure when you forgot to pay attention
to the incoming tide. (pic)

Sea level rise is similar -- small changes in the average height of sea level can be difficult to 
visualize until a windstorm combined high tide brings local flooding. Increasingly "sunny flooding" 
is happening in places like Miami Beach (ref) and elsewhere. Just like a walk on the beach, however, 
it is possible to plan for increases in sea level rise if only we could easily motivate decision 
makers and the general public by showing the impact. 

## The App Solution
We envision a smartphone and tablet app that is a cross between Pokémon Go and a mobile tide chart. 
The basic premise is to use your smartphone as a "viewer" of future sea level rise impact, by using 
a simple overlay indicating future water levels. Wondering what your favorite beach might look like 
after a meter of sea level rise? Pull out your smartphone, fire up the app and watch to projection of 
sea level onto your camera view. Want to record what the beach looks like when the 
closest tidal gauge is at a certain height? Snap a picture, add a note and upload to an archive of 
other shoreline pictures taken with the app. Want to compare to other tidal heights? Browse the map and
timeline for other images taken nearby!

### The Data Available
There are lots and lots of tide and current phone applications. Our is different, as the focus is on
using tidal data as 1 of several different factors that control sea surface height (and thus the water's
extent on the shoreline). Tide height, wind speed and direction as well was significant wave height all 
play a part in sea level. Our application will leverage data real time data provided by NOAA's Co-Ops 
tidal gauge data and the National Weather Service (refs). For projections of relative sea level (a function of
both global average sea level and local effects) we will integrate data available from NOAA's Office for
Coastal Management, which already has a GIS data available (https://coast.noaa.gov/slr/). We do *not* 
plan to replicate their tools; our unique contribution will be to use the available GIS data to connect
to our smartphone application for an "augmented reality" presentation á la Pokémon Go.

### The Data and/or Measurements Required
The basic data needed to effectively model sea level rise for a location is provided (with some margin of error)
by the smartphone: GPS location and orientation (compass direction and phone orientation in space). Combined
with some straightforward settings (user height, possible "pin" of location on a map if GPS signal is weak)
it is possible to accurately locate and orient any given image. Displaying a different sea surface height
is then a matter of simple geometry and image projection. The application will offer a "see the level" function 
that allows interactive sliding of sea level (visualized as a horizontal plane that moves up/down). A second
feature will allow for uploading a geo-tagged picture (complete with orientation). Adding photos at various 
locations at known tidal heights and times will help build a database of what the shoreline looks like 
in different conditions, and builds on the kinds of efforts already underway (in, for example, the Washington 
State Sea Grant "King Tides" initiative (http://washington.kingtides.net/)

## The Team
### Christian Sarason (lead)
### Matt Pruis (advisor, science)
### Ian Miller (advisor, science/community)
### Bridget Trosin (advisor, science/community)
### Karl Spang (advisor, VR)
### 
