# Xenith DNS blocklist
<img src="https://www.xenith.co.uk/hubfs/Xenith-logo-2019.svg" width="150">

This intent of this project is to collect phishing websites in a list in order to block the DNS requests via Pi-Hole.

Each entry is written as follows:
```
##########################################################
# 2021-06-16
# From: email@somedomain.com
# Url: phishing url
0.0.0.0 phishing_site.com
0.0.0.0 www.phishing_site.com
0.0.0.0 somedomain.com
0.0.0.0 www.somedomain.com
##########################################################
```
The domain from where the email generated is blacklisted only if it's not a legit company. 
