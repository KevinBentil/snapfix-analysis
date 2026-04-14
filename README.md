# CMMS Implementation and Performance Analysis


### Executive Summary.  
This project documents the successful implementation of a centralized CMMS solution across multiple client sites in Ireland, replacing a legacy platform (IBM TRIRIGA). The implementation focused on improving visibility, standardization, and data-driven decision-making for facilities, maintenance, and workplace services.
The solution enables:.    

Consistent ticket intake across sites.      
Real-time operational reporting.      
Improved SLA compliance tracking.      
Enhanced asset and audit management.     
Actionable insights for senior management.  

### Business Objectives.   
Eliminate inefficiencies in the existing maintenance management process.   
Standardize service request and audit data across all sites.   
Improve response times and SLA governance.   
Provide leadership with clear, reliable operational insights.   
Reduce dependency on technical teams for configuration changes.   

## CMMS Implementation Process followed;
1. Gathered client requirement through interview to identify inefficiency and gaps with exisiting solution.
2. Moved user requirements gathered from excel sheet into product backlog on Trello kanban board.
3. Assign user story numbers to each requirement
4. Prioritized user stories with client into MOSCOW [Must Have - Should Have - Could Have - Won't Have]
5. The CMMS platform was built customisable on all levels, hence no need to further schedule or break down user stories into iterations/sprints. Changes can be made at adminstrator level based on the solution without engaging tech/ solutions team, unless a code change i.e Change request or additional features.
6. Design work/ process flow on figma for client demonstration.
7. Configured platform functionlaties into groupd and sites for ticketting and data collection.
8. Migrated data from previous platform (Tririga) for configuration i.e;.  
    8 (i) Monthly asset PPM's.      
      (ii) WPC meeting room audit.      
      (iii) Soft service supervisor audit.      
      (iv) Security audit.      
      (v) Contractor checklist.


     

# GO LIVE & Operational Enablement;
 ## Multi-Site Rollout
1.I created a standardized site template in a form of a site group, replicated across all client locations in Ireland.    
  


<img width="1913" height="989" alt="Screenshot 2026-04-13 180214" src="https://github.com/user-attachments/assets/afc9c196-3e4c-4fc7-a36b-ed4d618b3e7f" />

Each site confiugured with unique tags and labels to enable both local management and group-level reporting.     

<img width="1550" height="795" alt="image" src="https://github.com/user-attachments/assets/0611f5a0-74c0-4008-96f1-3b5d12481e7c" /> .      

2. I configured process for raising tickets, taking into consideration tags & labels (spreadsheet headers) useful for analysis i.e.   
   (i). creating task locations for each group (e.g Upper ground, lower ground, 1st floor etc).   
   (ii). creating categories that tickets are likely to fall under (Project, Planned Maintenance, Near Hit).   
   (iii). creating SLA's for tickets (Standard, Emergency, Standard).     
<img width="1917" height="987" alt="1" src="https://github.com/user-attachments/assets/34f47eda-5b37-4912-a0b5-23e968ce020f" />

<img width="1910" height="941" alt="2" src="https://github.com/user-attachments/assets/e3b30afb-ee8e-429e-9c31-4772028cec27" />

<img width="1916" height="994" alt="3" src="https://github.com/user-attachments/assets/05d18815-1cc6-40fa-b573-963f6126c699" />

<img width="1916" height="988" alt="4" src="https://github.com/user-attachments/assets/9f7d5a44-ba45-41b3-9c76-3e6dd201f320" />

<img width="1905" height="984" alt="5" src="https://github.com/user-attachments/assets/d9a569ce-28ef-47f6-a0f9-147b5a2616c5" />

<img width="1253" height="798" alt="6" src="https://github.com/user-attachments/assets/3b6ac3b8-d500-4467-a344-d2c6bc44ff56" />

<img width="1917" height="986" alt="7" src="https://github.com/user-attachments/assets/1dc850c0-e71a-4e09-a655-783cbf69190d" />

# 4. QR Code–Enabled Service Requests.     
I deployed QR codes across all buildings (meeting rooms, common areas, restrooms, entrances).  
Enabled fast, intuitive ticket creation via mobile devices.     
Enforced mandatory fields to improve data completeness and accuracy. 

### Key Outcome:  Increased user adoption and reduced friction in raising service requests.

![IMG_0629](https://github.com/user-attachments/assets/56e7ba8b-0846-414d-b346-ca7104f0a01d) .  

Users raising a ticket are presented with the above in the form of fields that are mandatory for generating a ticket.


<img width="375" height="667" alt="IMG_0631" src="https://github.com/user-attachments/assets/7dcbb9e7-a26d-48dc-b2d5-143428bc5677" /> 

<img width="375" height="667" alt="IMG_0632" src="https://github.com/user-attachments/assets/1b41e577-cb70-48c7-977f-9b9b34051e12" />




# **Reporting, Analysis & Management Insights**
All operational data is accessible via the CMMS portal and exportable in CSV format across multiple report types.   

Designed dashboards and reports to support management oversight, including:.  

--Volume of tickets by site.   
--Ticket type distribution.   
--SLA compliance and non-compliant tickets.   
--Average resolution times.   
--Daily ticket trends.   
--Segregation of tickets raised by internal staff vs service providers.   
--Trend analysis for workload forecasting.   

<img width="1425" height="801" alt="image" src="https://github.com/user-attachments/assets/46c65c52-0be1-47f9-ad39-5b8cacdbfef5" />

<img width="1425" height="804" alt="image" src="https://github.com/user-attachments/assets/5b002187-3f8d-4259-86b9-8ff3c7bf4eb2" />

<img width="1430" height="803" alt="image" src="https://github.com/user-attachments/assets/972b5450-9ad6-4a32-95f0-8e9ccc1f9a83" />







**Cleaning Audit**

Introduced for the purpose of monitoring week on week cleaning audit

<img width="1431" height="800" alt="image" src="https://github.com/user-attachments/assets/e65eee74-c8dc-41fc-8ca4-7ec042872139" />



### Asset Management Enhancement.   

Migrated furniture asset data from spreadsheets into the CMMS.   
<img width="1436" height="762" alt="Screenshot 2026-04-13 at 7 03 38 p m" src="https://github.com/user-attachments/assets/c338f825-67d7-4c86-accb-cbf356201089" />

Captured images for each asset to improve traceability and verification. This established a foundation for advanced asset tracking
<img width="1440" height="685" alt="Screenshot 2026-04-13 at 7 06 04 p m" src="https://github.com/user-attachments/assets/16223faa-3967-4405-8600-da1b25991f00" />

<img width="1440" height="722" alt="Screenshot 2026-04-13 at 7 06 25 p m" src="https://github.com/user-attachments/assets/e81c7860-27ae-44c5-b601-8f2fe693f14a" />

### Planned Phase 2 Enhancements:

NFC or barcode tagging for each asset.  
Faster audits and improved asset lifecycle tracking


# Business Impact & Value Delivered

Improved visibility of maintenance and service performance.   
Reduced manual reporting and spreadsheet dependency.    
Increased accountability through SLA tracking.    
Enhanced decision-making through standardized data.       
Scalable solution supporting future sites and services.      

