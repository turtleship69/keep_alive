# Keep_alive
A script to allow you to keep your repl always on using something like uptimerobot.com

# Usage
1) pip install flask
install it yourself just to be safe ;)
2) pip install keep_alive
from the shell just run the above command
3) use the code
import keep_alive
keep_alive.keep_alive()
4) uptimerobot.com
set it up to ping your repl every 30 minutes.
The url to use (which shows up after you run the flask server, or script, at least once) is the one which looks like this: 
https://LiquidAustereCommand.nathanmachane.repl.co
the first part is your project name, the second is your username, the rest is just repls domain.
5) Thats it

# Use cases
1) Discord bot
2) A long running computation that will probably time out (I suggest against this, it is arguably abuse)
3) A website made in flask (in which case this is pretty much useless)
