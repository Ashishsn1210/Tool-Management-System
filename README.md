# Tool Management System (Application)


## Overview
This project is a Tool Management System built using Google AppSheet to help manufacturing companies track and manage their tools efficiently.

Many factories still track tools using spreadsheets or manual registers which leads to:
- Loss of tools
- Poor inventory visibility
- Untracked tool usage
- Difficult purchase approvals
- Lack of lifecycle tracking

This system digitizes the entire workflow and provides a centralized platform for tool tracking and management.


## Problem Statement
Manufacturing companies manage many tools used in production processes. Without a proper tracking system, companies face challenges such as:
- No visibility of tool inventory
- Difficulty tracking tool issue and return
- Lack of approval workflow for tool requests
- Poor vendor management
- No tracking of tool lifecycle events like regrinding or repairs


## Solution
The Tool Management System provides a digital platform to manage tools across their entire lifecycle.

The system allows users to:
- Maintain a centralized tool database
- Track tool movement
- Create tool indent requests
- Manage vendors and purchase orders
- Track tool lifecycle events
- Automate approval workflows through email


## System Architecture
The application is built using a no-code architecture powered by Google AppSheet with Google Sheets acting as the backend database.

The system architecture consists of:
- AppSheet – Frontend application interface and workflow engine
- Google Sheets – Backend data storage and structured tables  
- Automation Workflows – Trigger-based actions such as notifications and approval processes, Serial Number and Unique ID generation.


## Key Features
- Centralized tool database for maintaining tool information
- Inventory tracking to monitor tool availability
- Tool issue and return tracking for operational control
- Structured data entry forms for consistent data management
- Modular system design for easy navigation and scalability  
- Automated workflows for operational processes  
- Vendor and procurement tracking  
- Lifecycle monitoring of tools including maintenance activities
- Access Control to modules based on user roles


## App Modules

The application is structured into multiple modules to organize different operational functions within the system. Each module represents a specific functional area that helps manage and track various aspects of the tool lifecycle and inventory operations. Each module acts as a dedicated workspace where users can view records, update information, and manage related operations. This approach improves usability, maintains data consistency, and allows the system to scale easily as new features or operational processes are introduced.

![App Modules](https://github.com/Ashishsn1210/Tool-Management-System/blob/main/Images/TMS%20App%20Modules.png)

The system consists of the following modules:
- Tools – Master database of all tools
- Indents – Tool request system
- Inward – Track tool entries into inventory
- Issue / Return – Track tool movement
- Vendors – Vendor master
- Inventory – Tool stock monitoring
- Purchase Orders – Tool procurement tracking
- Life Log – Tool lifecycle history
- Regrind – Tool reconditioning tracking


## Data Entry Form

The application uses structured data entry forms to capture and manage information within the system. These forms provide a user-friendly interface that allows users to input, update, and maintain records in a consistent and organized manner. Each form includes predefined fields designed to ensure accurate data entry while reducing the chances of missing or incorrect information. Validation rules and structured inputs help maintain data integrity across the system. The forms also simplify complex processes by guiding users through the required inputs step by step. This makes the application accessible even for users with minimal technical experience. By standardizing how information is entered into the system, the application ensures reliable data management, improves traceability of records, and supports efficient workflow execution across different operational activities.
These forms act as the primary interface through which users interact with the system, making data management simple, structured, and efficient.

![Entry Form](https://github.com/Ashishsn1210/Tool-Management-System/blob/main/Images/TMS%20Entry%20Form.png)


## System Workflow

The application follows a structured workflow to manage tool operations efficiently.

Typical workflow process:
![System Workflow](https://github.com/Ashishsn1210/Tool-Management-System/blob/main/Images/SystemWorkflow.png)

## Business Impact
This system helped our organization:
- Reduce manual tracking of tools
- Improve inventory visibility
- Prevent loss or misplacement of tools
- Streamline operational workflows
- Maintain structured records of tool lifecycle activities

By digitizing tool management processes, the system improves efficiency, accountability, and operational transparency.


## Future Improvements
- Dashboard for tool usage analytics
- Integration with ERP systems
- QR code scanning for tool tracking


## Application Demo
The following video demonstrates a sample workflow of registering a tool using the Tool Management System.
![App Demo](https://github.com/Ashishsn1210/Tool-Management-System/blob/main/Images/TMS_Demo.gif)
