# GDS-OTC-Settlement-Alteryx-Project---Client-Vs-Broker-File-Reconciliation
# Project Summary:
## This project involves a recurring weekly process for our external client, covering products such as NP (New Product) and MSTR (Multi Strategy Total Return). Our team is responsible for maintaining a running Excel tracker to monitor & track the client’s OTC settlement activities. The task focuses exclusively on reviewing and validating agreed and released payments for the week, pertaining to a single broker portfolio account.

# Problem Statement:
## This project focuses on the manual OTC derivatives settlement process executed weekly for external clients. The process is time-consuming and prone to human errors due to manual intervention. Additionally, there exists a potential data-security risk if incorrect account details are inadvertently included, as the settlement information is shared with the external counterparty’s (Broker) portfolio accounting team via email.

# Alteryx Workflow Automation - GDS Broker vs Client Reconciliation:
# Key Steps & Contributions in Alteryx Workflow:

## 1.  Prepared the Business Requirement Document (BRD) and obtained approval from senior management for project initiation.
## 2   Gathered pre-requisite data from internal teams and began workflow development in Alteryx.
## 3.  Designed the workflow with three core stages - Input, Processing, and Output stages.
## 4.  Integrated upstream data inputs (Excel or CSV files) into Alteryx, processed them through configured logic, and generated reconciled outputs automatically in a designated shared drive output folder.
## 5.  Built a multi-level reconciliation process leveraging key fields such as Alert Code, Broker Code, Account, Quantity, Price, and Direction.
## 6.  Submitted a baseline request with a unique project number for deployment approval.
## 7.  Conducted demos for both management and the Alteryx governance team prior to workflow publication in the Alteryx Gallery.
## 8.  Supported UAT (User Acceptance Testing) and facilitated smooth migration to production.
## 9.  Upon Go-Live, end users could directly access the automated workflow from the Alteryx Gallery, achieving:
##                                a.  1.15 hours saved per week.
##                                b.  Reduced data breach risks.
##                                c.  Enhanced overall process efficiency.

# Project Highlights & conclusion:
## 1.  Eliminated manual touch points.
## 2.  Reduced data breach risk by removing manual data handling and improving process governance.
## 3.  Minimized turnaround time through reduced email communication between BNY and the Broker Fund Accounting Team, enhancing both efficiency and data security.
## 4.  Achieved a time savings of approximately 90 minutes per week, equivalent to 0.20 FTE efficiency gain.
## 5.  Improved processing time significantly — reduced from 2 hours to just 5 minutes per week.
