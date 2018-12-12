# WebPageTest Private instances
===============================

Docker images based on the Official WPT server and Agent images
Traffic shaping MacOS Workaround [not yet supported]



## WPT server
Sets a dummy value for connectivity [lan] in the settings/locations.ini file.


## WPT agent
Docker image with contains a copy of the existing WPT entrypoint script and adds the --shaper none flag.


