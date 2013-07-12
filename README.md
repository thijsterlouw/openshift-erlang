# OpenShift Erlang Cartridge
Experimental Erlang cartridge.


# Cartridge Type
Currently this is a [downloadable cartridge](https://www.openshift.com/developers/download-cartridges).
In the future we want to make this a system cartridge. The advantage of the system cartridge is that
it can install components onto the system. In particular we need to install EPMD and start it.
In order to change it into a system cartridge, we need to add a .spec file.
DIY-type cartridges are not needed anymore, except perhaps as a template.


# Testing scripts
```
./bin/control test
```
