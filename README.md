Tracking system using A9G module. 

This system will help you to view the path and location of your vessel.

Regarding the vessel's motion the hardware will keep pushing API request.  

Through HTTP request encrypted latitude and longitude values will be passed down on web platform. 

Web platform code:https://github.com/Akash-Rayhan/vesselTracker

The web application will show the location on a map. 

Here we use  localhost. Hit the command "ssh -R 80:localhost:8000 ssh.localhost.run" on your pc. This will allow remote clients and this will forward all connections from gateway's port 8000 to internal host port 80. If the gateway has live internet address this will allow anyone to the web server. Make sure your pc is connected to router not any mobile network

If you want to take a look of the project here:https://www.youtube.com/watch?v=aYuR-ZNx-2E
