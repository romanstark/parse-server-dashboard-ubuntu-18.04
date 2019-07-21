# parse-server-dashboard-ubuntu-18.04
Shell scripts and config files to install Parse Server and Dashboard on Ubuntu 18.04 LTS.
This work is based on https://github.com/bajpangosh/Install-Parse-Server-on-Ubuntu/tree/master/ubuntu-18.04

# Howto
Clone this repository into your home folder and run the shell script:
On a fresh Ubuntu 18.04 installation please install git before you start.
You net to setup A-Records for you domain. E.g. *.example.com or the named subdomains you are going to choose during setup

```
cd /root && git clone https://github.com/romanstark/parse-server-dashboard-ubuntu-18.04.git
sudo bash setup-parse-and-dashboard-u18-04
```

# What's missing
* Add option for letsencrypt instead of self signed certificate. 
* Add option to don't setup parse dashboard as the dashboard may be used on different locations and hosts. 
