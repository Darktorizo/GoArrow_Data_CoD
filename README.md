# GoArrow_Data_CoD
2024-02-25
  
How to update GoArrow Dungeon Maps:
 - Unzip 'Dungeon Map Cache.zip' into your current ..Plugins\GoArrowVVSEdition\Dungeon Map Cache folder.
 - This is the baseline version from 2018.
 - Unzip 'Dungeon Map Cache Updates.rar' into your current ..Plugins\GoArrowVVSEdition\Dungeon Map Cache folder.
 - Overwrite all existing files since there have been updates to some images to reflect portal changes.
 - I needed to split off the updates from the baseline zip, since it was now bigger than 25MB size limit.  UGH!
 - Grand total is about 838 maps!

How to update GoArrow Atlas Locations:
 - Copy data_cod.xml to your hard drive.
 - Open Asheron's call. Open Go Arrow Plug-in. Click Atlas, then Update Menu. Copy full path to data_cod.xml file in the URL field.
 - Press "Update Locations Database" TWICE.  As of 2024-02-24 this should show 5391 current locations.  
 (There are over 200 'retired' locations in this file covering retired, seasonal and placess yet to be added with the latest ACE Emulator database v0.9.278)
 
Other notes:
- I'm using excel to generate xml and I've sorted file by location id now for easier editing.
- GoArrow creates ..Plugins\GoArrowVVSEdition\cod_locations.xml from the data in URL file you enter.
- If you delete ..Plugins\GoArrowVVSEdition\locations.xml, Go Arrow will re-create it to sync it with your cod_locations.xml file.
- GAlocations.xml has been fully merged into data_cod.xml.  It is no longer needed.
    
Thank you Darktorizo, Roogon and others for creating this locations file! More updates to come!
    - lugielord
    

-- Previous Comments from Darktorizo
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

3. Install GoArrow <Version>

4. Unzip/Overwrite any current files in the Dungeon Map Cache Folder

5. Enter Game, Go To Dungeon, Click On GoArrow > Dungeon Tab > This Dungeon 

Dungeon Maps "Should" Open

# GoArrow Dungon Maps Alternative

https://utilitybelt.gitlab.io/
