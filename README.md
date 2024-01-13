# Convert-VMDK-to-VDI

The VBoxManage command is the Swis Army Knife of tools to manage all things VirtualBox. The VBoxManage command will need to be in your path to be able to use it..

Go to the destination folder where the VMDK file is. then open cmd with administrative permission and run the below command --

<h3> VBoxManage clonehd --format VDI server1-disk1.vmdk server2-disk1.vdi </h3>

In the above example, change server1-disk1.vmdk to your input VMDK disk and server2-disk1.vdi to the path you’d like to store the ouput VDI.
