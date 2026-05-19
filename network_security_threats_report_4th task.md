# 1.Denial-of-Service (DoS) Attack

#### \---------------------------------------------

## Definition



A Denial-of-Service (DoS) attack is a cyberattack where an attacker attempts to make a network, server, or website unavailable to users by overwhelming it with excessive traffic or requests.



When multiple compromised systems are used together, the attack is called a Distributed Denial-of-Service (DDoS) attack.



How DoS Attacks Work



In a DoS attack:



The attacker sends a huge number of requests to a target server.

The server becomes overloaded.

Legitimate users cannot access the service.

The network performance slows down or completely crashes.



In DDoS attacks, attackers use botnets (infected devices controlled remotely) to generate traffic from multiple locations.



# Types of DoS Attacks

\--------------------------------------------------



## 1\. Flood Attacks



These attacks consume bandwidth by flooding the target with traffic.



Examples:



UDP Flood

ICMP Flood

HTTP Flood



## 2\. SYN Flood Attack



The attacker sends multiple TCP connection requests but never completes them, exhausting server resources.

###### 

## 3\. Application Layer Attacks



These target specific applications or websites using fake requests.



Impact of DoS Attacks

Website downtime

Financial losses

Reduced productivity

Damage to company reputation

Loss of customer trust

Service disruption



# Real-World Example

\--------------------------------------------

## Dyn DNS DDoS Attack (2016)



In 2016, attackers used the Mirai botnet to launch a massive DDoS attack against Dyn, a DNS provider. Major websites such as:



Twitter

Netflix

Spotify

Reddit



became temporarily unavailable.



The attack used thousands of infected IoT devices like cameras and routers.



# Prevention and Mitigation

\---------------------------------------------------------------

Preventive Measures

Use firewalls and intrusion detection systems (IDS)

Implement rate limiting

Use DDoS protection services

Monitor network traffic continuously

Configure load balancing

Use Content Delivery Networks (CDNs)



# Mitigation Techniques

# \---------------------

Traffic filtering

Blackhole routing

Cloud-based DDoS protection

Network redundancy







# 2\. Man-in-the-Middle (MITM) Attack

\---------------------------------------------------------------------------------------------

## Definition



A Man-in-the-Middle (MITM) attack occurs when an attacker secretly intercepts communication between two parties.



The attacker can:



Steal sensitive information

Modify messages

Monitor communication



# How MITM Attacks Work

\-------------------------------------------------

The attacker positions themselves between the sender and receiver.

Communication passes through the attacker.

The attacker intercepts or alters the data.

Both users believe they are communicating directly.



# Common MITM Techniques

\---------------------------------------------------

## 1\. Wi-Fi Eavesdropping



Attackers create fake public Wi-Fi hotspots to intercept user traffic.

## 

## 2\. Session Hijacking



Attackers steal session cookies to gain unauthorized access.



## 3\. ARP Spoofing



Attackers associate their MAC address with a legitimate IP address on a local network.



## 4\. SSL Stripping



Attackers downgrade HTTPS connections to HTTP.



# Impact of MITM Attacks

\------------------------------------------------------------

Theft of login credentials

Financial fraud

Identity theft

Data leakage

Unauthorized account access

# Real-World Example

\-------------------------------------------------

Public Wi-Fi Attacks



Cybercriminals often create fake Wi-Fi networks in airports, cafes, and hotels. Users who connect unknowingly expose:



Passwords

Banking information

Emails

Personal data

# Prevention and Mitigation

\-------------------------------------------------------------------

Preventive Measures

Use HTTPS websites

Avoid public Wi-Fi for sensitive activities

Use Virtual Private Networks (VPNs)

Enable multi-factor authentication (MFA)

Keep software updated



# Mitigation Techniques

\---------------------------------------------------------

Encryption protocols

Secure DNS

Certificate validation

Network monitoring





# 3\. Spoofing Attacks

\--------------------------------------------

## Definition



Spoofing is a cyberattack where attackers disguise themselves as trusted devices, users, or systems.



The main goal is to gain unauthorized access, steal information, or spread malware.



# Types of Spoofing

\---------------------------------------



## 1\. IP Spoofing



Attackers fake IP addresses to hide their identity.



## 2\. Email Spoofing



Attackers send emails pretending to be trusted organizations.



## 3\. ARP Spoofing



Attackers send fake ARP messages within local networks.



## 4\. DNS Spoofing



Attackers redirect users to malicious websites.



## 5\. Caller ID Spoofing



Attackers fake phone numbers to deceive victims.



# How Spoofing Works

\------------------------------------------------

The attacker impersonates a trusted source.

Victims believe the communication is legitimate.

Victims reveal sensitive information or download malware.

# Impact of Spoofing

\-------------------------------------------------

Identity theft

Financial scams

Malware infections

Data breaches

Unauthorized access

Real-World Example

Email Spoofing Scams



Attackers send fake emails appearing to come from banks or companies like:



PayPal

Amazon

Microsoft



Victims are redirected to fake login pages where credentials are stolen.



# Prevention and Mitigation

\--------------------------------------------------------------------

Preventive Measures

Verify sender identities

Use anti-spoofing technologies

Enable email authentication:

SPF

DKIM

DMARC

Use secure DNS

Educate users about phishing

# Mitigation Techniques

\--------------------------------------------------------

Packet filtering

Network segmentation

Security awareness training

