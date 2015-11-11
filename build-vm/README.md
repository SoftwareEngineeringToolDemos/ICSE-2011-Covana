### How to build a windows VM with Visual Studio 2010 installed:

  1.  Download and install VirtualBox.
  2.  Download and install Vagrant.
  3.  Clone this repoitory to your preferred location.
  4.      git clone https://github.com/SoftwareEngineeringToolDemos/FSE-2012-SecuriTAS.git
  5.  Open command line and navigate to the bulild-vm folder of the cloned repository.
  6.  Run vagrant up to set up the vm. This would do following:
        Download and add the base box image in Vagrant. Adding the base box would remove the need for further downloads 
        when the box is brought up at a later point of time.
        Create virtual machine using this image.
        Launch VM in GUI mode.
        Connect to it using WinRM
        Make a folder for Visual Studio, download the trial version's ece and install it.
