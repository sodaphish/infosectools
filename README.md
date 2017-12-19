#Infosec Tools


To find country-wide IP blocks:  ftp://ftp.ripe.net/pub/stats
To find networks advertised by an AS: http://bgp.potaroo.net/cgi-bin/as-report?as=AS11232

##Collections of smaller tools:

    http://www.woanware.co.uk/
    http://www.monkey.org/~dugsong/dsniff/
    http://www.nirsoft.net/


dpkg’s for clean installs: losf, chkconfig, htop, zmap, screen, nap, hping3, iftop, sslscan, hydra, 

##Reconn

    DNSA-NG — DNS subdomain brute-forcing tool (http://packetfactory.openwall.net/projects/dnsa/index.html)
    Maltego — http://www.paterva.com/web7/buy/maltego-clients.php
    recon-ng -- 


##Packeting

    nmap — port scanner and OS finger-printer (required for OpenVAS)
    hping3 — packet crafter 
    zmap -- port scanner on steroids (https://zmap.io)
    masscan — zmap alternative (https://github.com/robertdavidgraham/masscan)
    gspoof — easy packet crafter command-line tool (http://gspoof.sf.net)
    yersinia — L2 attack framework (http://www.yersinia.net/)
    voiphopper — VoIP VLAN hopping tool (http://voiphopper.sf.net)
    scapy — python library for scripting your own tools
    marvin — 802.1x defeater! (http://www.gremwell.com/marvin-mitm-tapping-dot1x-links)


##Password Crackers

    hydra — multi-protocol password cracker
    medusa — hydra with more supported protocols but some bugs. (https://github.com/jmk-foofus/medusa)
      medusa -h 10.151.9.215 -P /root/pwlist.txt -M vnc -u any 
    john — password cracker for /etc/secure files
    mimikatz — windows LSA and SAM attacker
    LaZagne — windows app password cracker (http://www.darknet.org.uk/2015/12/lazagne-password-recovery-tool-windows-linux/)
    hashcat — password cracker that is better than John
    cewl — ruby script for generating word lists from websites (https://digi.ninja/projects/cewl.php)
    maskprocessor — wordlist generator with wicked sweet capabilities (https://github.com/hashcat/maskprocessor)


##Vulnerability Scanners

    Nexpose ($)
    Nessus ($)
    OpenVAS/Greenbone
    Retina ($)
    GFI LanGuard ($)


##Configuration Auditors

    Nipper/PAWS ($)
    Netwrix (www.crowd-auditing.org/free_tools.html)
    Privilege Authority (www.scriptlogic.com)


##Web-Application Scanners

    BurpSuite ($)
    nikto — application scanner; required for OpenVAS
    zap (OWASP ZAP)
    dirb — directory finder; required for OpenVAS
    arachni — application scanner; required for OpenVAS
    wapiti — application scanner; required for OpenVAS
    bettercap — http/https MITM framework/proxy (http://bettercap.org/)


##Certificate Validation/Checking

    sslscan — ssl scanner that is EXCELLENT at telling you all the supported cipher suites and other features. (https://www.titania.com/freetools)
    sslyze — ssl scanner that can also be used as a library (https://github.com/nabla-c0d3/sslyze)


##Fuzzers

    Peach ($)
    https://github.com/blazeinfosec/pcrappyfuzzer 


##Exploit Tools

    Metasploit ($)
    ExploitPack Pro
    Cobalt Strike ($)
    ngrok — publishes private services to the internet


##Phishing

    LUCY (www.phishing-server.com)
    GoPhish (https://github.com/gophish/gophish) — all inclusive phishing platform, works great!
    CobaltStrike 2 ($)
    SpiderLabs Responder (https://github.com/SpiderLabs/Responder) — has multiple responder services that will detect rouge connections


##Collaboration

    Dradis
    CobaltStrike 3 ($)


##Logging

    Syslog
    Netwrix Event Log Manager
    Kiwi syslog
    syslog-ng
    ELK — Elastic, LogStash and Kibana stack for log processing/hunting
    RITA (https://www.blackhillsinfosec.com/?page_id=4417) — built on ELK 
    Bro (https://www.bro.org) — netflow processor for RITA


##DDoS/Network Stress Testing

    http://nutsaboutnets.com/netstress/
    http://totusoft.com/lanspeed/
    https://linhost.info/2010/02/iperf-on-windows/


##Reversing

    IDA (https://www.hex-rays.com/products/ida/index.shtml) — interactive disassembler and debugger
    OllyDbg (http://www.ollydbg.de/download.htm) — another debugger
    Binary.ninja (https://binary.ninja/purchase.html)


##Software Defined Radio

    SDR# (http://www.sdrsharp.com) - best SDR UX
    rtl-sdr (http://www.rtl-sdr.com) - backend drivers for SDR on Linux, including rtlsdrtcp, an SDR server for SDR#











User-land tools

    Remmina — *nix desktop sharing (http://www.remmina.org/wp/)
