Re-Worked-WAI-0.17
==================

Credits: Markk311, Lazyink, TheSzerdi, Falcyn , TAWTonic, EPOCH DEV's


Current Development done by williamjbrown, firefly, fuchs

* Current Version based on 0.16 
* Wicked Mission System  Features (WIP)
* Adds more options to ammo boxes 
* tweaks to missions 
* Added timeouts to missions 
* Fix ammobox despawn in 1.0.3   
* Wicked AI feature list   
* Customizable loadouts for groups 
* Customizable ammo boxes 
* Customizable Static weapon units 
* Customizable Heli patrols 
* Customizable vehicle patrols 
* Customizable helicopter group paradrop 
* Ability to setup custom skill settings 
* Can spawn units in any script in the dayz_server.pbo 
* AI share your info making them more difficult   
* Customizable random vehicles for missions 
* Vehicles save to database only when player gets close 
* Loads easily from AI system
* No need for extra install Map markers refresh so JIP players will have them on map 
* Uses wasteland like missions 
* Missions have a timeout if no player is in the area


**Requirements:**

*Notepad++

*PBO Manager

*Epoch 1.0.4 Server

**Difficulty**

Easy : 5-10 minutes

Some knowledge of Epoch Server & Mission file locations
How to use PBO manager to unpack and pack PBO files

## Installation Instructions

### dayz_server PBO Instructions

Now you just need to allow the connection of the mission system by doing this. 
 
Go to server_monitor.sqf located in the system folder in your server.pbo

* search for allowConnection = true; and add the line shown below 

    
    [] ExecVM "\z\addons\dayz_server\WAI\init.sqf";
    
    allowConnection = true;
    
    
    
Understanding  BIS_fnc_findSafePos

    http://tactical.nekromantix.com/wiki/doku.php?id=arma2:scripting:bis_fnc_findsafepos
	
*Already ported EMS Missions:

Major : SM1,2,3,5


Minor : None	
