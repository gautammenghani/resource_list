# Pentesting
### Common tools and misc resources
  * Payloads : https://github.com/swisskyrepo/PayloadsAllTheThings
  * jwt-cracker : https://github.com/lmammino/jwt-cracker
  * SSTI reference : https://github.com/DiogoMRSilva/websitesVulnerableToSSTI
  * Convert IP to decimal/hexadecimal : https://gist.github.com/mzfr/fd9959bea8e7965d851871d09374bb72
  * ZAP	
    * Forum : https://groups.google.com/forum/#!forum/zaproxy-users 
    * Short videos : https://www.alldaydevops.com/zap-in-ten
    * UI overview : https://www.zaproxy.org/docs/desktop/ui/
  * SSH
    * https://www.digitalocean.com/community/tutorials/ssh-essentials-working-with-ssh-servers-clients-and-keys
  * XSS resources
    * List of resources : xss-payloads.com

### Scanning and Enumeration
  * nbtscan : tool that scans for open NETBIOS nameservers on a local or remote server
  * rpcclient : a utility initially developed to test MS-RPC functionality in Samba itself
  * snmpenum : enumerate snmp

### Linux privesc
  * https://github.com/rebootuser/LinEnum
  * GTFOBins : https://gtfobins.github.io/
  * Check what cmnds can I ran as sudo : sudo -l	
  * Find files with suid bit set : find / -perm -u=s -type f 2\>/dev/null
  * Snoop on processes without root : https://github.com/DominicBreuker/pspy/
  * Find files or dirs which give read/write access to any user (eg. www-data)
    * find / -type f -user www-data 2\>/dev/null
    * find / -type d -user www-data 2\>/dev/null

### Active directory
  * shareenum : Enumerate shares from windows hosts (https://github.com/CroweCybersecurity/shareenum)

### Windows privesc
  * Abusing token privileges : https://www.exploit-db.com/papers/42556
  * Living off the land binaries: https://lolbas-project.github.io/

### Malware
  * Security incident reports: https://github.com/aptnotes
  * UI for aptnotes/whois/samples, etc : threatminer.org
 
# Windows internals
### Tools to understand working of windows
  * [nirsoft.net](https://nirsoft.net)
  * [Sysinternal suite](https://docs.microsoft.com/en-us/sysinternals/downloads/sysinternals-suite)

### Books
  * [Windows internals](https://docs.microsoft.com/en-us/sysinternals/resources/windows-internals)

# Binary exploitation
  1. [Liveoverflow's playlist](https://www.youtube.com/playlist?list=PLhixgUqwRTjxglIswKp9mpkfPNfHkzyeN)
  2. [Pwn.college \- ASU's security course](https://pwn.college)

# Reverse engineering
  1. [Crackmes](https://crackmes.one/)
