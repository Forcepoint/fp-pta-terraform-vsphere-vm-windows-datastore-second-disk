# vsphere-vm-windows-datastore-second-disk Terraform Module

This contains an abstracted resource for creating a virtual machine with a Windows OS
on a datastore instead of a datastore cluster, with a second disk attached to it.
See https://www.terraform.io/docs/providers/vsphere/r/virtual_machine.html

See the [variables.tf](variables.tf) file for descriptions of each variable. If default is not listed,
the variable is required. If a default is null, Terraform behaves as though you had completely 
omitted it.

Minimum Terraform Version: 0.12