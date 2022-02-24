# LittleBigPlanet Private Server Patcher
Private Server Patcher for the LittleBigPlanet Games based of [Jvy's patcher](https://github.com/LBPUnion/UnionPatcher).

# Important!
this version is being made on my free time, i might do random updates tho im not entirely sure if i may continue doing this!

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
- Java 11 or superior
- Eboot Decrypted on pc.[^2]

[^2]:This shouldnt be a problem in the future, since the goal is to decrypt it on the patcher


# How to run:
1. Install java 11 [Windows Installer](https://download.oracle.com/otn/java/jdk/jdk-11.0.12_windows-x64_bin.exe) |[MacOs installer](https://download.oracle.com/otn/java/jdk/11.0.12%2B8/f411702ca7704a54a79ead0c2e0942a3/jdk-11.0.12_osx-x64_bin.tar.gz) or dont install anything if you have a superior version.
2. Then you have to simply run the program by downloading it from the [Releases](https://github.com/SyngletOxygen/LittleBigPlanetPrivateServerPatcher/releases) tab.
3. Select the ´.elf´[^3] file, put the server dns / select it from the server list on the right side of the program *WITHOUT* the protocol (HTTP:// or HTTPS://) .
4. Choose the games that you are patching and write the name of the patched elf.[^4]
5. If you have done everything right, you shall press "Patch!"

## <a name= "games"> Supported games:</a>[^5]

### Main games:

| GAMES                  |Status                 |support spectrum     |Patcher version|
|------------------------|-----------------------|---------------------|---------------|
| LittleBigPlanet1       |<ul><li> [x] </li></ul>|90% sure,need testing|0.26+|
| LittleBigPlanet2       |<ul><li> [x] </li></ul>|Fully Supported      |0.25+|
| LittleBigPlanet3       |<ul><li> [x] </li></ul>|90% sure,need testing|0.27|
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
