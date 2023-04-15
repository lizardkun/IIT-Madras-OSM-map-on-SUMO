## Installing SUMO
https://sumo.dlr.de/docs/Installing/index.html 

## Running sumo
```
cd /usr/share/sumo/bin
```
```
./netedit 
```
Create a network using netedit.
To launch it on the sumo GUI, press Ctrl-T

## There are four types of files required for running a SUMO simulation
1. .osm.xml file : Downloaded gps coordinates for OpenStreetMaps for a bounding box
2. .net.xml file : Converted osm file to a type NetEdit can use
3. .rou.xml file : Contains routes and vehicles added to the simulation
4. .sumocfg file : loads the sumo simulation from the .net and .rou files
