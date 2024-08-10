# ddclient-arm32v7

Tested on rk322x-box Armbian 22.11.1 (Debian 10)

Configs for:

https://www.noip.com

https://desec.io

## pi-hole

If you start a pihole on your home server, possibly you'll face something like this:

````
ddclient-dedyn  | WARNING:  found neither IPv4 nor IPv6 address
ddclient-dedyn  | WARNING:  Could not determine an IP for mydedyn.dedyn.io

ddclient-noip   | WARNING:  found neither IPv4 nor IPv6 address
ddclient-noip   | WARNING:  Could not determine an IP for myddns.ddns.net
````

Don't worry.. just do restart and all will be fine:
````
docker-compose restart
````