# Vagrant project for mininet / valve / ryu

Launch an Ubuntu 15.04 32 bit server VM with the following packages:

- Mininet: http://mininet.org/
- Valve: https://github.com/openvapour/valve
- Ryu: https://github.com/osrg/ryu

First time Vagrant will update all packages and install the latest patches.

### Getting Started

Install Virtual Box: https://www.virtualbox.org/

Install Vagrant: http://www.vagrantup.com

- Clone this project

- Refresh git submodule

```
git submodule init
git submodule update
```

- Launch VM the first time

```
vagrant up
vagrant reload
```

`./valve` folder is mirrored in the VM `/home/vagrant/valve`

`./projects` folder is mirrored in the VM to `/home/vagrant/projects`

- Login in Vagrant VM

```
vagrant ssh
```
