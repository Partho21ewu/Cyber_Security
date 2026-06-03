# Cyber Security Infrastructure & Network Services Lab

## Overview

This project demonstrates the implementation of core cybersecurity and network infrastructure services on a Linux environment. The work includes Public Key Infrastructure (PKI), DNS server configuration, firewall management, SSL/TLS certificate generation, and secure web server deployment.

The objective was to gain hands-on experience with enterprise-level security technologies and network administration.

---

## Project Components

### 1. Public Key Infrastructure (PKI)

Implemented a hierarchical certificate authority structure:

* Root Certificate Authority (Root CA)
* Intermediate Certificate Authority (Sub CA)
* Server Certificate Generation
* Certificate Signing Requests (CSR)
* Certificate Validation

Tools:

* OpenSSL

---

### 2. SSL/TLS Certificate Management

Features:

* RSA Key Generation
* Certificate Signing
* Root Trust Chain Configuration
* Secure Certificate Deployment

Security Objectives:

* Authentication
* Encryption
* Trust Establishment

---

### 3. DNS Server Configuration

Configured BIND9 DNS Server including:

#### Forward Lookup Zone

* Domain Name Resolution
* A Records
* MX Records
* NS Records

#### Reverse Lookup Zone

* IP Address Resolution
* PTR Records

Features:

* Domain Mapping
* Mail Server Configuration
* DNS Validation

---

### 4. Firewall Security

Implemented firewall policies using UFW:

* Default Deny Incoming Traffic
* Default Allow Outgoing Traffic
* SSH Access Rules
* HTTP Access (Port 80)
* HTTPS Access (Port 443)
* DNS Access (Port 53)

Security Benefits:

* Access Control
* Network Protection
* Service Hardening

---

### 5. Web Server Deployment

Configured and managed:

* XAMPP
* Apache Web Server
* Local Development Environment

Capabilities:

* Web Hosting
* Service Management
* Server Administration

---

## Technology Stack

* Ubuntu Linux
* OpenSSL
* BIND9 DNS
* UFW Firewall
* XAMPP
* Apache Web Server
* PKI Infrastructure

---

## Architecture

```text
Internet / Network
        │
        ▼
    Firewall (UFW)
        │
 ┌──────┴──────┐
 │             │
 ▼             ▼
DNS Server   Web Server
(BIND9)      (XAMPP)
 │
 ▼
PKI Infrastructure
 │
 ├── Root CA
 ├── Intermediate CA
 └── SSL Certificates
```

---

## Learning Outcomes

* Cyber Security Fundamentals
* Public Key Infrastructure (PKI)
* SSL/TLS Certificate Management
* DNS Administration
* Firewall Configuration
* Linux Server Management
* Network Security Implementation

---

## Future Enhancements

* Intrusion Detection System (IDS)
* VPN Deployment
* Security Monitoring Dashboard
* SIEM Integration
* Automated Certificate Renewal
* Cloud-Based DNS Infrastructure

---

## Author

Partho Mahmudul Islam

Master's Student – AI, Machine Learning & Data Science

Kyoto College of Graduate Studies for Informatics (KCGI)
