# Python malware.

##### Discoluser 

###### This project has been created with the premise of learning and awareness of the power of python.

###### We are not responsible for any possible malicious use.

Python malware provides an example of the source code of a client/server malicious application that allows you to take remote control of one or more assets over HTTP protocol.

That kind of malware is also named a reverse shell or backdoor.

Our example is split into two principals file: 

- Client-side code, that have as principal function infects the victim machine and requests a reverse HTTP session to our C2 server, in the same way, our client performs tasks such as exfiltrating files, receiving incoming files from our C2 server, or simply taking screenshots of our target, to later be shared over the same HTTP session to our C2 server.

- Command and Control server or server-side code , which provides you the capability to send and receive commands through standard input and output, manage the session between our C2 server and the victim machine, send and receive files to our client, or handle multiple sessions like a botnet.  
