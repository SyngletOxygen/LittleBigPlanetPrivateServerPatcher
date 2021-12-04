# LittleBigPlanet Private Server Patcher
Private Server Patcher for the LittleBigPlanet Games



### Features:

- Patches this [games](#games)
- Connectivity to the List of Private Servers


### TODO:
- add filter for certain games<br />
- host 24/7 server list[^1]<br />
- utilize TCP client with PS3 to automatically find the user's EBOOT in the correct folder for them
- Decrypt the eboot.bin



[^1]: it is being hosted but only temporarly



### Prequisites:
- Lastest version of java
- Eboot Decrypted on pc.[^2]

[^2]:This shouldnt be a problem in the future, since the goal is to decrypt it on the patcher


# How to run:
Install the lastest version of [java](https://www.java.com/en/download/ie_manual.jsp).
Then you have to simply run the program by downloading it from the [Releases](https://github.com/SyngletOxygen/LittleBigPlanetPrivateServerPatcher/releases) tab. <br />
Select the ´.elf´[^3] file, put the server dns / select it from the server list on the right side of the program, and write the name of the patched elf.[^4]<br />
And if you have done everything right, you shall press "Patch!"

## <a name= "games"> Supported games:</a>[^5]

### Main games:

| GAMES                  |Status                 |support spectrum     |Patcher version|
|------------------------|-----------------------|---------------------|---------------|
| LittleBigPlanet1       |<ul><li> [x] </li></ul>|90% sure,need testing|0.26+|
| LittleBigPlanet2       |<ul><li> [x] </li></ul>|Fully Supported      |0.25+|
| LittleBigPlanet3       |<ul><li> [x] </li></ul>|90% sure             |N/A|
| LittleBigPlanet PsVita |<ul><li> [ ] </li></ul>|N/A                  |N/A|
| LittleBigPlanet PSP    |<ul><li> [ ] </li></ul>|N/A                  |N/A|
| LittleBigPlanet Karting|<ul><li> [ ] </li></ul>|N/A                  |N/A|


### Non Mainline games:
| Games                              |Status                 |support spectrum|Patcher version|
|------------------------------------|-----------------------|----------------|---------------|
| LittleBigPlanet  Deploy build      |<ul><li> [ ] </li></ul>|N/A             |N/A            |
| to be decided                      |<ul><li> [ ] </li></ul>|N/A             |N/A            |



[^3]:this is the file that the Decryptor gives when the file is ... well .... decrypted.
[^4]:this file will be the output of the Patcher, the extension is <FILENAME>.patched. , you can write any folder, if you just write the name of the file, it will get set on the same folder as the patcher.

[^5]: this will get updated while i work on the patcher...
