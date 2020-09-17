# MYETP
AWS CLOUD INFRASTRUCTURE

This repository host the configuration files for the web and intranet AWS cloud infrastructure of MYETP organization.

These files will allow administrators to launch an automated creation of an AWS cloud infrastructure, including :

- Simple HTML intranet page
- VPN configuration between a local subnet and an AWS private subnet using Strongswan
- Docker website container
- AWS cloud infrastructure with network, RDS, autoscaling group for the website servers and EC2 instances for the intranet servers

Howto :

Just change the website.yml script with your own parameters and launch it on the AWS Cloud Formation service.

Prerequisites :

- Secrets for database, wordpress and VPN stored in the Secret Manager and System Manager services of AWS
- A local Ubuntu 18.04 server with Strongswan installed and configured
- A local Ubuntu 18.04 desktop with Samba files sharing
- Make sure to choose a not-used S3 bucket name when choosing the stack name (they will be the same)
