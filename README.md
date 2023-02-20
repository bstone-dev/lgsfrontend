# lgsfrontend
This is a project to link together common Linux Game Server Manager hosted games with a front end. https://linuxgsm.com/

There will be several components I need to learn and research.

I'm planning on creating the following:

A discord bot that passes a limited set of commands back to my game server host.
Discord Bot Features:
      Updates (Automatic, manual, scheduled)
      Start/Stop servers
      Add mods
      Remove mods
      Save states
      Alerts and notifications to changes in a channel


I also would like to create a web-based GUI for the same tasks.
Features:
      Updates (Automatic, manual, scheduled)
      Start/Stop servers
      Add mods
      Remove mods
      Save states
      Alerts and notifications to changes in a channel

Pre-reqs for Website:
Reverse proxy to WSGI
WSGI of some kind (used waitress last project, I want to try using the same thing as well as another WSGI.
User based authentication. A lazy implementation might use google/microsoft integrated authentication. 
Separation of different sites, owners etc. No idea how i'll be able to implement this. Probably a V2 of my setup. V1 will just be basic "everybody gets in." 
 
