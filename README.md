# gcpadder-linux
Userspace Linux driver for the Wii homebrew application [GCPadder](https://github.com/InvoxiPlayGames/GCPadder), originally by InvoxiPlayGames.

To build this, you should edit the `IP_ADDR` macro in main.cpp to point towards your Wii's local IP address. Then run GCC:
```sh
$ g++ -o gcpadder `pkg-config --cflags libevdev` `pkg-config --libs libevdev` main.cpp
```

Note that I likely won't be working on this any further, unfortunately.