# Vagrant project for mininet / valve / ryu

Launch an Ubuntu 14.04 server VM with the following packages:
- Mininet: http://mininet.org/
- Valve: https://github.com/openvapour/valve
- Ryu: https://github.com/osrg/ryu

First time update all packages and install the latest patches.

### Getting Started

- Install Vagrant

- Clone this project

- Refresh git submodule

```   
git submodule update
```

- Launch VM the first time

```
vagrant up --provision
vagrant reload
```

`./valve` folder is mirrored in the VM `/home/vagrant/valve`

`./projects` folder is mirrored in the VM to `/home/vagrant/projects`

- Login in Vagrant VM

```
vagrant ssh
```
