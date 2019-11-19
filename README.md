# L24-RC-IMUNES   
L24 Laboratory network simulation using IMUNES

* Git mirror: https://git.ecomaikgolf.com/L24-RC-IMUNES
* Preconfigured OVA: https://url.ecomaikgolf.com/L24-RC-IMUNES
* Credits to: http://imunes.net/

## Installation
### I don't have IMUNES <--
Download a preconfigured IMUNES (770M) `.ova` from [here](https://url.ecomaikgolf.com/L24-RC-IMUNES) and open it with VirtualBox.

**GUI**: Open VirtualBox > Press `Ctrl+I` > Search for `L24.ova`   
**CLI**: `vboxmanage import L24.ova`   
   
**Usage**: Run the VM and open `GUIA`    
**Tips**: Use `man ping` or `man traceroute` to view the documentation

### I already have IMUNES
Clone the repo and open `L24.imn` with IMUNES

## Features
### Control the entire network
![](1.png)
### Open a terminal in any machine/router
![](2.png)
### ~0% Noise
![](3.png)
### Wireshark in every ethernet segment
![](4.png)
### Easy to use
![](5.png)

## Notes
* Network performance is not the same (but max. speed is)
* Linux 2 does not have a remote command service
* VM does not have internet access (disabled)
* Linux/Windows commands differ! Revise the Windows syntax before the exam.
* Rely on IPv4 only
* To test TCP/IP use `nc -l PORT` in one machine (server) and `nc IP PORT (-O maxSize)` in another
