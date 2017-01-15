# Brainstorm: Introduction to OpenSSH

## Prerequisites

* backup of any current files in $HOME/.ssh (if it exists)

## Skills, Knowledge, Attitudes

* willingness to learn new things
* some familiarity with the command line
* What is OpenSSH? Where does it come from?
* Why would someone use OpenSSH?
* What can I do with SSH? (log into remote computer, log into local headless computer, hop to other computers, redirect web traffic, view screen of a remote computer, etc. ...need some more examples here)
* What is a client and what is a server?
* Where can I get OpenSSH?
* How do I install OpenSSH?
* How can I tell which version of OpenSSH I am using?
* What is the difference between SSH protocol 1 and SSH protocol 2?
* how does public key encryption work?
* how many keys will I have?
* where do I put my SSH keys?
* is there any required permission mode for my keys or directories inside $HOME/.ssh?
* what is the difference between a public key and a private key?
* where are the configuration files for my SSH client?
* types of ssh keys (RSA, DSA, ed25519, ecdsa)
* how to pick which type of key to make 

> * what type does your remote server allow?
> * concerns with certain types of ssh keys

* parts of an ssh key 

> * file name
> * key type
> * key bits
> * key passphrase
> * key comment - what to put in here

* securing your private ssh key
* passphrase or no passphrase?
* does the remote server see my passphrase? (does my passphrase go outside my computer?)
* what do I type on the command line to access an SSH server?
* how do I load my public ssh key onto the server?
* how can I be sure that the server that I am connecting to is the real server and not some man-in-the-middle? (known_hosts)
* how can I see the fingerprint of an SSH key?
* how can I remove my public key from a server?
* what do I do if my private key gets out in the wild?
* how can I set up different key pairs for each server I want to connect to? 
* how can I configure more than one account on a server I want to connect to?
* what is an SSH identity file?
* how can I configure my SSH client to connect to an SSH server on a non-standard (not port 22) port?
* how do I configure my SSH server to allow me to connect?
* where are the configuration files for my SSH server?
