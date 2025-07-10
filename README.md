# ELK Stack

## Objective

The goal of this project was to gain hands-on, practical experience as an aspiring SOC analyst, by setting up an ELK stack, conducting and investigating attacks, setting up alerts and dashboards and integrating a ticketing system.

### Skills Learned

- Drawing network architecture and threat modeling diagrams
- Log ingestion and ELK stack setup (Elasticsearch, Logstash, Kibana)  
- Detecting brute-force, malware and C2 attacks
- Creating custom detection alerts and dashboards in Kibana
- Endpoint investigation using Sysmon data
- Integrating a ticketing system into the security workflow.
- Deploying and using C2 framework (Mythic).
- Setting up and managing cloud-based servers and firewalls.


### Tools Used

<img src="https://img.shields.io/badge/-Elastic-005571?&style=for-the-badge&logo=Elastic&logoColor=white" /> — used as the search and analytics engine in the ELK stack. <br>
<img src="https://img.shields.io/badge/-Logstash-000000?&style=for-the-badge&logo=Logstash&logoColor=white" /> — for processing and forwarding logs into Elasticsearch. <br>
<img src="https://img.shields.io/badge/-Sysmon-000000?&style=for-the-badge&logo=windows&logoColor=white" /> — for generating detailed Windows system telemetry. <br>
<img src="https://img.shields.io/badge/-Kibana-E8478B?&style=for-the-badge&logo=Kibana&logoColor=white" /> — for visualizing logs, creating dashboards, and building alerts. <br>
<img src="https://img.shields.io/badge/-Mythic-000000?&style=for-the-badge&logo=linux&logoColor=white" /> — a command and control (C2) framework used for simulating attacker behavior. <br>
<img src="https://img.shields.io/badge/-OSTicket-231F20?&style=for-the-badge&logoColor=white" /> — used as the SOC ticketing system to manage incidents and investigations. <br>
<img src="https://img.shields.io/badge/-Vultr-007BFC?&style=for-the-badge&logo=Vultr&logoColor=white" /> — cloud provider used to deploy Windows and Linux machines. <br>

## Steps

<img width="895" height="729" alt="image" src="https://github.com/user-attachments/assets/18aacfad-ea0e-4df8-90ff-8d68780c39e9" /><br>
*Ref 1: Diagram of the network developed*

<img width="940" height="280" alt="image" src="https://github.com/user-attachments/assets/4244f871-f8bb-4ef1-af62-3679b344ecb9" /><br>
*Ref 2: Elasticsearch service running on ELK Server*

<img width="940" height="455" alt="image" src="https://github.com/user-attachments/assets/1aa89bb0-cf85-45ed-85e0-68a949e16828" /><br>
*Ref 3: Kibana service running as well*

<img width="940" height="327" alt="image" src="https://github.com/user-attachments/assets/5482da1e-19b0-40b5-8bec-3b1ef5010971" /><br>
*Ref 4: Created Fleet server and Windows server, and added Windows server to the fleet server*

<img width="940" height="474" alt="image" src="https://github.com/user-attachments/assets/503ec430-c982-4af5-a3fa-bc6c1eb49f71" /><br>
*Ref 5: Ingested sysmon data from Windows server into Elasticsearch*

<img width="623" height="530" alt="image" src="https://github.com/user-attachments/assets/b595dbf5-8b7a-4c00-a70b-8d01b32e6354" /><br>
*Ref 6: Spun up Ubuntu server, and added it to fleet to ingest logs*

<img width="1451" height="501" alt="image" src="https://github.com/user-attachments/assets/2bcb5576-d376-4597-9215-dcaf4550ecbd" /><br>
*Ref 7: Dashboard of SSH Authentications*

<img width="583" height="456" alt="image" src="https://github.com/user-attachments/assets/09c8c839-74fd-4ef5-b992-48640d8b1a02" /><br>
*Ref 8: Part of attack diagram*

<img width="940" height="459" alt="image" src="https://github.com/user-attachments/assets/c6f93035-d712-48b6-8a7d-255b285882f5" /><br>
*Ref 9: Set up a mythic server*

<img width="940" height="29" alt="image" src="https://github.com/user-attachments/assets/fe762529-b9a7-4999-8cdb-5bd06b1db8b4" /><br>
*Ref 10: Active callback from Windows server in Mythic client*

<img width="1455" height="585" alt="image" src="https://github.com/user-attachments/assets/5c1e04b4-140f-4a10-bd03-89fbb0a5bbe1" /><br>
*Ref 11: Dashboard focused on suspicious activity*

<img width="940" height="403" alt="image" src="https://github.com/user-attachments/assets/b7ae1a29-6fb9-4a7c-9382-06603c8a42bf" /><br>
*Ref 12: Set up OSTicket, integrated it into ELK, and set up automatic tickets for SSH brute force activity*












