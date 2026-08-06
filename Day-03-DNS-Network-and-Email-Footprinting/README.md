# Day 3 - DNS, Network and Email Footprinting

## Learning Objectives

After completing this lesson, I should be able to:

- Explain Footprinting
- Explain DNS
- Identify common DNS records
- Perform DNS enumeration
- Perform Reverse DNS Lookup
- Understand Network Footprinting
- Use Traceroute
- Understand Email Footprinting
- Explain why hackers perform reconnaissance


# What is Footprinting?

Footprinting is the process of gathering information about a target before attempting any attack.

Think of it like a detective investigating a building before entering it.

Instead of attacking immediately, an ethical hacker collects information about:

- Domain names
- DNS records
- Servers
- Email servers
- Network topology
- Public information

The information collected helps identify possible attack surfaces.


# What is DNS?

DNS stands for Domain Name System.

Imagine having a phone contact list.

Instead of memorizing everyone's phone number, you simply remember their names.

The Internet works the same way.

Example:

google.com

↓

142.x.x.x

DNS converts a domain name into an IP address.

# Common DNS Records

## A Record

Maps a domain name to an IPv4 address.

Example:

google.com

↓

142.xxx.xxx.xxx

---

## AAAA Record

Maps a domain to an IPv6 address.

---

## MX Record

Shows the email server responsible for receiving emails.

---

## NS Record

Shows the authoritative DNS server.

---

## TXT Record

Stores verification or security information.

---

## SOA Record

Contains information about the DNS zone.


# DNS Footprinting

DNS Footprinting is the process of gathering DNS information about a target.

The goal is to discover:

- DNS servers
- Mail servers
- Subdomains
- IP addresses
- DNS records

This information helps map the target infrastructure.


# Reverse DNS Lookup

Normal DNS

Domain

↓

IP Address

Reverse DNS

IP Address

↓

Domain Name

Example

8.8.8.8

↓

dns.google


# Network Footprinting

Network Footprinting gathers information about the target's network.

Examples include:

- Network range
- Routers
- Firewalls
- Operating systems
- Live hosts

# Traceroute

Traceroute shows every router a packet passes through before reaching its destination.

Think of travelling from Calabar to Lagos.

Calabar

↓

Uyo

↓

Port Harcourt

↓

Benin

↓

Ore

↓

Lagos

Traceroute displays each stop (hop).


# Email Footprinting

Email Footprinting gathers information from email headers.

Examples include:

- Sender IP
- Mail server
- Email route
- Date and time
