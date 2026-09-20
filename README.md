# PAC-Bin-Exporter-Importer-Wii-Party-U
Hello there! Do you want to edit or see assets inside the game Wii Party U? I hear a yes! This is a step by step guide on how to do so, Keep this in mind this has an importer and exporter that are much more flexible then the old way, however do keep in mind there could be bugs or glitches!
First, we need da software needed to even extract the files, You may download them a here!: https://github.com/ThatOneDumWiiUGuy/PAC-Bin-Exporter-Importer-Wii-Party-U/releases/tag/V1

The OG Tutorial is here!: https://gamebanana.com/tuts/19932
Exporting
Step 1: Install python 3, https://wsvincent.com/install-python/
Step 2: Extract the .zip and drop PACExporter.py into the folder with your .bin files.
Step 3: Run terminal or cmd (or if you can't be bothered, double clicking the .py)
Once you have done that, it should make a folder with the assets with the name of the bin file with _extracted added to it.
Editing:
Step 1: Download Switch Toolbox from https://github.com/KillzXGaming/Switch-Toolbox/releases/tag/Final
Step 2: Extract and Run "Toolbox.exe"
Step 3: This should allow you to edit a big majority of the files, files with bnfm in them are not editable yet, however soon if i get my crap together you will be able to!
Step 4: Make sure to press "Save" once you made your changes!
Explain: Basically the game for most textures has 1 or 2 more variants, this is the map of it,
This exists so it gives off a 3D Feel, well if you edit the regular texture but not the map or vice-versa
the game WILL crash.
Where are the maps?: They have a similar name to the file you are editing, normally with "_normal"
slapped after it, it looks the same but with weird yellowish colors, They are always in the same area as the regular texture.
Step 1: Find the map.
Step 2: In Switch Toolbox there should be a Properties Tab, Search for the Value "Mip Count"
Step 3: Once you know the Mip Count, select the EXACT SAME PHOTO, that you used for the regular texture
Step 4: Right Click the Texture and replace it, In GX2 Importer Find the Mip Count and Set it to the Mip Count you saw earlier, if not when repacking it'll increase the size of the .bin aka corrupting it.
Step 5: Once you set it to the exact Mip Count select okay and save! 

So you have made whatever hellspawn you want, what is next? Well of course importing it into the game itself!
Importing
Step 1: Grab PACImporter.py and put it in the folder where your og .bin files are and the extracted folder, make sure to keep every file that was there in the extracted folder is still there, including your modded assets.
Step 2: Execute the script
Step 3: Rename the new .bin file to remove the _modified addition and using sd caffiene replace the files, potato potato you have your hopefully working mod!
Enjoy!
