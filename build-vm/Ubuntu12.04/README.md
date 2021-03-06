###Please follow these steps to spin up a virtual machine for MDSheet using vagrant script:
1. Download and Install [Vagrant](https://www.vagrantup.com/downloads.html) on the host machine.
2. Download and Install [Virtual Box](https://www.virtualbox.org/wiki/Downloads) on the host machine.
2. Download the [Vagrantfile](https://github.com/SoftwareEngineeringToolDemos/ICSE-2012-MDSheet/blob/master/build-vm/Ubuntu12.04/Vagrantfile) from [build-vm](https://github.com/SoftwareEngineeringToolDemos/ICSE-2012-MDSheet/tree/master/build-vm/Ubuntu12.04) directory to your machine.
3. In the host machine, cd into the directory that contains the Vagrantfile and run the command `"vagrant up"`.
4. The command `"vagrant up"` will create a Ubuntu 12.04 VM with all the prerequisite dependencies installed in it to run the "inference" feature.

###Note:
* The VM boots up quickly and can be viewed from VirtualBox. But the "vagrant up" command runs up approximately for 15-20 minutes.
* VM Login Details:

 ` Username: vagrant`
  
  `Password: vagrant`

###Acknowledgements:
Used vagrant virtual box image of [32 bit Ubuntu 12.04](https://atlas.hashicorp.com/ubuntu/boxes/precise32).

###References:
[Vagrant Documentation](https://docs.vagrantup.com/v2/getting-started/)

[Vagrant Blog](https://www.vagrantup.com/blog.html)

[Ubuntu Precise32 Virtual Box](https://atlas.hashicorp.com/ubuntu/boxes/precise32)
