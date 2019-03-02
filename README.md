# ICMP-Tunnel
This POC will involve a C&C server and an agent. Where the C2 server will send the agent commands through an ICMP Tunnel and the agent will return the results, also, through the ICMP Tunnel.

## Note that:
– This POC requires you to install Scapy (https://scapy.readthedocs.io/en/latest/installation.html)

– This POC will not involve handling with fragmentation. Fragmentation will occur, for example, if the answer from the agent will be bigger then the allowed Payload Data size.

## Learn more about ICMP Tunnel!
To understand the concept more clearly, you are welcome to visit the article I wrote -
https://medium.com/bugbountywriteup/ping-power-icmp-tunnel-31e2abb2aaea
