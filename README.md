## Nickel-Labs-Provisioning
Engineer lab access provisioning system for Nickel Labs

## Project Overview
I am developing an information system (IS) to simulate an engineering lab environment that will demonstrate the full lifecycle of lab access for engineers. The lifecycle includes requesting access, provisioning, network segmentation, IP management, and monitoring.  
This repo conatains the automation and configuration files for Nickel Labs.

## Technology Stack
Proxmox VE - hypervisor
Windows Server 2022 - AD domain controller
Ansible - automated user provisioning
osTicket - access request intake and tracking
pfSense - virtual firewall and network segmentation
phpIPAM - IP address management
Splunk - log aggregation and monitoring 

## Repo Structure
provsion_user.yml - Ansilbe playbook for AD user provisioning 
inventory/ - Ansible inventory files
vars/ - variable files for provisioning
docs/ - Project documentation and diagrams
