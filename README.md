# AndroidMapsExample
Android Maps to track current location


It will first ask you for the Location permission (which is mandatory). 
After the location permission is granted to the app, it will ask for "GPS", as GPS ensures accuracy.

When both the above are enabled, it will fetch the latest location using #FusedLocationProviderClient and plot it on the Map as a marker.
