

![usat](https://user-images.githubusercontent.com/33130624/55902959-8373b400-5b9a-11e9-9f45-df11bedfa7b4.gif)

About USAT project:

USAT is short for "Unix System Administrator Tool".
USAT uses text terminal as interface (tui) and is a  menu based program written by Perl and has in scope to assisst Unix Administrators.

USAT has over 60 menus or submenus that each is supposed to do some task for system admin.

USAT holds the following information in MySQL tables:
- Specs of servers in local network
- Login credentials
- Commands to execute on remote servers
- Scripts that can be executed for a remote server
- Information about Data Base and existing tables

System admins can use a collection  of scripts  and
commands, stored in DB to manage servers  available
in the network.

You can upload or  download  your own  commands  and
scripts into database and this collection of commands
and scripts can  be managed or extended.

Important features for USAT
- Run a command from DB on a remote server
- Run a script from DB on a remote server
- Stores hardware and other detailed information about
  the servers in the network in a DB.
- Manage a dedicated Database named  as  "servers"  to
  store  commands, scripts  and many  other useful
  information related to each server.
- Direct access to remote server through USAT interface
  by simulating telnet or ssh

General view
USAT starts with a main menu. Main menu is divided
to other sub menus.
Each submenu can be considered as a  separate  category
with its own jobs.
