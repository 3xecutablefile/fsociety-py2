- Information Gathering
- Password Attacks
- Wireless Testing
- Exploitation Tools
- Sniffing & Spoofing
- Web Hacking
- Private Web Hacking
- Post Exploitation
- Contributors
- Install & Update

### Information Gathering:

- Nmap
- Setoolkit
- Host To IP
- WPScan
- CMS Scanner
- XSStrike
- Dork - Google Dorks Passive Vulnerability Auditor
- Scan A server's Users
- Crips

### Password Attacks:

- Cupp
- Ncrack

### Wireless Testing:

- Reaver
- Pixiewps
- Bluetooth Honeypot

### Exploitation Tools:

- ATSCAN
- sqlmap
- Shellnoob
- Commix
- FTP Auto Bypass
- JBoss Autopwn

### Sniffing & Spoofing:

- Setoolkit
- SSLtrip
- pyPISHER
- SMTP Mailer

### Web Hacking:

- Drupal Hacking
- Inurlbr
- Wordpress & Joomla Scanner
- Gravity Form Scanner
- File Upload Checker
- Wordpress Exploit Scanner
- Wordpress Plugins Scanner
- Shell and Directory Finder
- Joomla! 1.5 - 3.4.5 remote code execution
- Vbulletin 5.X remote code execution
- BruteX - Automatically brute force all services running on a target
- Arachni - Web Application Security Scanner Framework

### Private Web Hacking:

- Get all websites
- Get joomla websites
- Get wordpress websites
- Control Panel Finder
- Zip Files Finder
- Upload File Finder
- Get server users
- SQli Scanner
- Ports Scan (range of ports)
- Ports Scan (common ports)
- Get server Info
- Bypass Cloudflare

### Post Exploitation:

- Shell Checker
- POET
- Weeman

# Installation

## Installation

Clone the repository and run the installer.

```bash
git clone https://github.com/fsociety-team/fsociety.git
cd fsociety
bash install.sh
```

For Android devices install [Termux](https://play.google.com/store/apps/details?id=com.termux) and run the same commands.

## Installation [Windows](https://wikipedia.org/wiki/Microsoft_Windows)[![alt tag](http://icons.iconarchive.com/icons/yootheme/social-bookmark/32/social-windows-button-icon.png)](https://fr.wikipedia.org/wiki/Microsoft_Windows)

Install [Python 3](https://www.python.org/downloads/) and a Unix-like terminal such as [Cygwin](https://www.cygwin.com/) or [WSL](https://learn.microsoft.com/en-us/windows/wsl/).


```bash
git clone https://github.com/fsociety-team/fsociety.git
cd fsociety
bash install.sh
```

## [Docker](https://en.wikipedia.org/wiki/Docker_(software)) Usage ![docker logo](https://png.icons8.com/color/50/000000/docker.png)

### Dependecies

[Docker](https://www.docker.com/)

[Docker-compose](https://docs.docker.com/compose/install/)

```bash
docker-compose build
docker-compose up -d
docker-compose exec fsociety fsociety
docker-compose down # destroys instance
```


