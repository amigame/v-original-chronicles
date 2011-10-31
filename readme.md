# V: Original Chronicles

A mod for HL2 that tries to re-imagine the orignal V series using the Source Engine. 


### How to play

Download the mod and extract it in the Steam folder - in this sub-directory: 
<Install dir>/Steam/SteamApps/SourceMods

Next time you restart Steam it should come up in tyour Library as "V: Original Chronicles" 

To play the game you'll need the Source SDK 2006 installed - if not available you'll be prompted to install it. 

Once the gmae is loaded you'll first come accross an almost empty menu screen. In this first release you'll have to load the map and NPCs with the console :P 

So, bring up the console hittin "~" and then load a map typing: 

    map dm_overwatch

This is one of the most popular multiplayer maps of HL2 and we've just included it so you can test/fool around with the characters. 

We've setup the following shortcuts so you can create a little shootout:

    bind "b" "npc_create_equipment equipment_smg1"
    bind "j" "npc_create npc_combine_s"
    bind "n" "npc_create npc_citizen"
    bind "h" "npc_create npc_helicopter"

This means you can hit "B" to equip the NPCs then start to hit "J" (for soldiers) and "N" (for the resistance) as many times as you want. In Addition "H" will spawn dropships. Addmitedly the spawning is a bit buggy and only works when the crosshair is pointed on clear ground... 

The Visitors will attack you and the resistance, while they fight back. The Visitors will evade and move around a little bit, if they have to. The dropship doesn't do anything without proper map settings.

If you'd like to hand out more  firepower, you can alternatively bind H with
 
    bind "h" "npc_create_equipment equipment_ar2"


### How to help 

This is a community project and you are more than welcomed to participate in the development. Feel free to checkout the repo, read through the issue tracker and submit pull requests with addressed issues. 

The ultimate goal is to convert the whole single player campaign of HL2 with V soldiers and spaceships. 


