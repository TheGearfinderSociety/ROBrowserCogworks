## ROBrowser - Cogworks
A public version of the Gearfinder Society private edits and patches for ROBrowser. Made to properly support new features from modern emulators. This is available for free to any user who wish to test our system, we do recommend you to check out the original implementation that you can find here: [roBrowserLegacy](https://github.com/MrAntares/roBrowserLegacy/)

You can find our development community (and the official Gearfinder base) here: [Discord](https://discord.gg/wmXxjYHrqw)

All credits to the original team behind roBrowser and roBrowserLegacy.

## Guide
Starting Guide: [Guide](doc/README.md)

## Remote Client
Remote Client serves game assets to roBrowser via http by extracting them from their GRFs. You will need to setup a remote client if you want to serve the game assets centrally from your server. roBrowser can use local game assets via the Intro screen by dragging them into the file box. The original implementation of the Remote Client is written in PHP:
- [roBrowserLegacy-RemoteClient-PHP](https://github.com/MrAntares/roBrowserLegacy-RemoteClient-PHP)

Other implementations may arise and when they do we will list them here:
- [roBrowserLegacy-RemoteClient-JS](https://github.com/FranciscoWallison/roBrowserLegacy-RemoteClient-JS)

## WebSocket Proxy
The game server uses TCP/IP to communicate with the client, while roBrowser being a web page can't use TCP/IP. We use the WebSocket API to communicate with a proxy server that translates the packets into TCP/IP packets. This server is called wsProxy. You will need to install and configure wsProxy to make roBrowser able to connect to a game server. For more info, please visit the [roBrowserLegacy-wsProxy](https://github.com/MrAntares/roBrowserLegacy-wsProxy) repository.

## Contact

* [Discord](https://discord.gg/wmXxjYHrqw)
* Personal Discord Contact: rumiexmachina (Rumi Gearlock)
