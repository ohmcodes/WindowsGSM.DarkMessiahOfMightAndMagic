# WindowsGSMPluginTemplate
🧩WindowsGSM plugin that provides Dark Messiah of Might and Magic
 Dedicated server


# WindowsGSM Installation: 
1. Download  WindowsGSM https://windowsgsm.com/ 
2. Create a Folder at a Location you wan't all Server to be Installed and Run.
4. Drag WindowsGSM.exe into previously created folder and execute it.

# Plugin Installation:
1. Download [latest](https://github.com/ohmcodes/WindowsGSM.DarkMessiahOfMightAndMagic/releases/latest) release
2. Extract then Move **DarkMessiahOfMightAndMagic.cs** folder to **plugins** folder
3. OR Press on the Puzzle Icon in the left bottom side and install this plugin by navigating to it and select the Zip File.
4. Click **[RELOAD PLUGINS]** button or restart WindowsGSM
5. Navigate "Servers" and Click "Install Game Server" and find "Dark Messiah of Might and Magic Dedicated Server [DarkMessiahOfMightAndMagic.cs]

### Official Documentation
🗃️ N/A

### Unofficial Documentation
🗃️ N/A

### The Game
🕹️ https://store.steampowered.com/agecheck/app/2100/

### Dedicated server info
🖥️ https://steamdb.info/app/2145/


### Guide
start parameters
`-console -condebug +maxplayers 16 +map ctf_3 +exec server.cfg`

server.cfg
```
hostname "Your Server name here" // server name
rcon_password "yourrconpasshere" // server admin (rcon) passsword
sv_password "yourpasshere" // server join password

//Game Play Vars
mp_friendlyfire 1
sv_alltalk 0
sv_pausable 0
sv_cheats 0
sv_consistency 1
sv_voiceenable 1
mp_gametype 2 //[0|1|2] 0 = Deathmatch 1 = Team Deathmatch 2 = Campaign

// bandwidth rates/settings
sv_minrate 3000
sv_maxrate 20000
decalfrequency 60
sv_maxupdaterate 100
sv_minupdaterate 30

log on                //Creates a logfile (Enable= on Disable= off)
sv_logfile 1            //Log server information in the log file.
sv_logsdir D:\SRCDS\cstrike\logs    //Folder in the game directory where server logs will be stored.

sv_logecho 0            //Echo log information to the console.

sv_log_onefile 1        //Log server information to only one file.
sv_logbans 1            //Log server bans in the server logs.
sv_logdownloadlist 1        //Log files to download.

// operation
sv_lan 0
// region the server should appear in under the steam browser
sv_region 0
sv_contact "www.example.com"
```



# License
This project is licensed under the MIT License - see the <a href="https://github.com/ohmcodes/WindowsGSM.DarkMessiahOfMightAndMagic/blob/main/LICENSE">LICENSE.md</a> file for details
