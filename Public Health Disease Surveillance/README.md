# Public Health Disease Surveillance Architecture

## Overview

This project demonstrates the design, implementation, and validation of a distributed healthcare system used for disease surveillance. The system integrates multiple hospital systems and a centralized health information exchange using interoperability standards.

---

## Objectives

* Build a multi-system healthcare architecture
* Simulate disease outbreak data using synthetic patients
* Enable interoperability using FHIR APIs
* Secure and manage healthcare data systems

---

## System Architecture

The system consists of:

* 4 Hospital Systems (OpenEMR)
* 1 Health Information Exchange (HAPI FHIR Server)

Each hospital system generates and shares data through the FHIR server.

---

## Virtual Machine Configuration

* Multiple Ubuntu virtual machines deployed
* Each VM assigned a unique IP address
* All systems successfully communicated across the network

This confirms a fully functional distributed system.

---

## Synthetic Data Generation

Synthetic patient data was generated using Synthea.

Key results:

* Large hospital generated over 1400 patient records
* Smaller hospitals generated proportionally scaled datasets

This demonstrates system scalability and realistic population modeling.

---

## Interoperability

FHIR-based REST APIs were used to:

* Create healthcare resources using POST requests
* Send and receive JSON data
* Test endpoints using Postman
* Validate responses using HTTP status codes

---

## Technologies Used

* OpenEMR (Electronic Health Records)
* HAPI FHIR Server
* Synthea (Synthetic Data Generation)
* Postman (API Testing)
* Ubuntu Virtual Machines
* Apache and MySQL

---

## Security Measures

* Firewall configuration (UFW)
* Secure system configuration
* Access control and permissions

---

## Challenges

* Configuring multiple systems
* Networking and connectivity issues
* API testing and debugging
* System security setup

---

## Outcomes

* Built a functional healthcare data system
* Demonstrated interoperability using FHIR
* Simulated realistic patient data
* Verified communication across distributed systems

---

## Skills Demonstrated

* Health Informatics Systems
* FHIR / HL7 Interoperability
* API Development and Testing
* Linux System Administration
* Cybersecurity Fundamentals
