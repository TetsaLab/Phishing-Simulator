# Phishing-Simulator

## Objective

Designed and implemented a cloud-hosted phishing simulation lab to gain hands-on experience with security awareness testing and phishing campaign management in a controlled environment. The project focused on configuring and deploying phishing campaigns using Gophish, creating realistic HTML-based phishing emails and landing pages, configuring an SMTP relay through Mailpit, and tracking campaign metrics such as email delivery, opens, link clicks, and credential submissions.

This lab was developed exclusively for educational purposes within an authorized test environment to demonstrate practical skills relevant to security operations, security awareness programs, and phishing simulation management.

### Skills Demonstrated

*  Phishing simulation deployment
*  Security awareness campaign management
*  HTML email and landing page development
*  SMTP configuration and email delivery testing
*  Virtual machine deployment and management
*  Campaign monitoring and reporting
*  Troubleshooting application and network connectivity
*  Email infrastructure testing
*  Windows administration
*  Cybersecurity lab documentation
*  Security operations fundamentals

### Tools Used

-  VMware Workstation:	Hosted the Windows 11 virtual machine used as the phishing simulation environment.
-  Gophish:	Created and managed phishing campaigns, user groups, landing pages, email templates, and campaign reporting.
-  Mailpit:	Captured and viewed outbound phishing emails locally without requiring real mailboxes.
-  Windows 11:	Operating system hosting the phishing simulation environment.
-  HTML:	Developed custom phishing email templates and landing pages.

### Lab Architecture
Windows 11 VM
        │
        ▼
    Gophish
        │
        ├──────────────┐
        ▼              ▼
 Mailpit SMTP     Landing Page
        │
        ▼
 Simulated Users
        │
        ▼
 Campaign Metrics

 
## Implementation Steps

1. Built the Lab Environment
   - Created a dedicated Windows 11 virtual machine using VMware Workstation.
   - Configured the virtual machine to host all components of the phishing simulation.

2. Installed Gophish
    -  Downloaded and installed the latest Gophish release.
    -  Verified the application was running correctly.
    -  Accessed the Gophish administrative interface through the web console.
    
3. Configured Email Delivery
    -  Installed Mailpit to function as a local SMTP server.
    -  Configured a Gophish Sending Profile using Mailpit as the SMTP relay.
    -  Verified successful email delivery by sending test messages.
      
4. Developed Phishing Content
    -  Designed a custom HTML phishing email template.
    -  Developed a custom HTML landing page to simulate a credential prompt within the authorized lab environment.
    -  Configured campaign tracking to monitor user interactions.
      
5. Created Simulated Users
    -  Created a CSV file containing simulated employee accounts.
    -  Imported the user list into Gophish as a campaign group.
      
6. Launched the Phishing Campaign
   -  Created a phishing campaign using the custom email template, landing page, sending profile, and user group.
   -  Successfully launched the campaign within the lab environment.
     
7. Monitored Campaign Activity
    -  Verified email delivery through Mailpit.
    -  Monitored campaign metrics within Gophish, including:
    -  Email delivery
    -  Email opens
    -  Link clicks
    -  Credential submissions
    -  Confirmed successful tracking and reporting functionality.
      
8. Documented Results
    -  Recorded configuration steps, screenshots, and campaign results.
    -  Documented lessons learned and troubleshooting performed throughout the project.
  
## Key Outcomes
-  Successfully deployed a fully functional phishing simulation environment.
-  Configured a working SMTP relay using Mailpit for secure local email testing.
-  Developed custom HTML phishing emails and landing pages.
-  Executed phishing simulation campaigns using imported user groups.
-  Validated end-to-end campaign functionality, including email delivery, landing page interaction, and reporting.
-  Produced documentation suitable for demonstrating practical cybersecurity and security operations experience in a professional portfolio.
