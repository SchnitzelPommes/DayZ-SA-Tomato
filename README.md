# DayZ SA Tomato

Dayz Standalone UI Admin Tool



## Changelog

See CHANGELOG.md

## News

## 29.11.2018 23:00

### Fixed
- If more then one admin is Online both of them can see Playerlist + Map
- Teleport Buttons working now on PlayerTab 

 ### next up
 - Usage of Logs


#### If Someone got the mod to work on a 3rd Party hoster Cantact me or join https://discord.gg/Svgz48m

##  Notes

You can do with this tool what you want as the licence says if you add any features to it i would appreciate if you would share your code so that everyone can benefit from it.

#### Every mod which uses a Custom Mission is not compatible with any other mod which does the same so a merge has to be done in order to use both !
I recommend if you use it on your own server to merge this tool with your other mods (if there licence allows it) and create one big server mod for compatibility.

It is probably bad written.

It can be done better.

It has surely bugs i dont know of.

There will be someone who creates an actuall good Admin Tool.

Meanwhile i am Listening to suggestions 
and fixing the known bugs if i can .

You could cantact me per mail at DayZ-SA-Tomato@Primary-Network.de

## Installing
#### Disable all other mods you use right now

0. Check out this Link if you are using a 3rd party hoster they changed there Wiki since a user asked them how to Install this mod probs to them https://trugaming.com/wiki/index.php?title=DayZ#Server_Side_Mods hoefully this helps a little bit 
1. Copy DayZ-SA-Tomato to your Server/Client main Folder
2. Copy SchnitzelPommes.bikey to your Servers keys folder
3. Make sure YourServerFolder/DayZ-Sa-Tomato/Config/Admins.txt file exist (You can delete it Client side)
4. Make sure when step 3 completed add your Steam64ID to this file(for every ID 1 line)
5. Set start param -mod=@DayZ-SA-Tomato at Server/Client 
6. If not exist Add -profiles=D:\YourProfileFolderMaybe/DayzServer/Log and -scrAllowFileWrite To your server Parameters
![alt text](https://steamuserimages-a.akamaihd.net/ugc/43117016076707122/9D374D1F7933C13B477EE6792A3735D9FFAC74B4/)

#### Enable all mods you disabled one by one again contact me per mail at DayZ-SA-Tomato@Primary-Network.de and tell me which mods are not compatible so we can write a list here

Also Available in the Steam workshop 
https://steamcommunity.com/sharedfiles/filedetails/?id=1575615457






## Test and Use

Start your Server and login

Check your Server log for 

```
Adding Admin:
```

If this Meessage appears the server loadet the tool if not you did something wrong

```
In Game press "M" Key to bring up the UI
```

## Features

* **In Game** - M Key brings up the UI
* **In Game** - Insert Key go to Camera Mode Insert again to tp to Cursor
* **In Game** - N Key to Teleport to Cursor

------------

* **Commands Tab** - Toggle In Game Keys
* **Commands Tab** - Self Heal
* **Commands Tab** - Daytime
* **Commands Tab** - Nighttime
* **Commands Tab** - Spawn Car repaired and filled
* **Commands Tab** - Refill nearest Car

------------

* **Spawn Tab** - Item/AI/Building Spawning 

------------

* **Player Tab** - Player List
* **Player Tab** - Tp Players and tp to Players
* **Player Tab** - Strip Player
* **Player Tab** - Position of Player
* **Player Tab** - Disable Stamina for specific Player 
* **Player Tab** - Heal Player
* **Player Tab** - Kill Player

------------

* **Map Tab** - Shows Location of all Players on the Map


### Known Issues
* **Commands Tab** - Camera TP Buttons without Function
* **Spwan Tab** - Item Preview (right side not working)
* **Spwan Tab** - Building spawning in ground
* **Player Tab** - Blood Energy not showing correctly (sometimes it does)
* **Player Tab** - Send Message not working

## License

This project is licensed under the GNU v3 License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Everyone on the Forums/Discord who answered question (not only me but everyone)
* DayZCommunityOfflineMode for Snippets

