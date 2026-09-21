
## Hostel allotment
### Required Data
- Building Data
	- Building number
	- Hall Name
	- Capacity
	- Floors
	- Rooms
		- Room number
		- Room state (under Construction, vacant, occupied )
		- Accommodation Capacity
		- Residing students id
		- number of occupants 

---
# Identify
## Stakeholders
### 1. Students
#### Tasks or Actions
### 2. Hostel Office
#### Job Role: ___
#### Tasks or Actions
## Functional Requirements
- Choice filling
	- Floors
	- Single/Double sharing room
	- roommates
- Complaints
	- Status
	- Expected time
- Contact Details of Respective Authorities
	- Caretaker
	- Warden
	- Electrician
	- Plumber
	- Carpenter
	- HR
	- MR
	- etc...


# Users/Stakeholders
1. Students
2. Skilled Personals(Staff)
	1. Electrician
	2. Data Center
	3. Carpenter 
	4. Sweeper
	5. Plumber
3. Authorities
	1. Caretaker
	2. Warden
	3. Chief warden
# Domain
## Models
1. Student
2. Authorities
3. Skilled Personals (Staff)
	1. Buildings
	2. Building id
	3. Building name
	4. Building number
	5. Hall Name
	6. Capacity
	7. Floors
	8. Rooms
		- Room number
		- Room state (under Construction, vacant, occupied )
		- Accommodation Capacity
		- Residing students id
		- number of occupants 
5. Complaints
	1. Complaint lodger
	2. Complaint type
		1. Room 
		2. Shared Spaces
	3. Well described issue
	4. Attachments if any (Photos, videos) 
	5. Feedback 



## Complaint on Space
### Room
 - Sanitation 
	 - Mopping and Sweeping
	 - spider webs
	 - Mosquitos/Honey bees/insects etc...
 - Carpentry related 
	 - Bed
	 - cupboards
	 - latches
	 - room doors
	 - study chairs
	 - study tables
	 - windows 
 - Electricity related 
	 - Fan
		 - speed
		 - Not working
	 - Light
		 - bulb or tube light
		 - not working
	 - power cut
	 - switch board
	 - others
 - LAN
	 - speed
	 - not working
 - Civil work
	 - Tiles in room
	 - Water Seepage
	 - Drainage

### Shared Spaces
 - Sanitation 
	 - washroom
	 - Corridors
	 - steps
	 - Lift
	 - Dustbins (Waste Collection)
	 - Mosquitos/Honey bees/insects etc...
	 - Drainage clear
	 - Hygiene water issues
 - Carpentry related 
	 - washroom doors
	 - Washroom windows
	 - Washroom Mirrors
 - Electricity related 
	 -  Washing machine (If available )
	 - Exhaust Fan
		 - speed
		 - Not working
	 - Light
		 - bulb or tube light
		 - not working
	 - power cut
	 - switch board
	 - others
 - Plumber
	 - Water Clogging
	 - water supply
	 - water taps
	 - Flush
	 - Shower
	 - Drinking water
 - Civil work
	 - painting
	 - Tiles in room
		 - water seepage
- Hostel Ambience
	- Brach Cutting
	- Gardening
	- Sitting
	- Grass cutting
	- Others


# Existing Solution
## Complaint Form

<img width="1030" height="842" alt="image" src="https://github.com/user-attachments/assets/73832d48-d216-426d-9a25-b73ac2a34906" />

## Complaint Registry
<img width="1890" height="622" alt="image" src="https://github.com/user-attachments/assets/4e56c278-5590-4fbc-896d-13d663342054" />


## Issues with existing Solution
1. No Complaint status
2. No choice for roommates/mess etc...
3. Expected visits of skilled personals 
4. Each personals will have there dashboards showing respective information's
	- increasing transparency
	


# PPT Format
Title
Project title
Adv. and applications
limitations in prior/current available version



- Student Hierarchy

# PPT
## Title: Hostel Management
### The Problem Scenario
- Management isn't aware about the vacant rooms
- Complaints are one way communications
- No Prior Information about the visits
- They might come when you are unavailable
### The Available Solutions
- ERP
### Problems with Available Solutions
- Roommate changes is not reflected in the ERP
- No Complaint No. assigned
- No Limited Time Frame for Solutions
- No contact Details of Skilled Personals in ERP
- No way of knowing the complaint is assigned to someone
### Our Solution (What we Bring to the table)
#### Functionalities
###### For Students
- Centralized Complaint System
	- With Status
- Allocations Details
- Choice Filling (Mess, Hostel)
- Prior notification regarding Skilled Personals visit
- Authorities will be in the loop and will know the number of problems unresolved
###### For Authorities
- no. of Vacant Rooms and room details
- Pending Issues to be resolved
- Connected to the Ground reality

# Hostel Data
- Hostel Authority Structure
	- Chief Warden
		- Wardens (Warden and Assistant warden)
			- Caretaker
			- HR

| S.No | Hall of Residence           | No. of Rooms | Single/Double         | Total Capacity |
| ---- | --------------------------- | ------------ | --------------------- | -------------- |
| 1    | Azad Hall                   | 100          | Single                | 98             |
| 2    | Bose Hall                   | 100          | Single                | 98             |
| 3    | Ambedkar Hall               | 48           | Double                | 94             |
| 4    | Babha Hall                  | 48           | Double                | 94             |
| 5    | Gandhi Hall                 | 48           | Double                | 94             |
| 6    | Gokhale Hall                | 48           | Double                | 94             |
| 7    | Radhakrishnan Hall          | 48           | Double                | 94             |
| 8    | Raman Hall                  | 48           | Double                | 94             |
| 9    | Nehru Hall                  | 100          | Single                | 98             |
| 10   | Patel Hall                  | 100          | Single                | 98             |
| 11   | Tagore Hall                 | 48           | Double                | 94             |
| 12   | Viswesvraya Hall            | 48           | Double                | 94             |
| 13   | Rajendra Prasad Hall        | 202          | Single                | 198            |
| 14   | Vikram Sarabhai Hall        | 150          | Single                | 198            |
| 15   | Kakatiya Hall of Residence  | 1050         | Single                | 1050           |
| 16   | Ramappa Hall of Residence   | 1194         | Single-640 Double-554 | 640+1108 =1748 |
| 17   | International Students Hall | 150          | Single                | 150            |


| S.No | Hall of Residence  | No. of Rooms | Single/Double | Total Capacity |
| ---- | ------------------ | ------------ | ------------- | -------------- |
| 1    | Priyadarshini Hall | 75           | Triple        | 225            |
| 2    | Sarojini Hall      | 65           | Double        | 130            |
| 3    | New LH-A           | 120          | Single        | 120            |
| 4    | New LH-B           | 110          | Single        | 110            |
| 5    | New LH-C           | 90           | Single        | 90             |



