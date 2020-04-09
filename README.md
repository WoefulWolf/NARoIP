# NARoIP
NieR:Automata Race over Internet Protocol - the *kinda* multiplayer mod? <br>
Built upon *mar7ymoose*'s 2B Hook mod (https://www.nexusmods.com/nierautomata/mods/10).

## What is this?
NARoIP is a mod which adds basic multiplayer-like synchronization between game clients. <br>
Players on a server have their positions and names shared visually in the 3D game-world. <br>
The distance from your own player to other players is also displayed. <br>
This was made specifically with speedrunners in mind.

## Downloads
https://github.com/WoefulWolf/NARoIP/releases

## Installation
- Follow the same instructions as that of 2B Hook (https://www.nexusmods.com/nierautomata/mods/10) but using *NARoIP.dll* instead of *2B Hook.dll* <br>
##### OR
- Inject *NARoIP.dll* into your *NieRAutomata.exe* process using an injector (I recommend https://github.com/DarthTon/xenos)

- Open the menu in-game by pressing the default *INSERT* keybind.

## Hosting your own server
- Port forward UDP port *11939*.
- Run *NARoIP_Server.exe* (Windows), or *./NARoIP_Server* (Linux).
- (Make sure a firewall isn't blocking anything.)

## Credits
- mar7ymoose (2BHook)
- Amei (Testing)
- Mytherium (Testing)
- gbchan (Testing)
- Kekoulis (Testing)

#### Why no source-code?
Like stated above, this was built upon *mar7ymoose*'s 2B Hook which is not a public repository. <br>
(And my code is really messy.)
