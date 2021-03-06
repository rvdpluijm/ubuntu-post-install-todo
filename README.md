ubuntu-post-install-todo
========================

My task list after intalling Ubuntu 14.04

* [ ] `sudo ufw enable`
* [ ] `sudo apt-get install ubuntu-restricted-extras vim git gdebi-core autoconf bison build-essential libssl-dev libyaml-dev libreadline6 libreadline6-dev zlib1g zlib1g-dev libgsl0-dev curl python-gpgme gnucash python-dev python-pip ruby ruby-dev kdiff3-qt synaptic`
* [ ] `Voorkeuren` -> `Automatisch aanmeldgegevens invullen`, bij geavanceerd `Zoeken naar ...` uitzetten
* [ ] Fire Gestures, disable all but `Muis gebaren`
* [ ] install [HTML validator](http://users.skynet.be/mgueury/mozilla/index.html), choose serial and disable it by default after installation
* [ ] `System settings`
* [ ] `Helderheid en vergrendelen` -> disable `Pauzestand`, `Mijn wachtwoord vereisen ...`
* [ ] `Software & Updates` -> `Extra stuurprogramma's` enable tested binary driver
* [ ] [generate ssh](https://help.github.com/articles/generating-ssh-keys/) -> [add ssh](https://github.com/settings/ssh)
* [ ] `git config --global user.name "Remko van der Pluijm"` -> `git config --global user.email "remkop@gmail.com"` -> `git config --global core.editor nano` -> `git config --global merge.tool kdiff3`
* [ ] [git-up](https://github.com/aanand/git-up#install)
* [ ] [virtualbox](https://www.virtualbox.org/wiki/Linux_Downloads#Debian-basedLinuxdistributions)
 * [ ] `sudo ufw allow from 192.168.1.0/24` <- lan ip range
  * [ ] before installing `sudo apt-get install python-gpgme`
* [ ] [gimp](http://www.gimp.org/)
 * [ ] `sudo add-apt-repository ppa:otto-kesselgulasch/gimp`
 * [ ] `sudo apt-get update`
 * [ ] `sudo apt-get install gimp`
 * [ ] `bewerken` -> `voorkeuren` -> `interface` -> `taal` = `Engels [en_US]` -> restart gimp
 * [ ] `window` -> `single window mode`
* [ ] [git-cola](https://github.com/git-cola/git-cola#run-from-source)
* [ ] [thefuck](https://github.com/nvbn/thefuck#manual-installation)
* [ ] [vmware horizon view client] `sudo apt-get install vmware-view-client`
* [ ] remove [Ubuntu Unity]: `sudo apt-get remove unity unity-asset-pool unity-control-center unity-control-center-signon unity-gtk-module-common unity-lens* unity-services unity-settings-daemon unity-webapps* unity-voice-service`
* [ ] install [gnome3]: `sudo apt-get install ubuntu-gnome-desktop` / `sudo service gdm restart`
* [ ] install Trelby (screenwriter software): `wget http://www.trelby.org/files/release/2.2/trelby_2.2_all.deb
