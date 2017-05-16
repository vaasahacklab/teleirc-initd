# teleirc-initd
Initd script for teleirc-gateway.

You need to have teleirc from https://github.com/FruitieX/teleirc set up already for this to have any meaning.

Copy teleirc-networkname into /etc/init.d/teleirc-networkname, one per IRC-network to be connected into, and modify some parameters in the file(s).
Mainly:

| Parameter   | Value            | Example             |
|:----------- |:---------------- |:------------------- |
| IRCNET      | networkname      | IRCNET=freenode     |
| DIR         | /home/telebot    | DIR=/home/telebot   |
| DAEMON_USER | telebot          | DAEMON_USER=telebot |

Don't forget to chmod +x the file(s).
