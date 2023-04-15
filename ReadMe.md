## Installing SUMO
https://sumo.dlr.de/docs/Installing/index.html 

## Running sumo
```
cd /usr/share/sumo/bin
```
```
./netedit 
```
### Create a network using netedit.
![image](https://user-images.githubusercontent.com/94188928/232224148-971ff678-436a-485f-b8db-8b848e47f14c.png)

### To launch it on the sumo GUI, press Ctrl-T
![image](https://user-images.githubusercontent.com/94188928/232224162-5eacd668-1e0d-4dba-b39e-c3cbab8488ce.png)

## There are four types of files required for running a SUMO simulation
1. .osm.xml file : Downloaded gps coordinates for OpenStreetMaps for a bounding box
2. .net.xml file : Converted osm file to a type NetEdit can use
3. .rou.xml file : Contains routes and vehicles added to the simulation
4. .sumocfg file : loads the sumo simulation from the .net and .rou files


https://user-images.githubusercontent.com/94188928/232224170-4e33a541-99de-4975-ae08-094b8c06cfe6.mp4

