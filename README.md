# teleirc-initd
Initd script for teleirc-gateway.

You need to have teleirc from https://github.com/FruitieX/teleirc set up already for this to have any meaning.

Copy teleirc-networkname into /etc/init.d/teleirc-networkname, one per IRC-network to be connected into, and modify some parameters in the file(s).
Mainly:

IRCNET=networkname  (for example freenode)
DIR=/home/telebot   (where teleirc is installed in your system)
DAEMON_USER=telebot (username for running the daemon)

Don't forget to chmod +x the file(s).
