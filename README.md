# WS-OSPOS-Installer
WebShells &amp; OSPOS ( Open Source Point of Sale ) Auto Stand-Alone Installer

This file is for installing OSPOS on any hosting account using cPanel as a control panel with Shell Access.

## Please make sure you run it in $HOME directory.

. Cleans up Installation directory ( from previous installations )

. Downloads latest released project files

. Extract to desired location

. Auto configuration for database.php config file

. Create db User & Password db files depending on user's input of Dbname, Username, Password, & Hostname.

. Imports default Db SQL files using credentials provided by user at previous stage.

. Set file permissions for writable files

. Displays Installation / Server Info

**How to use ?**

1- Download Get-POS using ```wget``` or ```git clone https://github.com/WebShells/WS-OSPOS-Installer.git``` <br>
2- ```cd WS-OSPOS-Installer``` <br>
3- ```mv Get-POS ..``` <br>
4- ```cd ..``` <br>
5- ```chmod +x Get-POS``` <br>
6- ```/Get-POS```<br>
7- Answer the required DB questions. <br>

You're ready to enjoy OSPOS!

**Problems ?**

Please open up a new issue for reporting problems.
