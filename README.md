# Basic-Employee-Onboarding-AD-RBAC-
Active Directory infrastructure rebuild for a fictional company called “Northstar Medical Group”. Includes domain setup, organizational structure, user provisioning, RBAC implementation, and incident resolution.

# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
This project is related to a fictional company called Northstar Medical Group (NMG), they are a fast growing company who delegated their identity lifecycle workflow to a MSP. Users were being added manually and inconsistently, without correlation to any specific . Some employees ended up with way more access than they should have, while others couldn’t do their jobs because they didn’t have the permissions they needed. When someone left the company, the MSP often forgot to disable their account — sometimes for months. No one documented changes to user accounts, and new hires regularly spent days dealing with access issues. Because of all this disorganization and manual work, NMG faced serious HIPAA compliance risks.
## Solution Overview
I created four Organizational Units: Finance, HR, IT, and Operations and four Security Groups for each of them. I added every user to their respective department and assigned them the appropriate security group, ensuring the principle of least privilege. It is now easier to track disabled/enabled accounts, move users, and maintain overall organization. I also ran a mock ticket to simulate a user being given the wrong access and walked through the steps to correct it. Northstar Medical Group now has a well‑structured and organized Active Directory/RBAC environment.

## Video Walkthrough


## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Designed department-based OU structure (Finance, HR, IT, Operations)
* Implemented RBAC with security groups mapped to each department
* Provisioned 15 user accounts with consistent naming conventions and attribute standards






