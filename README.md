# Ex-02 InformationGathering
## AIM:
To perform information gathering techniques using kali linux 
## STEPS:
### Step 1:
Install kali linux either in partition or virtual box or in live mode

### Step 2:
Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:
### Whois

<img width="1834" height="1145" alt="image" src="https://github.com/user-attachments/assets/17911bc4-3318-4ff0-87cf-0fd66daacbbe" />


### Finding Hosting Company :

<img width="1852" height="938" alt="image" src="https://github.com/user-attachments/assets/18bedd12-f9c4-4d3b-9253-bc4317c0e837" />



### History of the website :


<img width="1824" height="1125" alt="image" src="https://github.com/user-attachments/assets/4fcb24d3-3d0d-4460-a778-d3196905908e" />



### ping command :
<img width="735" height="694" alt="image" src="https://github.com/user-attachments/assets/354b4935-5a03-4c5f-8637-b7b749d157a4" />


### whois :

<img width="760" height="742" alt="image" src="https://github.com/user-attachments/assets/79694cd4-c12c-4d63-b313-913e1506a733" />


### netcat :

<img width="665" height="108" alt="image" src="https://github.com/user-attachments/assets/bb93be15-acb6-4473-bc3b-590e015f712c" />

### nmap :

<img width="637" height="261" alt="image" src="https://github.com/user-attachments/assets/37659d82-c9f5-47c1-a5bc-4baff004e2db" />


### whatweb :

<img width="745" height="197" alt="image" src="https://github.com/user-attachments/assets/928a6c89-b160-421c-add3-4dd7bd400aa0" />


### httprint :

<img width="630" height="208" alt="image" src="https://github.com/user-attachments/assets/25d1d98e-6ccd-4459-957f-c91ac4edd97e" />


### TCP traceroute :

<img width="747" height="394" alt="image" src="https://github.com/user-attachments/assets/c957bd67-1b5e-42ba-baee-1fa5332cbb47" />

### UDP traceroute :

<img width="731" height="527" alt="image" src="https://github.com/user-attachments/assets/7478e1f6-9ed0-4a13-8629-fed1faa85635" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
