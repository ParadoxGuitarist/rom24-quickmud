rom24-quickmud
==============

## How to use this image

$ docker run -d -p 4000:4000 avinson/rom

telnet localhost 4000

To make your first immortal character, just start as a mortal
character, play at least as far as level 2, and then edit the
player file and change your level.  (After the first immortal,
you can advance the rest)

-----
QuickMUD is a Rom24b6 codebase with the following major features added:

* OLC 1.81
* Lope's Color 2.0
* Erwin's Copyover
* Erwin's Noteboard
* Color Login

It is still basically a "stock" ROM server.  The  functionality  of the
code hasn't been modified much except for the addition of  OLC. Changes
are pretty much limited to cosmetic features, like color login.  If you
want to start your own ROM based server, this code can give you a quick
start with some standard 'extra features' already implemented. However,
for the sake of the mudding community at  large,  don't  just  download
this code, compile it, and advertise it on MUD websites  as  "a  highly
modified  ROM  codebase".  Spend  some  time  developing  it. The world
doesn't need another cookie-cutter MUD.

Need help? Your best bet is to check out the ROM mailing list archives.
It can currently be found at http://www.the-infinite.org/lists/romlist.
Information  on the ROM mailing list itself can be requested by running
"echo help | mail rom-request@rom.org" (without the quotes). Aside from
that,  grab a  good  book on C and  visit your favorite search engine a
lot :)

Also,  for real-time  help,  try irc.acestar.org:6667  #rom.  There are
a lot of very good people hanging out in there willing to help  you out
with your mud-related cunundrums.

Any  existing bugs  in the  code can be reported to flugh@flugh.org.
I'll do my best to repair them ASAP.

Enjoy!
