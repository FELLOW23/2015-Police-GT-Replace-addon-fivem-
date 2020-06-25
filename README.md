# 2015-Police-GT-Replace-addon-fivem-

Installation [ADDON]

In OpenIV navigate to \mods\update\update.rpf\common\data and extract dlclist.xml to your desktop. Open it with notepad and add the text below to the bottom of the list of dlcpacks, save it and put it back where it came from. 
    <Item>dlcpacks:\policegt350r\</Item>

Then navigate to \mods\update\x64\dlcpacks and create a new folder called policegt350r and put my dlc.rpf into it. 
Use trainer to spawn by name: policegt350r

[REPLACE] 

Put my replace vehicle files here > \mods\update\x64\dlcpacks\patchday3ng\dlc.rpf\x64\levels\gta5\vehicles.rpf 
Dont forget to copy and paste my police3 data where it belongs. I dont know where to put it so your on your own! 

[FiveM]

Navigate to FXSERVER > CFX > Resources > make a folder (policegt350r) open > make a stream folder > make a __resource.lua by right clicking and make a text document  > add  > resource_manifest_version '77731fab-63ca-442c-a67b-abc70f28dfa5'
 
files {
    'vehicles.meta',
    'carvariations.meta',
    'carcols.meta',
    'handling.meta',
    'vehiclelayouts.meta',    -- Not Required
}

data_file 'HANDLING_FILE' 'handling.meta'
data_file 'VEHICLE_METADATA_FILE' 'vehicles.meta'
data_file 'CARCOLS_FILE' 'carcols.meta'
data_file 'VEHICLE_VARIATION_FILE' 'carvariations.meta'
data_file 'VEHICLE_LAYOUTS_FILE' 'vehiclelayouts.meta'   -- Not Required

In the __resources folder > go back to the policegt350r folder > open openIV > and paste  the dlc.rpf folder in the mods folder and open it > x64 > vehicles.rpf > and paste all the folders in the stream folder > go back to the dlc.rpf folder > open the data folder > and paste in the main folder > DONE!!! > join the server and spawn with the name of the folder.

Thanks for using it and if you have any more questions join my discord and i will help.

Discord: https://discord.gg/UNTTaW7

ENJOY!!
