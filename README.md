```markdown
+-------------------------------------------------------------------------------------------------------------+
#                                            **Official Source For**                                          #
#_________         ___.                                    __   .__ ____  ___   _________________  _________  #
#\_   ___ \ ___.__.\_ |__    ____ _______   ____    ____ _/  |_ |__|\   \/  /  /   _____/\_____  \ \_   ___ \ #
#/    \  \/<   |  | | __ \ _/ __ \\_  __ \ /    \ _/ __ \\   __\|  | \     /   \_____  \   _(__  < /    \  \/ #
#\     \____\___  | | \_\ \\  ___/ |  | \/|   |  \\  ___/ |  |  |  | /     \   /        \ /       \\     \____#
# \______  // ____| |___  / \___  >|__|   |___|  / \___  >|__|  |__|/___/\  \ /_______  //______  / \______  /#
#        \/ \/          \/      \/             \/      \/                 \_/         \/        \/         \/ #
#                                            **By John Poli Modica**                                          #
+-------------------------------------------------------------------------------------------------------------+
```



# Welcome to CybernetiX S3C

My name is John Modica. I am a CEO/CISSP/CISO/CTO/Pentester/Ethical Hacker just trying to help others with simple tools and scripts for their Unix system of choice.

# **Repositories**

## **1. InfoSploit**

