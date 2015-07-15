# msf-installer
because darkoperator took his down for a reason we haven't found yet


MSF-Installer
=============

Script to help with installing and configuring Metasploit Framework, Armitage and the Plugins I have written on OSX and Linux

##Supported Platforms

The script will install Metasploit Framework and dependencies on:

* OSX Mountain Lion with Apple Java, Xcode and Xcode Command Line Development tools component
* Ubuntu 12.04 and Ubuntu 13.04
* Debian 7.0

On VPS systems where the user is root run the script without the RVM option. 

##Components

The script will install on OSX the following components:

* Homebrew
* Ruby 1.9.3
* PostgresSQL
* Nmap
* Metasploit Framework
* Armitage

On Linux it will installs:

* Developments tools and libraries to support Metasploit Framework and compile Nmap
* Ruby 1.9.3
* PostgresSQL
* Nmap
* Metasploit Framework
* Armitage

## ToDo

* Add Armitage Update script to install process
* Add better comments in to log file.
