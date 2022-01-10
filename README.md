# SDTemplate
Project Template for Substance Designer

This is a simple starter template for designer projects, with a custom node for toggling between both Unity's and Unreal's default mask packing.

![HDRP Support](Images/Engine_HDRP.PNG?raw=true "HDRP Support")

![Unreal Support](Images/Engine_Unreal.PNG?raw=true "Unreal Support")

![Unreal Support](Images/Overview.PNG?raw=true "Unreal Support")

# Installation
Make sure a path to the directory of the GameMaskPacker file exists under Preferences -> Projects -> Library
Also ensure a path to CustomDefault under Preferences -> Projects -> General -> Template Directories

Personally, I have a folder for "Designer Library" with nodes and whatnot and a subfolder for templates, and just throw all my things in there as follows:

![LibraryDir](Images/LibraryDir.PNG?raw=true "LibraryDir")
![TemplatesDir](Images/TemplatesDir.PNG?raw=true "TemplatesDir")

# Use
Provided your librarys are all set, just make a new project and your template should be one of the options

![Usage](Images/Use.PNG?raw=true "Usage")

On export, just toggle off the "Materials" section if you only want the useful stuff, as they're for automatic viewing's sake.
One thing to note is that I pack Height into the non-RMO channels of the masks, but I distributed the sbs so you can change whatever you like

![Exporting](Images/Export.PNG?raw=true "Exporting")