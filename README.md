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
