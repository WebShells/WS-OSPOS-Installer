# WS-OSPOS-Installer
WebShells &amp; OSPOS ( Open Source Point of Sale ) Auto Stand-Alone Installer

This file is for installing OSPOS on any hosting account using cPanel as a control panel with Shell Access.

. Cleans up Installation directory ( from previous installations )

. Downloads latest released project files

. Extract to desired location

. Auto configuration for database.php config file

. Create db User & Password db files depending on user's input of Dbname, Username, Password, & Hostname.

. Imports default Db SQL files using credentials provided by user at previous stage.

. Set file permissions for writable files

. Displays Installation / Server Info

**How to use ?**

1- Simply download Get-POS to your SSH using wget command.
2- Chmod +x Get-POS
3- Answer the required DB questions.

You're ready to enjoy OSPOS!

**Problems ?**

Please open up a new issue for reporting problems.
