The spectator.cfg is set up to allow you to spectate every individual Player with a designated button.


F1 to F6 are in order: Red Scout1, Scout2, Soldier1, Soldier2, Demoman, Medic.
F7 to F12 are in order: Blu Scout1, Scout2, Soldier1, Soldier2, Demoman, Medic.

1 to 5 are in order: Red Sniper, Heavy, Engie, Spy, Pyro.
6 to 0 are in order: Blu Sniper, Heavy, Engie, Spy, Pyro.

Up-Arrow will activate the HUD and put the Game volume to 0.1
Down-Arrow will deactivate the HUD and mute the Game. (Used in pregame DM/In between scene)

These Key binds are just suggestions. You can change them up however you want, as long as it doesn't hinder the production quality.


The convars inside spectator.cfg are mandatory. if you are using a custom cfg, please make sure to copy over all convars.


The startup options need to be set inside Steam. To do so, go to your library and right-click on Team Fortress 2. Select "Properties..." and click on "Set launch options...". Then just copy the contents of "Startup options.txt"


OBS Studio is required for the Setup. You can download the latest version here: https://obsproject.com/


The Fonts CodeProLC and CodeProBold need to be installed. Please make sure that the Fonts work inside OBS Studio.


The new Scene Collection and Settings presets are mandatory to install.


To set up OBS Studio, open up the program and go to "Profile" in the navigation bar, then click on "Import". Navigate to the "OBS presets" folder and choose one of the 3 provided settings folders. High, Medium and Low correspond to the required CPU performance. Highlight the preset you want and click "Choose Folder"

To import the scene collection, in OBS Studio, go to "Scene Collection" and click "Import", then "Add". Navigate to the "OBS presets" folder and highlight "Scene collection.json" and click "Open", then click "Import".

Both presets should now be available on their respective drop-down menu.


To set up the Scene Transition find the Scene Transition window inside OBS Studio and click on the gear icon, then click on "Properties"

Now redirect the Video File into the "Animations" folder.

On the "InBetween" scene, you will need to set up the Staff Pictures as well as the "Game Capture" source.
To set up the Staff Pictures, right-click each Staff Picture source and go to "Filters". There you will find an "Image Mask/Blend" filter.
Click on it and, on the right hand side, you should see the settings pop up. Now you have to redirect the Path of the filter into the "Overlays" folder (..\Recources\Oberlays\Mask.png)

Now double-click each Staff Picture to open it's property window. Now redirect the Image File into the "Staff Pictures" folder and select one of the provided pictures.

To set up the "Game Capture" scene open up your TF2 and check if it registers the game window automatically. If not, double-click the source and target your game inside the properties window.


There are 2 Logs.TF Sources inside the Logs Scene. You will have to copy the Logs link into 1 of them to refresh them both. The Source higher on the list shows the Medic stats.

Leaving it invisible (clicking the eye icon) will show the normal Logs screen. Making it Visible reveals the Medic stats on top of the normal Logs.

In OBS Studios "Studio Mode", you will have to Transition to the Logs Scene if you want the Medic stats to show up on the stream.

You may need to resize the Sources if team sizes change. To resize Sources, unlock the Source, hold ALT and drag the red dots in the direction you want to crop.


If you have trouble with any of these functions, Ping or PM @KortexTF #2405 on Discord.
