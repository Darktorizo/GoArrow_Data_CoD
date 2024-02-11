# GoArrow_Data_CoD
2024-02-11
  
GoArrow Dungeon Map updates:
  - Unzip BOTH 'Dungeon Map Cache Baseline 20180827' & 'Dungeon Map Cache Updates' into your current ..Plugins\GoArrowVVSEdition\Dungeon Map Cache folder.
    Had to split into 2 files since it was now bigger than 25MB.  UGH! 

GoArrow Atlas Location updates:
 - Copy data_cod_20240211.xml to your hard drive.
 - Open Asheron's call. Open Go Arrow Plug-in. Click Atlas, then Update Menu. Copy full path to data_cod_20240211.xml file in the URL field.
 - Press "Update Locations Database" TWICE.  Should show 5187 current locations.  (There are 227 'retired' locations in this file now that are missing or don't work in ACE Emulator version)

Created new file data_cod_20240211.xml since I changed the file format quite a bit from Darktorizo's posted data_cod.xml file. I'm using excel to generate xml and sorted file by location id now for easier editing.
GoArrow creates ..Plugins\GoArrowVVSEdition\cod_locations.xml from the data in URL file you enter.
If you delete ..Plugins\GoArrowVVSEdition\locations.xml, Go Arrow will re-create it (This syncs it with cod_locations.xml)
You should no longer need GAlocations.xml,
You should no longer need (previous) data_cod.xml
    
Thank you Darktorizo, Roogon and others for creating this locations file! More updates to come!
    - lugielord
    
--- 
Decal Plugin GoArrow Locations Database

For whatever reason just putting the link below in the GoArrow Update the Locations Database / URL Box does not work and gives an error.

Instead download the file using the link, save to somewhere like C:\data_cod.xml, the add that to the GoArrow Update the Locations Database / URL Box, Hit the Update Locations Database button, Let it finish, then hit the button again.

Current number of locations in database should read: 5219 (as of 11.20.2023 anyways)

---

Darktorizo's Location Database:

https://raw.githubusercontent.com/Darktorizo/GoArrow_Data_CoD/master/data_cod.xml - Last File Update / Upload 11.20.2023

---

Roogon's Location Database:

https://raw.githubusercontent.com/Darktorizo/GoArrow_Data_CoD/master/GAlocations.xml - Last File Update / Upload 04.15.2012

Mirror Of:

http://maps.roogon.com/downloads/GAlocations.xml - Last File Update / Upload 04.15.2012

---

# GoArrow Dungeon Maps
How I got the Dungeon Maps to work (Your Milage May Vary)

1.Modify your hosts file in Windows 10

    Open Notepad with administrator privileges.
    Browse to C:\Windows\System32\drivers\etc\hosts (Or paste this into the address bar)
    Open the file.
    Add:
    #Asherons Call ACMAPS for Go Arrow
    127.0.0.1 www.acmaps.com
    Save File
    
2. Download your GoArrow of choice:

Standalone
https://github.com/Darktorizo/GoArrow_Data_CoD/blob/master/GoArrow%203.0.0.0.msi

-Or-

VVS Edition
https://github.com/Darktorizo/GoArrow_Data_CoD/blob/master/GoArrow_2.5.0.0.VVS_WDM.zip

Also

https://github.com/Darktorizo/GoArrow_Data_CoD/blob/master/Dungeon_Map_Cache.zip

3. Install GoArrow <Version>

4. Unzip/Overwrite any current files in the Dungeon Map Cache Folder

5. Enter Game, Go To Dungeon, Click On GoArrow > Dungeon Tab > This Dungeon 

Dungeon Maps "Should" Open

# GoArrow Dungon Maps Alternative

https://utilitybelt.gitlab.io/
