# Basic Firewall Configuration Using UFW



## Objective

Configure a basic firewall using UFW on Linux.



# Tools Used

UFW (Uncomplicated Firewall)

Ubuntu/Linux Terminal



# Steps Performed



1\. Installed UFW

2\. Allowed SSH traffic on port 22

3\. Denied HTTP traffic on port 80

4\. Enabled firewall

5\. Verified firewall rules





# Commands Used



## Install UFW



bash

sudo apt install ufw -y





Allow SSH



bash

sudo ufw allow ssh





Deny HTTP



bash

sudo ufw deny http



Enable Firewall



bash

sudo ufw enable



Check Status



bash

sudo ufw status numbered





# Firewall Rules Configured



| Port | Protocol | Action |

|---|---|---|

| 22 | TCP | ALLOW |

| 80 | TCP | DENY |



# Outcome

Successfully configured a basic firewall using UFW to secure the Linux system.

