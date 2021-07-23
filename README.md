# Custom-Buffer-NPC-l2jserver Interlude

The order to integrate this custom NPC Buffer to your L2J Server are the following.

* 1) Get the npc.sql located in -> sql folder and execute it in the l2jdb database
* 2) Get 20701.htm file located in ->html/default and drag it to your server folders game/data/html/default folder
* 3) Get the 20701_NPCBuffer folder located in jscript/custom and drag it to your server folders game/data/jscript/custom folder
* 4) Open the __init__.py file located in your game server folder game/data/jscript/custom open it and add into the __all__ array, the name of the NPC folder '20701_NPCBuffer'
