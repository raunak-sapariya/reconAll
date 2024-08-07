# Automated Reconnaissance Script

## Description

This bash script automates the process of reconnaissance on a target domain. It performs various tasks to gather subdomains, probe for alive domains, check for potential subdomain takeovers, scan for open ports, scrape wayback data, and compile different file types found in the wayback data. The script leverages tools like assetfinder, httprobe, subjack, nmap, and waybackurls.

## Prerequisites

Make sure the following tools are installed and available in your system's PATH:

- assetfinder
- httprobe
- subjack
- nmap
- waybackurls
- eyewitness
- subjack

## Usage

```bash
chmod +x recon.sh
./recon.sh <target_domain>
