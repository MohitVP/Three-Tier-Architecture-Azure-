🏗️ 3-Tier Architecture Deployment Project
This project demonstrates how to set up a basic 3-tier architecture using Virtual Machines, where each tier serves a specific role:

Web Tier: Nginx installed on WEB-VM (port 80)

Application Tier: Tomcat 10 running on APP-VM (port 8080)

Database Tier: MySQL installed on DB-VM (port 3306)


🛠️ Tools & Services Used:
Nginx – Web Server

Apache Tomcat 10 – Application Server

MySQL – Relational Database

Ubuntu – OS for each VM

Azure – Cloud Platform for VM provisioning

Telnet – Used for connectivity testing between VMs


✅ Features:
Browser access to Nginx on port 80

Internal connectivity from Web to App (8080), App to DB (3306)

DB is not directly accessible from Web tier (security validated)

NSG rules ensure proper access control between all tiers


📁 Folder Contents:
Step-by-step installation guides for each tier

Telnet connectivity test results

Sample configuration code

Screenshots or validations (if added)


And I upload file as Word file so if you see a (raw) just click on that you will automatically download that work file and all the steps i mentioned.
