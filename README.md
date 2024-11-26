# Basic_C2_Server
## Description
A basic unix based command and control (C2) server, the server can handle multiple shell sessions concurrently, this client also comes equip with multiple command interfaces for handling sessions and creating basic reverse shell payloads. This project is not focused on creating shell code that can bypass modern AV, for basic capture the flag competitions where AV is minimal or not active this project will work fine.

## :desktop_computer: Building the Server
This project uses C++17, have the g++ compiler installed before cloning.
```bash
sudo apt update && sudo apt install g++
```
```bash
git clone https://github.com/EndermanSUPREME/CPP_C2_Server.git
chmod +x ./build.sh && ./build.sh
```

## :computer: Running the Server
The build.sh folder produces messages to stdout on how to run as well.
```bash
./server.out
```

## :wrench: Server Functionality
This C2 Server can:
* Support Multiple Shell Sessions
* Listen on ALL interfaces
* Interact/Remove Sessions via Input
* Basic Script Client to build basic reverse-shell commands
* Run Unix system commands locally when outside shell sessions
* Pop-up Notification when a Shell is possibly Captured

## Demo
https://github.com/EndermanSUPREME/Basic_C2_Server/assets/67215373/9bea9496-7404-4ab7-8042-d9d58a585225

## Developer Notes
There are still some small bugs that are being investigated
through testing the program operates as promised, but patches
are on the way!