InfoSploit is a simple python script for Information Gathering.
The properties of InfoSploit are:
● DNS Lookup ● Whois Lookup ● GeoIP Lookup ● Subnet Lookup ● Port Scanner ● Extract Links ● Zone Transfer ● HTTP Header ● Host Finder ● Robots.txt ● IP-Locator ● Traceroute ● Host DNS Finder ● Revrse IP Lookup ● Collection Email ● Subdomain Finder ● Install & Update ● About Me ● Exit
Click the [link](https://CybernetiX-S3C.GitHub.io/Infosploit) below to go directly to the source or use the basic steps down in the box to download and install directly inside your terminal.

[InfoSploit](https://CybernetiX-S3C.GitHub.io/Infosploit) 

```markdown
#★ Download:

● git clone https://github.com/CybernetiX-S3C/Infosploit

#★ How to use:
unzip Infosploit.zip
cd Infosploit
chmod +x install
./install

Run in Terminal

Infosploit

(To run in Android you do not install file Run direct python2 Infosploit)

#Tutorial
[Tutorial](https://www.youtube.com/watch?v=-6aV9LLF8NQ&t=9s)
```



## **2. Wifi Package**

Wifi Package are simple scripts to bypass the use of airmon-ng, while being able to flip the cards (wlan0/wlan1) between Managed and Monitor mode. This package also contains some very powerful script to change the TX Power of your wireless cards. (May not work for all cards). Click the [link](https://CybernetiX-S3C.GitHub.io/wifipackage) below to go directly to the source or use the basic steps down in the box to download and run directly inside your terminal.
DISCLAIMER: Changing the TX Power is infact illegal in most countries, and will cause cancer, brain damage, and severe loss of memory!

[Wifi Package](https://CybernetiX-S3C.GitHub.io/wifipackage)

```markdown
#★ Download:

● git clone https://github.com/cybernetix-s3c/wifipackage

#★ How to use:

unzip wifipackage.zip
cd (Into Either Folder)
bash NameOfFile.sh (To Run)

#Tutorial
[Tutoriral](https://www.youtube.com/watch?v=Ae6NImby6ZA)
```

## **3. IP-Locator**

IP Locator is basically what is says. It is a script made to utilize perl in a way to find a geolocation of an IP or Domain.
No need for installation. Click The [link](https://CybernetiX-S3C.GitHub.io/ip-locator) below to download the main source, or use the instructions below to download and run directly inside your terminal.

[IP-Locator](https://CybernetiX-S3C.GitHub.io/ip-locator)

```markdown
#★ Download:

● git clone https://github.com/cybernetix-s3c/Ip-locator

#★ How to use:

unzip ip-locator.zip
cd ip-locator
perl iplocator.pl  [host] [ip] [domain] 

Ex:  ./Iplocation.pl  www.google.com 
     ./Iplocation.pl  216.58.210.206

Incase you get any errors reguarding some of the modules, fix is quite simple.
Type in terminal:
cpan WWW::Mechanize    (for the WWW::Mechanize)
cpan JSON              (for the JSON)

and follow instructions.

#Tutorial
[Tutorial](https://www.youtube.com/watch?v=6ETpwk3wsl0)
```

## **4. Script Kiddie WPS Cracker (SK-WC)**

SCRIPT KIDDIE WPS CRACKER [SK-WC] is a small tool based on the bash script language. It can help you to extract the WPS pin of many vulnerable routers and grab the password. This SK-WPS Cracker tool uses the following tools :

    “Piexiewps”
    “Reaver”
    “Bully”
    “Aircrack Suite”
    “Wash”

and some commands, in automatic way to do its job. Enjoy
Click the [link](https://CybernetiX-S3C.GitHub.io/SK-WPS-Cracker) below to grab the source, or use the directions in the box to download the source directly in your terminal.

[SK-WPS-Cracker](https://CybernetiX-S3C.GitHub.io/SK-WPS-Cracker)

```markdown
#★ Download:

● git clone https://github.com/cybernetix-s3c/SK-WPS-Cracker

#★ How to use:

unzip SK-WPS-Cracker.zip
cd SK-WPS-Cracker
./SK-WC.sh

#Tutorial
[Tutorial](https://youtu.be/newiXU4de_M)
```
# **Random Links**

## Speedtest
Check your internet speed on their OFFICIAL website.
[Speedtest.net](https://www.speedtest.net/)
```markdown
# Check your speed in your terminal.
#★ Download:

pip / easy_install
pip install speedtest-cli
or

easy_install speedtest-cli
Github
pip install git+https://github.com/sivel/speedtest-cli.git
or

git clone https://github.com/CybernetiX-S3C/speedtest-cli.git
python speedtest-cli/setup.py install
Just download (Like the way it used to be)
wget -O speedtest-cli https://raw.githubusercontent.com/CybernetiX-S3C/speedtest-cli/master/speedtest.py
chmod +x speedtest-cli
or

curl -Lo speedtest-cli https://raw.githubusercontent.com/CybernetiX-S3C/speedtest-cli/master/speedtest.py
chmod +x speedtest-cli

#★ How to use:

$ speedtest-cli -h
usage: speedtest-cli [-h] [--no-download] [--no-upload] [--bytes] [--share]
                     [--simple] [--csv] [--csv-delimiter CSV_DELIMITER]
                     [--csv-header] [--json] [--list] [--server SERVER]
                     [--exclude EXCLUDE] [--mini MINI] [--source SOURCE]
                     [--timeout TIMEOUT] [--secure] [--no-pre-allocate]
                     [--version]

Command line interface for testing internet bandwidth using speedtest.net.
--------------------------------------------------------------------------
https://github.com/CybernetiX-S3C/speedtest-cli

optional arguments:
  -h, --help            show this help message and exit
  --no-download         Do not perform download test
  --no-upload           Do not perform upload test
  --bytes               Display values in bytes instead of bits. Does not
                        affect the image generated by --share, nor output from
                        --json or --csv
  --share               Generate and provide a URL to the speedtest.net share
                        results image, not displayed with --csv
  --simple              Suppress verbose output, only show basic information
  --csv                 Suppress verbose output, only show basic information
                        in CSV format. Speeds listed in bit/s and not affected
                        by --bytes
  --csv-delimiter CSV_DELIMITER
                        Single character delimiter to use in CSV output.
                        Default ","
  --csv-header          Print CSV headers
  --json                Suppress verbose output, only show basic information
                        in JSON format. Speeds listed in bit/s and not
                        affected by --bytes
  --list                Display a list of speedtest.net servers sorted by
                        distance
  --server SERVER       Specify a server ID to test against. Can be supplied
                        multiple times
  --exclude EXCLUDE     Exclude a server from selection. Can be supplied
                        multiple times
  --mini MINI           URL of the Speedtest Mini server
  --source SOURCE       Source IP address to bind to
  --timeout TIMEOUT     HTTP timeout in seconds. Default 10
  --secure              Use HTTPS instead of HTTP when communicating with
                        speedtest.net operated servers
  --no-pre-allocate     Do not pre allocate upload data. Pre allocation is
                        enabled by default to improve upload performance. To
                        support systems with insufficient memory, use this
                        option to avoid a MemoryError
  --version             Show the version number and exit





```


### Support or Contact

[Facebook Page](https://www.facebook.com/Cyber.S3C.Professional)
[YouTube](https://www.youtube.com/channel/UCAOxHOEpTxpwpmrwy5edWHg/)

