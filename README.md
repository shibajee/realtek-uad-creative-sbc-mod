## Instructions:
- Uninstall current realtek audio driver, if possible use [DDU](https://www.wagnardsoft.com/forums/viewtopic.php?f=5&t=2747) for clean driver uninstallation.

- Restart ur PC with Disable driver signature enforcement:

Go to Settings > Update & Security > Recovery > Advanced startup > click Restart now

Now go to Troubleshoot > Advanced options > Startup Settings > click Restart

After the restart u will get a Startup Settings page, press F7 to go into disable driver signature enforcement.

- Download driver "Realtek_UAD_SBC_v6***.7z" from here [![Github all releases](https://img.shields.io/github/downloads/shibajee/realtek-uad-creative-sbc-mod/total.svg)](https://github.com/shibajee/realtek-uad-creative-sbc-mod/releases/) and extract it.

- Go to ***_UAD_WHQL_SBC folder and double click Setup.exe.

![alt text](https://i.postimg.cc/9QDrtMSq/Untitled-2.png)

Continue with the warning sign and click Install this driver software anyway. Do not restart, select I will restart my computer later.

- Enable Sideload apps:

Go to Settings > Update & Security > For developers > click Sideload apps and close.

- Now go to UWP_BUNDLE folder and run INSTALL_UWP_BUNDLE.bat as administrator. This will install Realtek Audio Console and Sound Blaster Connect UWP app. Installation is silent and will close automatically.

- We have to activate the Sound Blaster Connect. Go to GenKGA folder and run GenKGA.bat as administrator, activate ur desired soft.

(Some antivirus might detect GenKGA3.1.exe as a false posivite as like any other self made exe file, the source of GenKGA file can be found [HERE](https://pastebin.com/BHnvBYWD). Just disable ur antivirus/realtime protection or made the whole setup folder as a safe folder in antivirus.)

- Restart ur PC. If everything is ok, launch Sound Blaster Connect from start menu after the restart. Play a music file and try different presets in app to ensure that creative effects r working properly.


![alt text](https://i.imgur.com/0BOZ1a5.jpg)
![alt text](https://i.imgur.com/sOJN3I6.jpg)
![alt text](https://i.imgur.com/7ZL2bm7.jpg)


#### Uninstallation:

- First uninstall Realtek Audio Console and Sound Blaster Connect UWP app from Start menu or Settings, after that uninstall 
realtek audio driver and then restart ur pc (if possible use [DDU](https://www.wagnardsoft.com/forums/viewtopic.php?f=5&t=2747) for clean driver uninstallation)

#### Update:

- Uninstall current mod by above then install new driver.

- If u want to switch to different Creative soft, lets say u want to switch from Sound BlasterX 720 to Sound Blaster Cinema 5 then just run the "GenKGA.bat" again,
activate ur desired soft and restart ur pc. (u don't have to uninstall the whole driver or soft)


## FAQ:

- Which Windows version is compatible ?

Windows 10 2004 to present. (For Windows 10 older version or Windows 8.1/8/7 you can try the [Realtek HDA Mod](https://github.com/shibajee/realtek-hda-creative-sbc-mod))

Press Windows Key+R, type winver and hit enter to know the Windows Edition/Version.

- Both 32bit and 64bit ?

Only 64bit, get out from 32bit peasantry already.

- Which realtek audio chips are supported with this mod ?

Almost every audio chip they made.

- Any plan to add multiple APO in future ?

No, I like things simple and lightweight.

- Any update schedule for driver ?

Usually once in a month or two unless there is a binary update from Creative or MS store.
