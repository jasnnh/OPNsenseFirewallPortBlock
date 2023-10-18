# OPNsenseFirewallPortBlock
Configuring OPNsense to block ports 443, 80, ICMP &amp; any TCP.

Go to Firewalls > Rules > WAN add a new rule above the default TCP rules and in this case we can set ports 443, 80, 21 all or any TCP of our choosing in this case i blocked RDP and Telnet and then later added FTP port 21 to the list.

![Screenshot](https://github.com/jasnnh/OPNsenseFirewallPortBlock/blob/main/image6.png)

You can view the logs in realtime by navigating to Firewall > Liveview to see the logs of the port being blocked.

![Screenshot](https://github.com/jasnnh/OPNsenseFirewallPortBlock/blob/main/image5.png)

