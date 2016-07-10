# OpenVPN Brainstorming

This is a rough outline of a lesson plan for an introduction to OpenVPN including setup.

## Audience

Desktop computer users wanting to avoid snooping of traffic when using an access point they don't control. Examples of this include:

* surfing from a friend's house
* wireless access at an airport or coffee shop
* accessing the internet while visiting another company

Instructions will be provided for users of Unix-like operating systems.

## Skills, Knowledge, Attitudes

### Prerequisite knowledge

* familiar with Unix command line
* know difference between TCP and UDP
* know what an RFC is
* know where to find RFCs
* know encryption basics (TLS, ciphers, etc.)
* know basic ip networking

### Knowledge items

* know the purpose of a VPN
* know the scenarios where a VPN would be useful
* know the different types of VPN
* know the pros/cons of OpenVPN
* know the license of OpenVPN community version (and `openvpn-as` commercial version)
* know the ports through which OpenVPN operates
* know that the community (open source) version can be a VPN client and a VPN server
* know limitations and benefits of the commercial version
* know where to find the OpenVPN mailing list, IRC, and forums
* know how to install on unix-like system
* know how to install on Windows
* know how to install on smart phone
* know the difference between point-to-point mode and client/server mode
* know the meaning of Perfect Forward Secrecy (PFS)
* know how to achieve Perfect Forward Secrecy in OpenVPN (X.509 certificates over pre-shared keys)
* know that a tap can carry all kinds of traffic and a tun carries only IP traffic
* know the flow of information from the application --> tun --> OpenVPN --> ethernet adapter
* know which transport protocol (TCP or UDP) to use with the VPN
* know the purpose of the `ta.key`
* know the 2 channels OpenVPN uses for client-server communication (control and data channel)
* know the meaning of OpenVPN `tap` mode

## Installation

* check to see if OpenVPN is already installed:

	$ which openvpn

If this returns a directory, openvpn is already installed. If OpenVPN is already installed, check the version:

	$ openvpn --version

If OpenVPN is not already installed, install it. On Ubuntu 14.04 and 16.04 you can install OpenVPN using the built-in software package manager by typing:

	$ sudo apt-get install openvpn

On Ubuntu, the package manager will install OpenVPN in the `/usr/sbin/openvpn` directory. Configuration files for OpenVPN will be in the `/etc/openvpn` directory.

Next you will install Easy-RSA to help create certificates.

* Go to the Easy-RSA GitHub [releases][easyrsa] section.     
* Scroll down to the **Downloads** section and click on the file named **EasyRSA-3.X.X._tgz_**



## Notes

Easy-RSA on Ubuntu is in `/usr/share/easy-rsa`    
Make a CA directory using `make-cadir` - see 

## References

[openvpn.net][openvpn]

Crist, Eric F., and Jan J. Keijser. Mastering Open VPN: Master Building and Integrating Secure Private Networks Using OpenVPN. Birmingham: Packt, 2015. Print.

[openvpn]:https://openvpn.net/index.php/open-source.html
[easyrsa]:https://github.com/OpenVPN/easy-rsa/releases
