# ark
Ark Survival Evolved File Backups and Working Files


Corruption issue:

When starting up there was an issue with the service complaining about a config option not being valid.
It turned out the /home/ark/server/ShooterGame/Config/Default* is NOT were the problem was.
The problem actaully resides in a corrupted "cache" folder located at: /home/ark/server/ShooterGame/Saved/Config/LinuxServer/Engine.ini 

removing that file allowed the server to re-create the file.