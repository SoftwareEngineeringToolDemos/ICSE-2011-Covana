### How to build a Windows VM with Covana installed:

  1.  Download and install [VirtualBox] (https://www.virtualbox.org/wiki/Downloads)
  2.  Download and install [Vagrant] (https://www.vagrantup.com/downloads.html)
  3.  Clone this Repository
  4.  Navigate to the build-vm folder of the cloned repository on your host machine
  5.  Run *vagrant up* to set up the vm. This would do following:

        a.Download and add the base box image in Vagrant. Adding the base box would remove the need 
        for further downloads when the box is brought up at a later point of time.

        b. Create virtual machine using image.

        c. Launch Winodws VM, if dialog box asks for restart, choose restart later.

        d. Install Visual Studio, Pex, Covana and downloads files such as installation, youtube video link etc.

  6.  You can also use the following credentials to log in to the system:
      *  Username: vagrant
      *  Password: vagrant
      
### NOTE: vagrant up takes 30-40 mins to complete.
## References
  *  [Vagrant shell documentation] (https://docs.vagrantup.com/v2/provisioning/shell.html)

## Acknowledgements
I would like to thank the uploader of the windows basebox "datacastle/windows7" for making it available on vagrant cloud.

NOTE: For Visual Studio to open on startup, the VM should be restarted. Since the vagrant reload provisioner is throwing errors (even after the script installs the reload provisioner), it has been commented in the Vagrant script. It is advised that you restart the VM after all provisioning (provisioning sets up VS to open on startup) is done if you want Visual Studio to open on start up. else, try manually installing the realod provisioner and uncomment the reload line i nthe VagrantFile. 
