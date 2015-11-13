###Please follow these steps to spin up a virtual machine for MDSheet using vagrant script:
1. Download and Install [Vagrant](https://www.vagrantup.com/downloads.html) on the host machine.
2. Download and Install [Virtual Box](https://www.virtualbox.org/wiki/Downloads) on the host machine.
2. Download the [Vagrantfile](https://github.com/SoftwareEngineeringToolDemos/ICSE-2012-MDSheet/blob/master/build-vm/Ubuntu14.04/Vagrantfile) from [build-vm](https://github.com/SoftwareEngineeringToolDemos/ICSE-2012-MDSheet/tree/master/build-vm/Ubuntu14.04) directory to your machine.
3. In order to clone the private repository of author from [bitbucket](https://bitbucket.org/), you need to get access from the author on request and change the [input](https://github.com/SoftwareEngineeringToolDemos/ICSE-2012-MDSheet/blob/master/build-vm/Ubuntu14.04/input) file accordingly by adding the credentials. 
4. In the host machine, cd into the directory that contains the Vagrantfile and run the command `"vagrant up"`.
5. The command `"vagrant up"` will create a Ubuntu 14.04 VM with all the prerequisite dependencies installed in it to run the "embedding" and "co-evolution" features.

###Note:
* The VM boots up quickly and can be viewed from VirtualBox. But the "vagrant up" command runs up approximately for 15-20 minutes.
* VM Login Details:

 ` Username: vagrant`
  
  `Password: vagrant`

###Acknowledgements:
Used vagrant virtual box image of [32 bit Ubuntu 14.04](https://atlas.hashicorp.com/ubuntu/boxes/trusty32).

###References:
[Vagrant Documentation](https://docs.vagrantup.com/v2/getting-started/)

[Vagrant Blog](https://www.vagrantup.com/blog.html)

[Ubuntu Trusty32 Virtual Box](https://atlas.hashicorp.com/ubuntu/boxes/trusty32)
