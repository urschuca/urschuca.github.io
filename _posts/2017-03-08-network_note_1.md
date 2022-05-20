---
title: "Networks notes"
categories:
  - it
tags:
  - it
  - network
  - linux
toc: true
toc_label: "Table of Contents"
---

# Networks notes

__netstat -lnpt | grep LISTEN | grep :port__

__nc -u @ip port__ (sans le -u pour tester en TCP)

__nc -u -l port__ (pour ecouter sur le port)

__tcpdump -i interfaces "filtre"__ (exemple de filtre host ad.re.sse.ip)

__nc -v -u -z -w 3 example.host 20__ (test example host port 20 udp open/closed)

__/sbin/tc qdisc add dev eth0 root handle 1:0 netem delay 20ms__ (ralentit le réseau)


