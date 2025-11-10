# SAP-ABAP-Employee-Leave-Management
SAP ABAP mini project implementing an Employee Leave Management System using Data Dictionary, Function Modules, ALV Reports, and Table Maintenance Generator (TMG).
Upload the following:

**📘 Employee Leave Management System (SAP ABAP Project)**
🧩 **Overview**

The Employee Leave Management System (ELMS) is a SAP ABAP mini project designed to automate and simplify the leave management process for organizations.
The system integrates core ABAP components — Data Dictionary, Function Modules, ALV Reports, and Table Maintenance Generator (TMG) — to provide complete CRUD functionality and real-time reporting.

**⚙️ Key Features**

Custom transparent table (ZELM_LEAVE) for storing employee leave data

Function Module (Z_FM_ELM_CREATE) for automated Leave ID generation

ALV Reports (ZELM_RPT) for detailed leave summaries

Table Maintenance via SM30 for easy admin control

Validation and error-handling logic for accurate record creation

**🧠 Technical Stack**
Component	Description
Platform	SAP ECC 6.0 / S/4HANA 1909
Language	ABAP (Advanced Business Application Programming)
Database	SAP HANA
Frontend	SAP GUI / ALV Reports
Transactions Used	SE11, SE37, SE38, SE80, SE16N, SM30
Testing Tools	Data Browser (SE16N), TMG (SM30)

**🏗️ Modules Implemented**

Data Dictionary Objects (ZELM_LEAVE, Domains, Data Elements)

Function Module – Z_FM_ELM_CREATE

Include Program – ZELM_INCL_DB

Report Program – ZELM_CREATE_UI

ALV Report – ZELM_RPT

Module Pool Program – ZELM_MGNT

Table Maintenance Generator (TMG)

**📸 Output Screenshots**

Screenshots demonstrating each stage of project implementation:

Output 1 – Custom table structure

Output 2 – Technical settings

Output 3 – Module Pool execution

Output 4 – Include program logic

Output 5 – Report input screen

Output 6 – Function Module execution

Output 7 – ALV Report output

Output 8–11 – TMG, SE16N validation, and maintenance proofs

**🔍 Testing and Validation**

The project was tested using:

SE11/SE16N: Verified data consistency

SM30: Validated CRUD operations

ALV Reports: Confirmed accurate display and totals

FM Execution (SE37): Checked Leave ID generation

**🚀 Future Enhancements**

Integration with SAP Smartforms for automated leave reports

Workflow approval for multi-level leave authorization

Email notifications to HR and employees

🧑‍💻 Developer

Karthik S
http://www.linkedin.com/in/contactkarthik-s
