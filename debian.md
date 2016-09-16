### Install Elixir
Followed the directions on the Elixir website, but ran into a problem with Erlang
not installing because of some missing libraries. I tried to install these libraries
manually with no success. Then, I noticed in the ```apt-get`` error message
that it suggested running ```apt-get -f install``` and this got it installed.

Not sure this was the only solution because I had tried serveral other avenues like
manually installing from the Erlang Solutions website, but got the same missing
libraries error.


### Installing Guest Additions on Debian
1. Login as root
2. apt-get update
3. apt-get upgrade
4. apt-get install build-essential module-assistant
5. Run: m-a prepare
6. Click Install Guest Additions from the Devices menu
7. Run: mount /media/cdrom
8. Run: sh /media/cdrom/VboxLinuxAdditions.run

Had some problems with the Install Guest Addtions command, said it was already
mounted, but it all worked out in the end.

### Syntax Hightlighting in Vim
Added ```syntax on``` in a .vimrc (which I had to create on this machine).

### Switch Tabs in Terminal
Ctrl+PgUp, etc
Alt+1, etc

