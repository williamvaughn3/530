# Resources and Links

## Interesting and Useful Links 

[Azure Threat Research Matrix](https://microsoft.github.io/Azure-Threat-Research-Matrix/) 
[Adversarial Machine Learning Threat Matrix](https://github.com/mitre/advmlthreatmatrix)
[IR Model of needs - Modeled after Maslows Heirachy of Needs](https://github.com/swannman/ircapabilities)
[WIPS](https://documentation.meraki.com/MR/Monitoring_and_Reporting/Air_Marshal86)

####  Tools 
lightweight, standalone, command-line based TCP egress analyzer for Windows used to test firewall rules
 - [egress-analyzer(]https://github.com/dodochenpai/egress-analyzer)

Graph Tool
- [Round Robin Database Tool](https://oss.oetiker.ch/rrdtool/).

Flow collecter and Analyzer
- NFdump  http://nfdump.sourceforge.net/     
- NfSen https://sourceforge.net/projects/nfsen/

Network Conf Stig Checker
- https://github.com/syn-4ck/pynipper-ng?tab=readme-ov-file
    - Old

- Uiversity of Wisconsin for their excellent summary of IPv6 tools. 
[https://kb.wisc.edu/ns/page.php?id=12364]("Network Troubleshooting Tools, IPv4, and IPv6. )

#### single out the IPv6 addresses, we will do an extended grep with a regular expression. The regex is:
```sh
(([0-9a-fA-F]{1,4}:){7,7}[0-9a-fA-F]{1,4}|([0-9a-fA-F]{1,4}:){1,7}:|([0-9a-fA-F]{1,4}:){1,6}:[0-9a-fA-F]{1,4}|([0-9a-fA-F]{1,4}:){1,5}(:[0-9a-fA-F]{1,4}){1,2}|([0-9a-fA-F]{1,4}:){1,4}(:[0-9a-fA-F]{1,4}){1,3}|([0-9a-fA-F]{1,4}:){1,3}(:[0-9a-fA-F]{1,4}){1,4}|([0-9a-fA-F]{1,4}:){1,2}(:[0-9a-fA-F]{1,4}){1,5}|[0-9a-fA-F]{1,4}:((:[0-9a-fA-F]{1,4}){1,6})|:((:[0-9a-fA-F]{1,4}){1,7}|:)|fe80:(:[0-9a-fA-F]{0,4}){0,4}%[0-9a-zA-Z]{1,}|::(ffff(:0{1,4}){0,1}:){0,1}((25[0-5]|(2[0-4]|1{0,1}[0-9]){0,1}[0-9])\.){3,3}(25[0-5]|(2[0-4]|1{0,1}[0-9]){0,1}[0-9])|([0-9a-fA-F]{1,4}:){1,4}:((25[0-5]|(2[0-4]|1{0,1}[0-9]){0,1}[0-9])\.){3,3}(25[0-5]|(2[0-4]|1{0,1}[0-9]){0,1}[0-9]))
```

- Source IP addresses logged in all conn.log files stored in that directory:
`zcat conn* | jq -j '.["id.orig_h"], "\n”`

- Free IPv6 Tunnel service
Hurricane Electric http://he.net

- RasberryPi Setup IPv6 Tunnel
RaspberryPi: https://www.raspberrypi.org/forums/viewtopic.php?f=36&t=88054[1