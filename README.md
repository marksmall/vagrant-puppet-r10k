# Puppet r10k example

Example code to go along with tutorial that details [how to build a Puppet repo using r10k with roles and profile](https://techpunch.co.uk/development/how-to-build-a-puppet-repo-using-r10k-with-roles-and-profiles).


## Notes on getting it working

Need to add vagrant plugin to install vbguest to install virtualbox guest additions `vagrant plugin install vagrant-vbguest`.

Link **Vagrant** with you **Control repo** `cd vagrant && ln -s ../control-repo/ puppet`