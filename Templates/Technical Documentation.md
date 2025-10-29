# University of Washington
TekSystem

# 251028 SharePoint Migration from SP 2019 to M365 SPO
Created by Go, Richard (TEKSystem)

| Target release |       |	
| --- | --- |
| Epic	| --- |
| Document status	| DRAFT |
| Document owner	| Go, Richard (TEKSystem) |
| Designer	|     |
| Developers	| Colleen, Sharri |
| QA	| Rosemary |
| POC	|  Rosemary |
|  | --  |
|  | --  |

## Goals
- Have a ready-made Dashboard for Executive Leadership use that is dynamic.
- Updated supply information with the most current/updated data for making a better decision on planning and scheduling.
- Usable information on Dashboard without the noise of other data.
- [ ] Need metrics requirements from LT Clancy and Scott (KPIs)

## Background and strategic fit
- The Training Unit just changed their training scheme from a Division like style to Team style training.
  - See User interaction and design / III. Team Structure below.
- ⁠This will reduce the manpower for making training schedule with the updated information from its sources/inventory.
  - Supply, gear, gadgets
  - Individual student's stats and availability
  - Individual instructor's stats and availability
- This centralized data collection from a variety of decentralized data that each department are using.


## Assumptions
- Field User will primarily access this using a Toughbook in the field with no internet access.
  - Data will be stored in an Excel file while in the field.
  - Then, will upload the data once the user gets internet connection.
- May use a CUI portal with no SSN for students and instructors' information. Supply data may be on a public view.
  
💡 We may use the FDR Contract App for this project.



## Requirements
Long Range Training Plan Tracker

- Plan training schedule in a Gantt Chart view 	Must Have	
- Data series added on the chart with updated information from Supply Sources.
- Version control
- Online Resource Tracking

Sources updating data on their portal
Create tools for updating inventory
Must Have	
Supply or sources of gears, ammunition, electronics, etc updates their data on a set schedule given by the Training Managers.

**Resource Managers**
Supply Portal List
Are they using centralized data sets like:

- Cardio
- Pulmonary
- Psychology

Individual student data inputs forms and turn into a Dashboard
Individual instructor data inputs forms and turn into a Dashboard

**Must Have**	
These are data before the students come to UW.

**Students**
Quals
Availability
Status
Gear inventory
Physical
Experiences
Currency
Instructor
Availability
Quals
Grade Sheet

Capture data from the field using 
Upload data from Toughbooks (TB) to SP
Field Training Data Transfer

**Must Have**	
Toughbooks - requested steps by customer
Collect data from TB using Excel
Email the Excel
Upload to FS
Extract data to SP Lists
Produce Dashboard
Naming convention on Excel file will be important to eliminate double entry when we upload to SP Lists. 


**Dashboard** - Data



**Collect useful data broken by**
- Individual Students
- Individual Instructors
- Equipment
- Groups
- Teams
- Dashboard - Power BI




**Page Design**

Functional Homepages with useful links	
Links
Doesn't like showing Document library contents on pages
Page design
Make it functional for users
Create an approval Document Library
Training of personnel



**Not doing**
Target Variable

**Improve readiness score**

**Must Have**	
What is success?


## User interaction and design
#### I. Training Steps

| Steps | Phase  |
| --- | --- |
| Checkin <li>Snapshot | Ultra |
| Classroom <li>Dashboard (PBI)| Mx |
| Field <li>Use of tablet w/o IC <li>Input data on Excel <li>Upload data to SP when IC is available. | Mx |
| Classroom  <li>Mx Phase   |
| Graduate <li>Mx Phase |
| EOD TTC <li>CQT <li>SQT |


#### II. Constant

| Constan/Dynamic |
| --- |
| ***Supply*** <br /> Uses MS Forms or PA <br /> <li>Current status <li>Gear inventory <li>Experiences <li>Quals <li>Physical <li>Medical <li>Currency <li>Classroom   |
| Scheduler <li>Long Range Training Plan <li>Gantt Chart <li>Supply Data | 
| Planner <li>Gantt Chart <li>Dashboard     |

#### III. Team Structure

| Team |   |
| --- | --- |
| Team 1	| <li>Platoon 1 (8 students) <li>Platoon 2 (8 students) <li>10 instructors <li>1 Instructor <li>1 tablet <li>2 students <li>8 ULT (Subjects/course) |
| Team 2	| same as Team 1 |
| Team 3	| same as Team 1 |

#### IV. Action Items

**230627**

- [x] Gemba Walk
- [ ] Grade Sheet
- [ ] Get current data set
- [ ] Google Sheet
- [ ] Toughbooks
- [ ] No IC
- [ ] What data do they collect
- [ ] Integrity of data
- [ ] Resource Managers
- [ ] How are they doing their inventory?
- [ ] How are they reporting to Training Managers?
- [ ] Priority to build (ask Rosemary)
- [ ] Grade Sheet
- [ ] Online Resource Tracker
- [ ] Long Range Training Plan Tracker
- [ ] Snapshot
- [ ] KPI's
- [ ] What is success?
- [ ] Target variable
- [ ] Aggression analysis
- [ ] Get current data set/series
- [ ] What data are they currently using?


## Questions
Below is a list of questions to be addressed as a result of this requirements document:

- What are the metrics requirements from LT Clancy and Scott (KPIs)
- Are the field users will accept the new process for uploading data to SP once IC is established?
- Can you define success? (LT Clancy)


## Resources

- Centralized source of data for creating dashboards and reports
- Can only pull data and has no write capability
- Power BI can pull data using data clusters
- No API connector to FS except PBI
- Gemba Walk	
- Walk through the process to identify data constraints
- Start with Grade Sheets


## Not Doing
- Page Design, responsibility of each department. We can advise.
- Training of personnel for administering the new SharePoint Online. That is the job of each department head, Rosemary.


## Legend:
| Abbv  | Meaning |
| --- | --- |
| IC	| Internet Connection |
| KPI| 	Key Performance Indicator |
vMx	| Maintenance |
| PAP	| Power Apps |
| PAM	| Power Automate |
| PBI	| Power BI |
| SP	| SharePoint |
| TB	| Toughbooks |
| TM	| Training Manager |


## Logs

**251028**	
  - Initial meeting with:
  
  - **UW**
      * Rosemary (IT Head)
      * Colleen (SP Developer)
      * Sharri (SP Developer)
  
  - **TEKSystem**
      * Mikayla (PM)
      * Richard (me)









