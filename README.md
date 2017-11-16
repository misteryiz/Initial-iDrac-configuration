# Initial iDrac configuration on Dell PowerEdge R620/R730 servers.
**Please use this as a guide when you setup a Dell PowerEdge server and mount that into a rack initially. Default, when you connect the network cables, iDrac will issue a self assigned ip : 192.168.0.120. We can chnage this to the required IP assuming that the IP space available and the network / switches are configured properly.**

> * iDRAC (Integrated Dell Remote Access Card) configuration utility is accessed at boot time, and is useful when installing a new PowerEdge server. 
> * iDRAC alerts you when an issue occurs, enables streamlined local and remote server management, and reduces or eliminates the need for administrators to physically visit the server.

```diff
- Initial Setup:
+ This assumes that the personnel should have physical access to the server in the data center. 
+ You should also have access to a monitor and keyboard. Another assumption is that the server 
+ is rack mounted and all the power cables as well as network cables are connected properly.
``` 
