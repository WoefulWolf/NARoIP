# STOPPED DEVELOPMENT/DOESN'T WORK ON NEW PATCH
# NARoIP (w/ VC3Mod)
NieR:Automata Race over Internet Protocol - the *kinda* multiplayer mod? <br>

![Modifications](https://i.imgur.com/cLEBdyD.png)

## What is this?
NARoIP is a mod which adds basic multiplayer-like synchronization between game clients. <br>
Players on a server have their positions and names shared visually in the 3D game-world. <br>
The distance from your own player to other players is also displayed. <br>
This was made specifically with speedrunners in mind. <br>

Ghost racing has also now been implemented, allowing users to record and save *.ghost* files! <br>
These files can easily be shared among users and used for practice during playback. 

## Downloads
https://github.com/WoefulWolf/NARoIP/releases

## Installation
### Myth's NARoIP Guide Video
[![Myth's NARoIP Guide](https://img.youtube.com/vi/fSGBdcc4wqs/0.jpg)](https://www.youtube.com/watch?v=fSGBdcc4wqs)
- Place the *xinput1_3.dll* file in your NieR:Automata directory (adjacent to your NieRAutomata.exe).
- Launch the game.
- Open the menu in-game by pressing the default *PAGE_UP* keybind.

## Hosting your own server
- Port forward UDP port *11939*.
- If running Linux server, you will require the ENet package (For [Debian, Ubuntu, etc.](https://packages.ubuntu.com/focal/libenet7) or [Arch, etc.](https://www.archlinux.org/packages/community/x86_64/enet/)).
- Run *NARoIP_Server.exe* (Windows), or *./NARoIP_Server.out* (Linux).
- (Make sure a firewall isn't blocking anything.)

## Help!
### Cannot run linux server! ("Permission denied", "command not found", "cannot execute binary file")
- Try marking the file as an executeable with: `chmod +x NARoIP_Server.out`

## Credits
- icefire (VC3Mod)
- mar7ymoose (2BHook)
- Amei (Testing)
- Mytherium (Testing)
- gbchan (Testing)
- Kekoulis (Testing)
- rodg (Testing)

#### Why no source-code?
This is the sort of private project that incorporates mods from other users, but if you personally ask, I really won't mind providing you with the source code.
