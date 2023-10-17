# TechRumble_Team_ReportingRockstars
"A Comprehensive Data Reporting Solution for Power BI reports automatic refresh - Featuring a Dimensional Data Model, Power BI Reports, Automatic Refresh with Power Automate, and Interactive Data Input via PowerApps visual in power BI. Empower your data analysis with this end-to-end solution."

**Project Name:** BI REPORTING
## Description
This project is a comprehensive data reporting solution designed for the TechRumble Hackathon. It addresses the need for real time data  reporting, and data input capabilities. The solution includes a dimensional data model, Power BI reports, automatic data refresh through Power Automate, and user data input via PowerApps. It aims to streamline data reporting processes and enhance user interaction with data.
**Automated Data Refresh and Power Automate:**
▪ The heartbeat of our solution is its seamless data refresh mechanism, automated through Power Automate. This ensures that our reports always reflect the latest information, providing real-time insights.
▪ Power Automate Integration: We've integrated Power Automate, a robust workflow automation tool, into our solution. Power Automate allows us to set up triggers that initiate data refresh based on predefined conditions.

**What-If Scenario -Enabling Write-Back Functionality:**
▪ Leveraging dynamic "What If" scenarios (Enabling Write back functionality), users can visualize various outcomes instantly. Moreover, our innovation extends further with PowerApps write-back integration, enabling users to collaboratively modify data within Power BI, solidifying a seamless and empowering reporting ecosystem.

## Features
- **Dimensional Data Model**: A robust data model designed to provide a structured and efficient data foundation.
  ![image](https://github.com/Upendrachary-yelsoju/TechRumble_Team_ReportingRockstars/assets/137254163/c25051c3-bb00-40cb-887c-be699ad99a06)
- **Power BI Reports**: A collection of visually appealing and insightful reports that transform raw data into meaningful insights.
  ![image](https://github.com/Upendrachary-yelsoju/TechRumble_Team_ReportingRockstars/assets/137254163/725bdc4a-5ecf-4ae0-8590-204c0ae97c4b)
- **Power Automate Integration**: An automated workflow that ensures Power BI reports are always up-to-date when data changes occur.
  ![image](https://github.com/Upendrachary-yelsoju/TechRumble_Team_ReportingRockstars/assets/137254163/2cca1ffe-cea7-46e5-8cb5-f5957d90da7f)
- **PowerApps Integration**: A user-friendly interface allowing users to input, edit, and delete data, with seamless integration into Power BI reports.
## Overall Technical Architecture
![image](https://github.com/Upendrachary-yelsoju/TechRumble_Team_ReportingRockstars/assets/137254163/0bbda846-7e09-401f-964f-9b4d3cc9bd6e)
1.ETL -Extracting transforming and Loading Data into SQL dB from AWS S 3 bucket
2.Getting the data from SQL server to power BI and then generating the comparative reports for the data
3.Automating Refreshing Process Configuring the SQL triggers “when an item is modified”modified”//“when an item is created” in power automate and then Configuring the action for power bi refresh
4.Write back to power bi dashboard dragging the power apps from power bi visuals then selecting the necessary columns creating an app by selecting the same SQL dB as a source Now the interface to enter the inputs will be reflected in to power bi dashboard The visuals of reports changes whenever there is a change in data

  ## Table of Contents
- [Installation Instructions](#installation-instructions)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributors](#contributors)
- [License](#license)
- [Screenshots or Demo Links](#screenshots-or-demo-links)
- [Contact Information](#contact-information)

## Installation Instructions
To set up and run this project locally, follow these steps:
1. Clone this repository to your local machine using `git clone <repository_url>`.
2. Navigate to the relevant sections to configure and run:
   - **SQL QUERIES**: Follow the SQL scripts provided in the `SQL Queries` directory.
   - **Power BI Reports**: Open the `PowerBI_Reports` folder and access the Power BI DAX functions for specific Measures .
   - **Power Automate Integration**: Explore the `PowerAutomate_Flow` for the configuration details.
   - **PowerApps Integration**: Find the PowerApps Formulas included in app designing in the `PowerApps_App` directory.
3. Ensure that you have the necessary dependencies and technologies (listed below) installed.

## Usage
To use this project, follow these steps:
1. Access the Power BI reports to gain insights from your data.
2. Use the integrated PowerApps app to input, edit, and delete data.
3. Observe how the Power Automate flow ensures the reports are updated when data changes occur.

## Technologies Used
This project utilizes the following technologies, frameworks, and libraries:
- AZURE SQL Server for the dimensional data model
- Power BI for report creation
- Power Automate for Automatic refresh workflow automation
- PowerApps for user data input

## Contributors
- [Yelsoju Upendra Chary](https://github.com/Upendrachary-yelsoju) - Project Member1
- [Marada Rajeswari ] -Project Member2


## Execution Screenshots or Demo Links
- ![image](https://github.com/Upendrachary-yelsoju/TechRumble_Team_ReportingRockstars/assets/137254163/be17a47d-92bb-4d05-9d57-822fc9f83914)
- ![image](https://github.com/Upendrachary-yelsoju/TechRumble_Team_ReportingRockstars/assets/137254163/1ddbf47f-2160-4ef7-921b-1e77c64ea682)
- ![image](https://github.com/Upendrachary-yelsoju/TechRumble_Team_ReportingRockstars/assets/137254163/455e6c8e-8e9d-40eb-91fa-d640a919e4b8)
- ![image](https://github.com/Upendrachary-yelsoju/TechRumble_Team_ReportingRockstars/assets/137254163/aa4e923e-3883-422a-abf7-984d88b9d610)
- ![image](https://github.com/Upendrachary-yelsoju/TechRumble_Team_ReportingRockstars/assets/137254163/db2e5cf0-1d85-462d-9f94-6a4485d09e2c)

## Contact Information
If you have questions, suggestions, or want to collaborate on this project, feel free to contact us:
- Email: yelsojuupendrachary@gmail.com
- GitHub: https://github.com/Upendrachary-yelsoju


