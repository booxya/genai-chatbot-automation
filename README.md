# GenAI Chatbot Document Processing Automation

## Key Highlights
- Configuration-driven automation (no-code approach)
- Scalable solution across multiple teams
- Reduced manual workload and improved consistency

## Overview
This project presents a configuration-driven automation system designed to support GenAI chatbot solutions by streamlining document processing and management. The system automates document transfer, conversion, and synchronization across SharePoint environments, eliminating manual work and ensuring data consistency.

## Business Problem
- Manual document transfer and conversion were time-consuming and error-prone  
- Documents were often inconsistent or outdated  
- Users needed fast access to structured and historical information  
- Scaling chatbot content across teams required a flexible system  

## Solution
A configuration-driven automation system built using:
- Power Automate (workflow orchestration)
- SharePoint (data source & storage)
- Configuration table (dynamic logic)

Key features:
- No-code / low-code approach  
- Scalable and reusable design  
- Easy to extend without modifying logic  

##  Architecture (Simplified)
[Configuration Table - SharePoint List] -> 
[Power Automate Flow - Orchestration] -> 
[Processing Logic: Conditions, Transformations] -> 
[Target SharePoint Libraries - Chatbot Folders]


##  How It Works

### Configuration-driven logic
Each row defines:
- source  
- target  
- document type  
- file name  
- chatbot destination  

New workflows can be added without changing the flow logic.

### Processing scenarios

**ASPX → PDF**
- Retrieves metadata  
- Generates PDF  
- Saves to target  

**Other files**
- Copies or updates documents  
- Maintains consistency  

### Smart logic
- Checks if file exists  
- Updates or creates new  
- Handles multiple file types  

### Error handling
- Email notifications on failure  
- Stable and predictable execution  

##  Technical Highlights
- Configuration-driven orchestration  
- Conditional branching  
- Dynamic file handling  
- Metadata processing  
- Centralized automation flow  

##  Business Impact
- Reduced manual workload  
- Improved data consistency  
- Lower operational effort  
- Reliable document delivery  
- Scalable across teams  

##  Complexity Handled
- File type differences  
- Metadata handling  
- Conversion logic  
- File synchronization  
- Error handling  

##  Future Improvements
- Monitoring dashboards  
- More document types  
- Adoption tracking  
- Further scalability  

##  Disclaimer
This project is based on a real-world enterprise solution. All details have been generalized and no confidential data is included.

Author: Joanna Wasilenko
