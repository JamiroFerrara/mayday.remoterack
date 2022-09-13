 # Remote Rack
 This is the code for the remote rack. It is a simple tcp client / server for
 use with the raspberry pi.
 
 There are 3 projects in the repo, the server the rpi client and the shell
 command client.
 
 Install a server on the linode and run the commander / listener.
 
## Installation
** Might not work since repo is private.
### Windows
Listener

wget https://github.com/JamiroFerrara/mayday.remoterack.listener/releases/download/v1.0.0/listener-v1.0.0-x86_x64-pc-windows-msvc.exe

Server

wget https://github.com/JamiroFerrara/mayday.remoterack.server/releases/download/v1.0.3/server-v1.0.3-x86_64-pc-windows-msvc.exe

### Linux
Listener

wget https://github.com/JamiroFerrara/mayday.remoterack.listener/releases/download/v1.0.0/listener-v1.0.0-x86_64-unknown-linux-gnu

Server

wget https://github.com/JamiroFerrara/mayday.remoterack.server/releases/download/v1.0.3/server-v1.0.3-x86_64-unknown-linux-gnu

## Available commands
* 'shutdown' -> shutdown on all listeners
* 'reboot' -> reboots all listeners
* '00' -> turns off relay 0
* '10' -> turns off relay 1
* '20' -> turns off relay 2
* '30' -> turns off relay 3
* '01' -> turns on relay 0
* '11' -> turns on relay 1
* '21' -> turns on relay 2
* '31' -> turns on relay 3
