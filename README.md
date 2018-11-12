

## Hardware Requirements & Supported Devices

>Hardware requirements

 Dynamics is a client (web application) which has various hardware requirements. The overall minimum requirements is a 1.9ghz processor, 2GB or Memory and a minimum resoultion (Super VGA) of 1024 x 768. You wont be able to see the application as it is. Changes occur during various releases. 


>Supported Broswers 

I.E. 10 is not suppoeted for windows 10, 8,1 but is supported for windows 8 and 7. Use IE 11 for windows 10 and 8.1. And lastly you can use Microsoft Edge with Windows 10 only.
- Mozilla firefox (latest publically-released version) running on Windows 10, 8.1, 8 or 7 
- Google Chrome (latest publically-released version) running on Windoes 10, 8.1, 8, 7 and Andriod 10 tablets 
- Apple Safari (latest publically-released version) running on Max OS X 10.8, 10.9, 10.10 or the Apple Ipad

> Outlook Client 

- OS: Windows 7, 8 and 10
- MS Office: Office 365, Office 2016, Office 2013, or Office 2010
- Web Broswer: IE, 10 or 11
- Outlook client: Needs installation & Supports Offline Features 
- Outlook App: No installation & Works with OWA 

!> Latest updates can be found at https://technet.microsoft.com/en-us/library/hh699710.aspx/

## Deployment of Microsoft Dynamics & Editions

The best place to find out what is new, whats in development and whats been previously released, can be seen in the business roadmap. 

<b> Business Edition is optimised for 10-250 Employees. Enterprise Edition is optimised for 250+ Employees. </b>

> Business Edition

The Business edition includes Sales, Marketing and Financials. 
- Its optimised for 10-250 employees
- Sales: Dynamics CRM sales
- Marketing
    - Email marketing
    - Landing pages
    - Webinars
    - Lead management & Campaign Designer 
- Financials
    - Finance and Accounting
    - Sales
    - Purchasing 
    - Basic Inventory Management
    - Basic Transfer 

> Enterprise Edition 

- Sales
- Customer Insights
- Customer Service
- Feild Service
- Project Service Automation
- Finance and Operations
- Retail
- Talent 

## Deployment Plan for Clients 

> User License type

Full Access: Full access to business apps
- Apps based
    - Individual business apps like sales, customer service, operations, etc. 
- Plans Based
    - (Customer engagement plan, Microsoft Dynamics 365 plan, etc.). Includes all Applications (Also known as Enterprise Edition with Plan Based Licensing)

Team Members: Light users
- Consume data or reports
- Complete tasks like Time & Expense Entry etc.
- Team Member license is assigned. 

Device Licensing: For share device scenarios. 

The Plan is more cost effective the buying individual apps. It also makes it easier to scale later on. 

- Using Microsoft Dynamics NAV or AX? Plan for Migration to Dynamics 365 Financials And Operations. 
- Using another Software - Identify Functionalities to use in microsoft Dynamics 365. 

> Questions to consider

- You might need to also reconsider business processes mapping. This will improve business processes and standardise them. 
- How many users will be using Dynamics 365?
- What will be the roles of those users? (Consider roles & responsibilities mapping)
- Data migration strategies and plan 
- Downtime planning and backlog
- Create a detailed project plan
- Consult existing partnet or appoint a new partner
- Planning is critical before you start!

## Data Import Planning 

> Questions to ask the customer & Best Practices 

- Whats the data source? (CRM On-Premise or other systems)
- How much data to import? (Master data, Transactional data, or All data)
- Data availability in the required format? (for importing the data)
- Data cleansing (You need to cleanse the data before you import)
- Duration for the Data Import? (This is always depended on how much data you have)-
- Are we importing everything or doing some manual data entry?
- Check the state of the record before importing the data. ( Finalised data can not be imported)
- Downtime planning (Data import can take a long time so this is something you need to consider.)

> Importing Data, supported methodologies 

- If you have a small amount of data you can manually enter the data
- Import data wizard. Import CSV files, map fields etc.
- Data Loader Service  (Dependent on region location)
- Using SDK (This requires programming and can be quite complex to import your data) 
- Various third party tools such as Scribe. 

> Data Loader Service

- Data from On-remise solution to Dynamics 365 (You will need to use Azure)
- Data is stored in Azure (mainly for large volume migration)
- Avoids writing code or 3rd part yools for migration 
 
!> It's important to note that data (Millions of Records or Huge data) must be available in Azure in the same tenant as Dynamics 365 to use Data Loader Service. If it's not in Azure & same tenant, Data Loader Service cannot be used.


## How To Sign Up and Cancel Subscriptions 

- You get a free 30 day trial
- Dont need to use a Credit Card
- You can cancel anytime
- You get access to Office 365 Admin Center 
- An Office 365 subscription is not needed for Dynamics 365

!> Go to https://trials.dynamics.com/ to sign up for a dynamics trial

For development purposes use the option which states "Are you signing up on behalf of a customer or using this trial for development purposes?"

- Once the country/region is chosen, you cannot change. 

## Manage Users and Security Roles

- You can add users within the Office 365 Admin Center 
- You can manage subscriptions in the Office 365 Admin Center
- Assign administrative rights in Office 365 Admin Center
- Then you can assign a licence in office 365 to a user
- After the user is created in office 365 admin center, it automatically synchronises with dynamics 365. 
- At least one security role is required for the user to start using Dynamics 365 

 Within Dynamics to assign a security role 
```Settings > Security > Users > Add a role to the user ``` 

- The office 365 Users & Active Directory Users are different
- Users will need to manage 2 accounts 
- To reduce administration effort, Sync Azure AD & Internal AD
- You need: to configure ADFS & Enable SSO.
- After SSO Implementation:
    - Single Account is used to login Dynamics 365 & Internal Applications
    - No need to remember 2 account details.
    - Seamless access to Dynamics 365.
    - Single point to administer user & Security 