# GoogleMaps Timelapse
[![Pylint](https://github.com/stalbrec/gmapstimelapse/actions/workflows/pylint.yml/badge.svg)](https://github.com/stalbrec/gmapstimelapse/actions/workflows/pylint.yml)

### Exporting your GoogleMaps Timeline

Go [here](https://takeout.google.com/takeout/custom/local_actions,location_history,maps,mymaps?dnm=false&continue=https://myaccount.google.com/yourdata/maps&hl=de&utm_source=privacy-advisor-maps) and follow steps in order to create this minimal Google data export including your location tracking data, then download the takeout via your chosen way of delivery.

### Installation

- Install prerequisites for python modules:
  
  - install `geos, cython` 
    
    - MacOS: `brew install geos; brew install cython`

- before installing python packages make sure to set the `GEOS_DIR` env-variable. 
  (Needed for installing `basemap`)
  
  - If installed via homebrew on MacOS:
    
    - `export GEOS_DIR=/opt/homebrew/Cellar/geos/<version>/`




