## GPS Buoy
July 2020 - F.Bernier

The goal was to build a simple gps buoy as a small and quick project.    

The features of the buoy are:
- Get the buoy position from the GPS module
- Create a wifi hotspot to connect a laptop or a smartphone
- Send the position via UDP, with the protocol Mavlink to the laptop or the smartphone    
QGroundControl is used to display the Mavlink message (gps position on a map)
- Save gps position in a csv file on the sd card

Initial buoy architecture:    
![GPS Architecture](/posts/gps_buoy/buoy_architecture.svg)

The GPS used is a uBlox M8N. The processor used is a NanoPi NEO2. The embedded linux is Ubuntu 16.04. The software was implemented in C/C++.    
The buoy case is a waterproof ERMET flight case from Conex.    
![GPS Buoy Inside](/posts/gps_buoy/gps_buoy_1.JPG)

The buoy was tested on the Etang de Cazaux-Sanguinet in July 2020:    
![GPS Buoy Test 1](/posts/gps_buoy/gps_buoy_test_1.JPG)



