# SRCoder FPS Controller  
## Introduction
This is a basic but flexible First Person Controller for use in your projects.
## Instructions

Once you have the addon from the assetlib, just drag ```player.tscn``` onto your scene. Make sure no other camera are on the scene as the prefab comes with it's own.  
Then set up the following actions in the Project->Project Setting->Input Map:
1. up
2. down
3. left
4. right  

These must be named exactly as shown here.

Optionally, you can add ```mouse_lock.tscn``` onto your scene too.
    
MouseLock will allow the mouse to be toggled with escape and comes with a handy signal in case you need it.
  
  
The Player comes with quite a few tweakable values and is fully documented and commented. Feel free to experiment.
  
    
Lastly, there is a sample scene in the addon. If you want to see it in action, open ```sample-scene.tscn``` to see the fps controller in action.