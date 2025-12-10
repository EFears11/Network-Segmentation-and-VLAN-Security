# Network-Segmentation-and-VLAN-Security
Project Summary:
This project bulids a complete, enterprise-style virtual network using pfsense as the firewall/router 
It demostrates how real organization secure their environments using VLANs, firewall rules, IDS/IPS, and Captive portal 

All components are bulit entirely  in virtual machines using VirtualBox no hardware. 

This project simulates a small business network contaning 
1. Corpo VLAN (trusted users)
2. IoT VLAN (restricted devices)
3. Guest VLAN (untrusted visitors)


   Repo Contents:
   
   /wiki/ - structured project wiki pages
   
   /screenshots/ - installation steps, network tess, and alert logs
   
   MileStones and User Stories (GitHub Projects tab)

   Learning Outcomes: By completing this project, we will have a better understanding of
   1. Network Architecture
      -Creating VLANs
      -Config virtual switches and router
      -Deploy VMs as clinets

   2. Security Controls
      -Config firewall rules
      -deploy snort/suricata
      -enable captive portal

   3. Hands on skills
      -pfsense administration
      -VirtualBox configuration
      - Logging, monitoring, and validation of network security
     
     📌 Project MilesStones:
   1. Environment Prep and Virtualization Setup
   2. pfSense Installation and Base Configuration
   3. VLAN Creation and Interface Assigment
   4. DHCP Setup for Each VLAN
   5. Firewall Rules for VLAN Isolation
   6. IDS/IPS Installation and Configuration
   7. Captive Portal for Guest VLAN
   8. Client VM Deployment Accross VLANs
   9. Network Testing, Logging and Verification
  
   ✏️ User Stories:
   
   - User Story 1: As a Admin Prepare and Configure the Virtual Environment
     
   -User Story 2: As an Admin Install and Configure pfSense in a Virtual Machine

   -User Story 3: As an Admin Create Multiple VLANs and Assign Them to Virtual Interfaces
   
   -User Story 4: As an Admin Configure DHCP for Each VLAN
   
   -User Story 5: As an Admin Create a Firewall Rules in pfSense to Isolate VLANs
   
   -User Story 6: As an Admin Install and Configure an IDS/IPS (Snornt or Suricata) on pfSense
   
   -User story 7: As an Admin Configure a Captive Portal on the Guest VLAN
   
   -User Story 8: As an Admin Deploy and Configure Client Virtual Machines
   
   -User Story 9: As an Admin Test and Verify Network Segmentation, Firewall rules, IDS/IPS Alerts, and Captive Portal Functionality 
  
   🛠️ Software Requirments:

   1. Host Machine
      -Windows Laptop
      -Minimum: 8GB Ram
      -30GB free disc space

   2. Virtualzation
      -Virtual Box
      -pfSense

   3. VM ISO files
      -pfSense Community edition
      -Windows 10 VMs

  📊 Final Deliverables: 
  1. Configured pfSense VM
  2. Three VLANs
  3. IDS/IPS 
  4. Captive portal for guest network
  5. Client VMs 
  6. README.md
  7. Documentation (Wiki)
  8. Screenshots of Configurations

👷🏽 Support / Help: 

-Wiki Pages 
-ScreenShots 


| Team Member     | Total Story Points Completed | Contribution % |
|------------------|------------------------------|-----------------|
| Terrell          | 24                           | 48%             |
| Millie           | 26                           | 52%             |
| **Team Total**   | **50**                       | **100%**        |

