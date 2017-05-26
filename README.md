# Exploits
Miscellaneous proof of concept exploit code written at Xiphos Research for testing purposes.

## Current Exploits

* phpMoAdmin Remote Code Execution (CVE-2015-2208)
* LotusCMS Remote Code Execution (OSVDB-75095)
* ElasticSearch Remote Code Execution (CVE-2015-1427)
* ShellShock (httpd) Remote Code Execution (CVE-2014-6271)
* IISlap - http.sys Denial of Service/RCE PoC (DoS only). (MS-15-034)
* se0wned - Seowintech Router diagnostic.cgi remote root
* WPsh0pwn - Wordpress WPShop eCommerce Shell Upload (WPVDB-7830)
* nmediapwn - Wordpress N-Media Website Contact Form with File Upload 1.3.4 Shell Upload
* pwnflow - Wordpress Work the flow file upload 2.5.2 Shell Upload
* delusions - Wordpress InfusionSoft Gravity Forms Shell Upload (CVE-2014-6446)
* suiteshell - SuiteCRM Post-Auth Remote Code Execution (CVE-2015-NOTYET)
* suiteracer - SuiteCRM Post-Auth Remote Code Execution Race Condition (CVE-2015-xxxx)
* unsanitary - Address Sanitizer + Setuid Binary = Local Root exploit (LD_PRELOAD vector)
* DiamondFox - DiamondFox Botnet C&C Panel Shell Upload
* DoubtfullyMalignant - BenignCertain DoS PoC
* TorCT-Shell - TorCT RAT C&C Panel Shell Upload
* vBullshit - vBulletin 5.x.x unserialize() Remote Code Execution (CVE-2015-7808)
* Xanity-Shell - Xanity RAT C&C Panel Shell Upload
* Joomraa - PoC + upload blacklist bypass (CVE-2016-8869, CVE-2016-8870, CVE-2016-9836)
* Deathsize - LifeSize Room remote code execution & local root exploit
* AssetExploder - ManageEngine Asset Explorer remote code execution
* DroppleGanger - Droppler <= 1.6.5 Auth-Bypass & RCE
* tr-06fail - TR-064 Misimplementations leading to remote device takeover in ZyXEL Routers
* screen2root - Screen 4.05.00 (CVE-2017-5618) local privesc
* FreeACS-Pwn - TR-069 exploit for FreeACS server, disclosed at BSides Edinburgh.
* Joomblah - Joomla 3.7.0 SQL Injection exploit (CVE-2017-8917)
* pisspoorpool - Local file inclusion exploit for p2pool status page
* TBA

## Infrequently Asked Questions.

1. Why is there no "leet zerodays" in here?

   Because some of our researchers don't believe in killing bugs prematurely, and the unofficial policy on disclosure is that it is at the sole discretion of the person who finds the bug.
2. Why don't you just write metasploit modules?

   Reasons, namely, "ruby", amongst other things. Also, other people who are actually getting paid by Rapid7 to do such things can do such things :)
3. Why are there some old bugs in here?

   The public exploits available for them were unreliable/untrustworthy/rubbish and better ones were called for, or, they are parts of ongoing experiments into various methods to make them more reliable/stealthy/whatever.

## Licence
See individual exploits for their respective licences.

## Bug Reports
We take the quality of our exploit code very seriously. If you find a bug, or an edge case where an exploit fails to succeed against a vulnerable target, do let us know immediately so said situation can be rectified via the bug tracker (issues thing on this repository), or via email/twitter.

## Changes
There is no changelogs here, as that would be too much effort, just git commits. Exploits may be updated regularly for greater stability, reliability or stealthiness, so check them for updates regularly.
