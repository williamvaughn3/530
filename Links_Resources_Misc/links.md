# Resources and Links

## Interesting and Useful Links 


A.ure Threat Research Matrix](https://microsoft.github.io/Azure-Threat-Research-Matrix/) 

A.versarial Machine Learning Threat Matrix](https://github.com/mitre/advmlthreatmatrix)

I. Model of needs - Modeled after Maslows Heirachy of Needs](https://github.com/swannman/ircapabilities)

W.PS](https://documentation.meraki.com/MR/Monitoring_and_Reporting/Air_Marshal86)

####  Tools 
lightweight, standalone, command-line based TCP egress analyzer for Windows used to test firewall rules
 - 
 e.ress-analyzer(]https://github.com/dodochenpai/egress-analyzer)

Graph Tool
- 
R.und Robin Database Tool](https://oss.oetiker.ch/rrdtool/).

Flow collecter and Analyzer
- NFdump  http://nfdump.sourceforge.net/     
- NfSen https://sourceforge.net/projects/nfsen/

Network Conf Stig Checker
- https://github.com/syn-4ck/pynipper-ng?tab=readme-ov-file
    - Old

- Uiversity of Wisconsin for their excellent summary of IPv6 tools. 

h.tps://kb.wisc.edu/ns/page.php?id=12364]("Network Troubleshooting Tools, IPv4, and IPv6. )

#### single out the IPv6 addresses, we will do an extended grep with a regular expression. The regex is:
```sh
((
0.9a-fA-F]{1,4}:){7,7}
0.9a-fA-F]{1,4}|(
0.9a-fA-F]{1,4}:){1,7}:|(
0.9a-fA-F]{1,4}:){1,6}:
0.9a-fA-F]{1,4}|(
0.9a-fA-F]{1,4}:){1,5}(:
0.9a-fA-F]{1,4}){1,2}|(
0.9a-fA-F]{1,4}:){1,4}(:
0.9a-fA-F]{1,4}){1,3}|(
0.9a-fA-F]{1,4}:){1,3}(:
0.9a-fA-F]{1,4}){1,4}|(
0.9a-fA-F]{1,4}:){1,2}(:
0.9a-fA-F]{1,4}){1,5}|
0.9a-fA-F]{1,4}:((:
0.9a-fA-F]{1,4}){1,6})|:((:
0.9a-fA-F]{1,4}){1,7}|:)|fe80:(:
0.9a-fA-F]{0,4}){0,4}%
0.9a-zA-Z]{1,}|::(ffff(:0{1,4}){0,1}:){0,1}((25
0.5]|(2
0.4]|1{0,1}
0.9]){0,1}
0.9])\.){3,3}(25
0.5]|(2
0.4]|1{0,1}
0.9]){0,1}
0.9])|(
0.9a-fA-F]{1,4}:){1,4}:((25
0.5]|(2
0.4]|1{0,1}
0.9]){0,1}
0.9])\.){3,3}(25
0.5]|(2
0.4]|1{0,1}
0.9]){0,1}
0.9]))
```

- Source IP addresses logged in all conn.log files stored in that directory:
`zcat conn* | jq -j '.
".d.orig_h"], "\n”`

- Free IPv6 Tunnel service
Hurricane Electric http://he.net

- RasberryPi Setup IPv6 Tunnel
RaspberryPi: https://www.raspberrypi.org/forums/viewtopic.php?f=36&t=880541

Palo Alto provides a guide on how DNS sinkholing works here: https://docs.paloaltonetworks.com/pan-os/9-1/pan-os-admin/threat-prevention/use-dns-queries-to-identify-infected-hosts-on-the-network/dns-sinkholingSimilarly,

Cisco provides similar capabilities on ASA with FirePOWER module described here:https://www.cisco.com/c/en/us/support/docs/security/asa-5500-x-firepower-services/213284-configure-the-domain-based-security-inte.html#:~:text=The%20sinkhole%20can%20be%20configured,IP%20address%20of%20sinkhole%20server.

#### Firewall Rule ANalysis Tools
- 1 https://www.algosec.com/
- 2 https://tufin.com/

### DNS anamolous
https://github.com/jbaggs/anomalous-dns

### Kube Sidecar and network vis
https://corelight.com/blog/deeper-visibility-into-kubernetes-environments-with-network-monitoring
https://corelight.com/blog/sidecars-for-network-monitoring


### JA3 Suricata: 
https://www.trustwave.com/en-us/resources/blogs/spiderlabs-blog/inspecting-encrypted-network-traffic-with-ja3/****

### Zeek Analysis Toolkit, 
https://supercowpowers.github.io/zat/

####  Anomaly based IDS using ML
 https://medium.com/hootsuite-engineering/anomaly-based-intrusion-detection-system-using-machine-learning-a18e88694ce0


 #### Insights on how to use Zeek to detect MITRE ATT&CK techniques:
 https://www.giac.org/paper/gcia/13981/methods-employ-zeek-detecting-mitre-att-ck-techniques/177454

 DHCP Fingerprinting:  https://fingerbank.org/
 
 ## fwknop   
 opensource SPA, uses asymmetric keys and an HMAC to transmit a single packet that authenticates a device securely. This packet is composed of the following message composition:<br> 16 bytes of random data; local username; local timestamp; fwknop version; mode (access or command); desired access (or command string); MD5 sum  
http://www.cipherdyne.org/fwknop/docs/SPA.html  
 http://www.cipherdyne.org/fwknop/  
 https://www.kitploit.com/2019/02/fwknop-single-packet-authorization-port.html  

### Honey Pots: 
https://www.activecountermeasures.com/free-tools/adhd/
https://github.com/telekom-security/tpotce


###  Honey Tokens 
1. https://github.com/gentilkiwi/mimikatz
2. https://www.dshield.org/diary/Detecting%2BMimikatz%2BUse%2BOn%2BYour%2BNetwork/19311
3. https://github.com/SMAPPER/MimikatzHoneyToken
4. https://www.autoitscript.com/site/autoit/
5. https://github.com/secureworks/dcept
CanaryTokens.org
