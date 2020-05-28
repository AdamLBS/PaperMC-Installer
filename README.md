# Bungeecord and Paper installer for Linux (forked from AdamLBS/mcinstall for PaperMC)

* [Requirements](#requirements)
* [Features](#features)
* [Supported versions](#supported-versions)
* [Installing](#installing)
* [Launch](#launch)
* [Updating](#updating)
* [Bugs](#bugs)
* [License](#license)

# Requirements

* Unix-like OS

* curl




# Features 

* Auto-Updater
* Automatically install all prerequisites
* Install both BungeeCord and Spigot at the same time.
* Using the latest stable versions of Spigot.


# Supported versions
* 1.8.8
* 1.9.4
* 1.10.2
* 1.11.2
* 1.12.2
* 1.13.2
* 1.14.4
* 1.15.2

# Installing

* **curl** is required to download the script.

* If you are logged in as root 
```bash
curl https://uploads.admlbs.fr/download.php?file=paperinstall --output /usr/bin/paperinstall && chmod 0777 /usr/bin/paperinstall
```

* If it's not the case : 

```bash
sudo curl https://uploads.admlbs.fr/download.php?file=paperinstall --output /usr/bin/paperinstall && sudo chmod 0777 /usr/bin/paperinstall
```

# Launch

* To launch the script and install a server you must use sudo or being root

```bash
paperinstall install
```

* To see all commands please type 

```bash
paperinstall help
```
# Updating

* To update the script you must use sudo or being root

```bash
paperinstall update
```
# Bugs


* Please report all bugs to adam@admlbs.fr


# License

This programm is distribued under GNU General Public License v3.0
