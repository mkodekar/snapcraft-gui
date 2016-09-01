# snapcraft-gui (development)
Graphical user interface to create snaps using snapcraft as backend , written in qt.

#Current task:
Snap package Manager (click package manager in file menu to see):

	-with local snap installation capabilities [Done]

	-allow remove installed snaps [Done]

	-allow obtain informatio about installed snaps by selecting them [Done]

	-allow check for snaps updates [Done]

	-allow update updatable snaps [Current target]

Snapcraft.yaml editor:
	
	-snapcraft's styled Yaml syntax highlightning [Done]
	
	-full editor functionalities [Done]
	
	-pastebin integration [Done]
	
Snap lifecycle commands [not started yet]

#NOTE:
Am implementing/adding each feature one by one so, all the features will not work. see the commits log to check what will work and what will not.

Currently it will not build any snap, that feature is yet to be implemented.


#ScreenShot

![snapcraft-gui](https://github.com/keshavbhatt/snapcraft-gui/blob/master/screenshots/sc1.png?raw=true)
![snapcraft-gui](https://github.com/keshavbhatt/snapcraft-gui/blob/master/screenshots/sc2.png?raw=true)
![snapcraft-gui](https://github.com/keshavbhatt/snapcraft-gui/blob/master/screenshots/sc3.png?raw=true)

#Build

	Build on Ubuntu 16.04 (Qt version 5.5.1) Gcc(64bit)

#dependencies

	See dependencies file in the source tree above

