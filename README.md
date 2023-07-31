* What is a virtual machine ?
a virtual machine is a virtual instance created by an emulation software on a real machine, this instance can perform closely the same as a real machine depending on the performance of the real one.

* What is Vagrant ?
as we talked on the previous question about the emulation software that creates virtual machines, Vagrant is one of these softwares, it helps create virtual environnements for developement in a single workflow

* Who wrote Vagrant ?
Mitchell Hashimoto

* What is Ubuntu ?
Ubuntu is an Operating System GNU/Linux and Based on Debian which is Linux distribution.

* What does “Ubuntu” mean ?
word "Ubuntu" is issued from the Bantoues Afrivan languages which means " Humanity and Fraternity "

* How to use VMs with Vagrant ?
 on your linux machine write these commands : 
-----------------------------------------------------------------------------------------
#mkdir vargant && cd vargant && vargant init ubuntu/xenial64

//Output : A `Vagrantfile` has been placed in this directory. You are now
//ready to `vagrant up` your first virtual environment! Please read
//the comments in the Vagrantfile as well as documentation on
//`vagrantup.com` for more information on using Vagrant.

#vargant up

//Output : Bringing machine 'default' up with 'virtualbox' provider...
==> default: Box 'ubuntu/xenial64' could not be found. Attempting to find and install...
    default: Box Provider: virtualbox
    default: Box Version: >= 0
==> default: Loading metadata for box 'ubuntu/xenial64'
    default: URL: https://vagrantcloud.com/ubuntu/xenial64
==> default: Adding box 'ubuntu/xenial64' (v20200822.0.0) for provider: virtualbox
    default: Downloading: https://vagrantcloud.com/ubuntu/boxes/xenial64/versions/20200822.0.0/providers/virtualbox.box
    default: Download redirected to host: cloud-images.ubuntu.com

#vargant ssh

//Output : Welcome to Ubuntu 16.04.7 LTS (GNU/Linux 4.4.0-187-generic x86_64)

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 * Support:        https://ubuntu.com/advantage


0 packages can be updated.
0 updates are security updates.

New release '18.04.5 LTS' available.
Run 'do-release-upgrade' to upgrade to it.

-----------------------------------------------------------------------------------------------

* What does the command "uname" do
it write the name, version and details about current machine
