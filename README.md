<p align="center">
	<img src="https://imgur.com/TUKyoMz" width="600px">
</p>

#### Version 2.0.0
#### By NANDYDARK
All in one tool for **Information Gathering** and **Vulnerability Scanning**

# Scans That You Can Perform Using DARK EAGLE :
+ Basic Scan
	- Site Title **NEW**
	- IP Address
	- Web Server Detection `IMPROVED`
	- CMS Detection
	- Cloudflare Detection
	- robots.txt Scanner
+ Whois Lookup `IMPROVED`
+ Geo-IP Lookup
+ Grab Banners `IMPROVED`
+ DNS Lookup
+ Subnet Calculator
+ Nmap Port Scan
+ Sub-Domain Scanner `IMPROVED`
	- Sub Domain
	- IP Address
+ Reverse IP Lookup & CMS Detection `IMPROVED`
	- Hostname
	- IP Address
	- CMS
+ Error Based SQLi Scanner
+ Bloggers View **NEW**
	- HTTP Response Code
	- Site Title
	- Alexa Ranking
	- Domain Authority
	- Page Authority
	- Social Links Extractor
	- Link Grabber
+ WordPress Scan **NEW**
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
- git clone `https://github.com/nandydark/DARK EAGLE
- cd DARK EAGLE
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