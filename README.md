# Lets-Play-Twitch
Twitch streamers control computer

Project was created for democracy voted games. Example playing chess 200 versus 200 players.
It will gather twitch chat based commands for N seconds and will take actions based on most voted command
Can control keyboard and mouse using external driver project "interception"

======<br>
# INDEX:
======<br>
```
1. Quickstart
2. FAQ
3. Usage
4. Internal Programs
5. Special Keys
6. Mapper
7. Keyboard Layout
10. Troubleshooting
11. The config file
14. Special thanks
15. Contact
```
======<br>
# 1. Quickstart:
======<br>

- Install Interception as administrator with "install_as_admin.bat"
- reboot PC
- edit config.txt to your needs
- start "TwitchRDC.exe"

======<br>
# 2. FAQ:
======<br>

======<br>
# 3. Usage:
======<br>
If configured well, it will connect to a twitch irc channel. Will continuesly monitor chat. If keywords are found it will act as configured ( ex : move mouse )
It will not start taking actions until it can measure twitch latency. To do this watch your chat with broadcaster. Type "sync1" and wait until you see the chat in video, than write "sync2".
Press '`' in console to force shutdown
Type in chat "shutdown" as owner to initiate shutdown.

======<br>
# 4. Internal Programs:
======<br>

======<br>
# 5. Special Keys:
======<br>
'`' - makes the program shudown gracefuly

======<br>
# 6. Mapper:
======<br>
You can get keyboard map if you start the program : "TwitchRDC.exe 1". Program will enter special state to print any key you press

======<br>
# 7. Keyboard Layout:
======<br>

======<br>
# 10. Troubleshooting:
======<br>
Only tested on win 7 x64. If you have trouble you will need to contact me to investigate the isue

======<br>
# 11. The config file:
======<br>
There is a description in config file about layout.

======<br>
# 14. Special thanks:
======<br>
Interception library was written by Francisco Lopes ( i think ). You can contact him at he's site : http://oblita.com/interception.html

======<br>
# 15. Contact:
======<br>
You can contact me at jozsab1@gmail.com. I do receive quite a lot of email. Just saying in case there is no reply i could have marked it as spam or something.
