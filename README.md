# Project-ITT-Geolocation-Python

This is very simple. You can try this one

first, you need to install the geocoder module

pip install geocoder
Then you can try this one

import geocoder
myloc = geocoder.ip('me')
print(myloc.latlng)
