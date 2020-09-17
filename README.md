# MYETP
AWS CLOUD INFRASTRUCTURE

This repository host the configuration files for the web and intranet AWS cloud infrastructure of MYETP organization.

These files will allow administrators to launch an automated creation of an AWS cloud infrastructure, including :

- HTML files for the intranet
- VPN configuration files using Strongswan
- Docker website container
- Yaml script for the AWS cloud infrastructure

Howto :

Just change the website.yml script with your own parameters and launch it on the AWS Cloud Formation service.

Prerequisites :

- Secrets for database, wordpress and VPN stored in the Secret Manager and System Manager services of AWS
- A local Ubuntu 18.04 server with Strongswan installed and configured
- A local Ubuntu 18.04 desktop with Samba files sharing
