# Identifying-IT-assets-in-a-network


# PROJECT  SPECIFICATIONS:


The interface is used to display a list of machines within the range of provided IP addresses in a single web page wherein each machine will be represented by a button or hyperlink text using colour codes to distinguish each machine by OS and Up/Down Status.
Further on clicking any of the button or hyperlink representing a machine, following information about that particular machine appears:

Host name
OSname and version details
Processor details
RAM capacity
Video card details, if any
Local file system/disk drives
Mounted network file systems
Available Users
Attached Devices
System Serial Number


# Necessary requirements for the project

Firewall of all the hosts and the server being used in this network should be turned off
                                  OR
Necessary inbound and outbound rules must be defined so as to allow:

WMI commands (for windows to windows access/ linux to windows access)
SSH commands (for host linux or unix access)-> Implemented using Mobaxterm

If the server computer is a windows running system then it should have a ssh server installed on it.
This project uses a GUI based SSH tool called MOBAXTERM to set up a remote connection with a linux or a linux based system.
For windows to windows access there is no need for a ssh server running on the system.
All the computers should be on the same network
All the computers must have the same credentials:
example:
Username- abc
Password- abc
As used in the code provided
