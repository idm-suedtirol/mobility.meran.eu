DEPRECATED
==========
The source code in this repository was used for the client side of the mobility.meran.eu web app.

The new code is available in the client folder of realtimebus repository:

https://github.com/idm-suedtirol/realtimebus

https://github.com/idm-suedtirol/realtimebus/tree/master/client


Client-side of bus.meran.eu
=============================

The client contains html/php, images, css and javscript files needed by the frontend.
Furthermore it contains openlayers adapted for realtimebus/bus.meran.eu and the whole configuration.

If you want to add/change/remove layers you need to modify js/sasabus.js

Widgets
-------

We provide the functionality of widgets for integration of single datasets into other websites. Widgets available are:
* http://mobility.meran.eu/widgets/?theme=bus
* http://mobility.meran.eu/widgets/?theme=walking
* http://mobility.meran.eu/widgets/?theme=carsharing
* http://mobility.meran.eu/widgets/?theme=bike
* http://mobility.meran.eu/widgets/?theme=emobility
* http://mobility.meran.eu/widgets/?theme=parking

The widgets are available also on:
* https://mobility.bz.it/widgets/?theme=bus
* https://mobility.bz.it/widgets/?theme=walking
* https://mobility.bz.it/widgets/?theme=carsharing
* https://mobility.bz.it/widgets/?theme=bike
* https://mobility.bz.it/widgets/?theme=emobility
* https://mobility.bz.it/widgets/?theme=parking

Setup your first client:
------------------------
- Install a web server like apache with php 
- Install a git-client
- checkout the repository localy with your git-client
- deploy the client folder on your apache


How to install on GNU/Linux (Ubuntu 14.04 apt-get)?
---------------------------------------------------
- sudo apt-get install git
- sudo apt-get install php5                # will install apache as dependency
- mkdir myGitRepo
- cd myGitRepo
- git clone https://github.com/tis-innovation-park/realtimebus.git
- git checkout c/s-separation              # set the dedicated branch
- cd /var/www/html
- ln -s ~/myGitRepo/realtimebus/client .   # maybe you need to do it as root / sudo
- http://localhost/client/                 # open in your web browser

