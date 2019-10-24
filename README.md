# lulzer
New python ddoser which is using "shotgun" technique to distribute the http flood through tens of thousands of HTTP/HTTPS/SOCKS4/SOCKS5 proxies. It simulate a real "botnet" attack from ten thousands of uniques source and it supports HTTPS!! It's very useful and worked against GoDaddy's websites and some CloudFlare sites with basic protection.

Example (GoDaddy's site down at the moment and stay down until the attack was stopped):

https://check-host.net/check-report/b444915kbb3


This script is for educationnal purposes only!! Use it on your own responsability.

Requirement:

-bane

to install it:

*windows/termux:

pip install bane

*linux:

sudo pip install bane



Usage:

cd lulzer

python lulzer.py
