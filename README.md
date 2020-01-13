![DARKEAGLE](https://user-images.githubusercontent.com/58636468/72290307-e555d280-3672-11ea-9b82-76c9fdb77bf9.png)

#### Version 2.0.0
#### By NANDYDARK
All in one tool for **Information Gathering** and **Vulnerability Scanning**

# Scans That You Can Perform Using DARK EAGLE :
+ Basic Scan
	- Site Title 
	- IP Address
	- Web Server Detection 
	- CMS Detection
	- Cloudflare Detection
	- robots.txt Scanner
+ Whois Lookup 
+ Geo-IP Lookup
+ Grab Banners 
+ DNS Lookup
+ Subnet Calculator
+ Nmap Port Scan
+ Sub-Domain Scanner 
	- Sub Domain
	- IP Address
+ Reverse IP Lookup & CMS Detection 
	- Hostname
	- IP Address
	- CMS
+ Error Based SQLi Scanner
	- HTTP Response Code
	- Site Title
	- Alexa Ranking
	- Domain Authority
	- Page Authority
	- Social Links Extractor
	- Link Grabber
+ WordPress Scan 
	- Sensitive Files Crawling
	- Version Detection
	- Version Vulnerability Scanner
+ Crawler
---
- Version 2.0.0
	- Separated all scans so that you are served the amount of information you need
	- `Sub-Domain Scanner` improved
	- `fix` command improved
	- `Web Server Detection` Improved
	- `CMS Detection` Improved
	- `Banner Grabbing` Improved
	- Added `WordPress Scanner`
	- Added `Bloggers View`
	- Added `MX Lookup`
	- Added `Update` option
	- DARK EAGLE Banner Updated
	- Many Other Internal Fixes

Modules.
# Usage:
- git clone `https://github.com/nandydark/DARK-EAGLE
- cd DARK-EAGLE
- php darkeagle.php
- Use the "help" command to see the command list or type in the domain name you want to scan (without Http:// OR Https://).
- Select whether The Site Runs On HTTPS or not.
- Select the type of scan you want to perform
- Leave the rest to the scanner

# List of CMS Supported
DARK EAGLE's `CMS Detector` currently is able to detect the following CMSs (Content Management Systems) in case the website is using some other CMS, Detector will return _could not detect_.

- WordPress
- Joomla
- Drupal
- Magento
# Known Issues
**ISSUE:** Scanner Stops Working After Cloudflare Detection!

**SOLUTION:** Use The `fix` Command OR Manually Install *php-curl* & *php-xml*
