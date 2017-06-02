# Nginx IPv4 to IPv6 Reverse Proxy

Add IPv6 to IPv4 Only Dedicated Server With Nginx IPv4 to IPv6 Reverse Proxy Running On Virtual Server.

````
     A Record                   AAAA Record
+-------------------+     +---------------------+
| Dedicated Server  |====>| Virtual Server      |   ===> Headers and HTML passed
|                   |     | With IPv6 running   |
| With IPv4 Only    |     | Nginx reverse proxy |
| running Apache    |     +---------------------+
| or Nginx          |
+-------------------+ 

````

You'll pass SSL Labs test too : https://www.ssllabs.com/ssltest/analyze.html?d=thecustomizewindows.com&s=2a00%3a6d40%3a40%3a506e%3a0%3a0%3a0%3a1


Described here - https://thecustomizewindows.com/2016/11/add-ipv6-ipv4-server-nginx-reverse-proxy/
