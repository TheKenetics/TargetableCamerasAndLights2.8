# TargetableCamerasAndLights
Blender addon to create targetable cameras and lights

## Why
This addon makes it easier to add a targetable camera or light to the scene, or make existing cameras and lights targetable.

## Installation  
### Requirements  
Works on Windows, Mac, and Linux.
Created for Blender 2.8 Beta
### How to Install  
Download the python file (put it in a place where you can easily find it, like your desktop)  
In Blender's settings, go to the addons tab  
At the bottom, click "Install from File"  
Find where you put the python file, select it, and click "Install from File"  

## Using
### Creating New Targetable Cameras/Lights
Inside the 3D View in Object Mode, set the 3D Cursor where you want the camera/light to be.  
Then select the object you would like the camera/light to point towards.  

Open the Add Object menu, and go to:  
Camera > Add Targetable Camera  
or  
Light > Add Targetable Light > Type  

A camera or light will be created at the 3D cursor, and the target empty will be created at the active object.

### Making existing Cameras/Lights Targetable
Select all the existing cameras/lights you would like to make targetable.  

Open the Add Object menu, and go to:  
Camera > Add Target to Selected Cameras  
or  
Light > Add Target to Selected Lights  

A target empty will be created and all selected cameras/lights will target it.
