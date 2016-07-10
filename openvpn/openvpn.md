# OpenVPN Brainstorming

This is a rough outline of a lesson plan for an introduction to OpenVPN including setup.

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

## Notes

Easy-RSA on Ubuntu is in `/usr/share/easy-rsa`    
Make a CA directory using `make-cadir` - see 

## References

[openvpn.net][openvpn]

Crist, Eric F., and Jan J. Keijser. Mastering Open VPN: Master Building and Integrating Secure Private Networks Using OpenVPN. Birmingham: Packt, 2015. Print.

[openvpn]:https://openvpn.net/index.php/open-source.html

