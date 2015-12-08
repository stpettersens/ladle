******************************************************************

08/12/2015

Daniel Rampel has forked Ladle and is adding support
for POST requests, Lua scripting (Lua pages/scripts), etc.

Please see:

https://github.com/danielrempel/ladle

Unless you want to so something **extremely simple** with
Ladle, I would strongly recommend that you use his fork
rather than the original project listed here.

******************************************************************

13/03/2015

Ladle (lua-web-server) was originally a project on Google Code,
the original code has been ported as-is to Github because
Google Code is being shut down.

******************************************************************

--------------------------------
Ladle web server
--------------------------------

Prerequisites:

* Lua interpreter
* LuaSocket
* CGILua
* XML4Lua

=============================================================

To start the Ladle web server:

1) Open up a shell prompt
2) Navigate to directory containing ladle.lua
3) Run "webs" script

Make sure that the Lua intepreter is in your PATH
or you will have to type the full path to the Lua interpeter
e.g. /path/to/lua ladle.lua

The server runs by default on port 80 and can be accessed in 
a web browser with http://localhost

Files served by the server should be placed in /www

=============================================================

To stop the Ladle web server:

1) Open up a shell prompt
2) Navigate to directory containing ladle.lua
3) Run "telin" script followed by port number

   -> E.g. "telin 80" or "./telin.sh 80"
      if you ran the server on port 80

4) Type "kill" and hit return

=============================================================
