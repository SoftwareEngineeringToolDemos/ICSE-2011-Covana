### How to build a windows VM with Visual Studio 2010 installed:

  1.  Download and install [VirtualBox] (https://www.virtualbox.org/wiki/Downloads)
  2.  Download and install [Vagrant] (https://www.vagrantup.com/downloads.html)
  3.  Clone this repoitory:
         https://github.com/SoftwareEngineeringToolDemos/ICSE-2011-Covana.git
  5.  Navigate to the build-vm folder of the cloned repository on your host machine
  6.  Run *vagrant up* to set up the vm. This would do following:
  
        a.Download and add the base box image in Vagrant. Adding the base box would remove the need for further downloads when the box is brought up at a later point of time.

        b. Create virtual machine using this image.
        
        c. Launch windows vm with GUI.
        
        d. Connect to it using WinRM
        
        e. Make a folder for Visual Studio, download the trial version's ece and install it.
        
## Acknowledgements
I would like to thank the uploader of the windows basebox "datacastle/windows7" for making it availble on vagrant cloud.
