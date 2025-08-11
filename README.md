# Task-5
packet capturing and analyzing 

to start capturing using Wireshark, choose a active network interface: for ethernet - choose eth0 and for wifi - choose wlan0

click on the shark fin icon to start capturing 

To generate a network traffic, visit any website, preferably http

click the red square in order to stop capturing the packets

stepts performed:

captured live packets from active interface,  
generated traffic by browsing or pinging servers, 
filtered and identifed the protocol 

http, tcp and dns are the three protocols found

With HTTP, DNS is visible and TCP payload shows actual requests (e.g., “GET /index.html”) and responses (HTML, CSS, JS). When you visit an HTTPS website, you’ll still see DNS and TCP activity in Wireshark — but what you see is different from HTTP because the actual web content is encrypted.


