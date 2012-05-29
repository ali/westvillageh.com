# How to connect to IRC

IRC is a chat room where all the cool kids hang out. You'll need a
CCIS account to connect.

1. Open up Terminal.app if you're on a Mac, Cygwin if you're on
   Windows, or whatever Terminal Ubuntu comes with.
2. ssh onto a Linux machine on the CCIS network.
   Protip: login.ccs.neu.edu is a good choice
3. Type `screen` once you're connected. This creates a persistent
   session that you can connect to again in the future.
   Next time you connect to the machine, type `screen -dr` to resume
   your screen session.
4. Type in `irssi`. This opens up Irssi, an IRC client for terminals.
5. Type `connect irc` to connect to the CCIS IRC server.
6. You're now connected! Type `/list` to see a list of channels, and
   use `/join channelname` to join them. Example: `/join general`


## Further reading:

1. Prof. Barzilay's guide: http://pl.barzilay.org/resources.html#irc
2. The CREW IRC Primer:
   https://wiki.ccs.neu.edu/display/Crew/IRC+Primer
