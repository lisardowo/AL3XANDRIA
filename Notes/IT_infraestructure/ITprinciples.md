# Module 01: IT principles

## Summary

> What is IT and IT infrastructure, modern alternatives to handmade all the infrastructure. Introduction and examples of Cloud Computing.

---

## Core concepts

- SAAS
- PAAS
- IAAS

### 1. SAAS

- **What is?:** SAAS stands for software as a service, here the vendor is in charge to provide all the services to the client, has a principle of On-demand service where you sign up and as soon as that is complete the user can start using the service 
- **Features"** Usage-based billing, Pay-as-you-go, integrated via API, Software doesn't live in client machines, client machines only input/output data from software by connecting to vendors servers, can be used in a web browser or thin client
- **Why is important:** Faster and cheaper deployment type, outsource non critical solutions to focus on develop important/customized solutions 
- **Considerations:** Dependability, connectivity, security, growth potential, lock-in platform
- **Examples:** Citrix, Ciscos webex, succesFactors

### 2. PAAS

- **What is?:** PAAS stands for Platform as a service, here is where the software run, the vendor take care of hardware an OS that will run the software but not the software itself 
- **Why is important:** useful in collaborative development and automatic deployment/testing 
- **No suitable for:** Need hosting portability, proprietary approaches impact development, app performance require customization of hardware or software 
- **Examples:** Hostinger, Notification and payment services

### 3. IAAS

- **What is?:** IAAS stands for infrastructure as a service is the practice of deliver computing infrastructure(servers, storage, network) as an on demand service. Vendor only provides hardware, client manages all the other services 
- **Why is important:**  demand is volatile organization is growing, limited capital, temporary infrastructure is needed
- **Examples:** AWS, Azure, DigitalOcean

---
Client []
Provider [x]
|who manages who?|IAAS|PAAS|SAAS|
|----------------|----|----|----|
|Apps            | [] | [] | [x]|
|Data            | [] | [] | [x]|
|Operative System| [] |[x] | [x]|
|Virtualization  | [x]|[x] | [x]|
|Server & Storage| [x]|[x] | [x]|
|Networking      | [x]|[x] | [x]|

## Notas y Observaciones Adicionales

> modern infrastructure is built outsourcing to other companies to keep costs low

---

## Resources

- [Differences and examples](https://www.leanix.net/en/wiki/apm/iaas-vs-paas-vs-saas)

