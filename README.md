# Vacation-Tracking-System

## Table of Contents
1. [Vision](#vision)  
2. [Functional Requirements](#functional-requirements)  
3. [Non-Functional Requirements](#non-functional-requirements)  
4. [Constraints](#constraints)  
5. [Use Cases](#use-cases)  
   - [5.1 Manage Time Use Case](#51-manage-time-use-case)  
      - [5.1.1 Create Request](#511-create-request)  
      - [5.1.2 Withdraw or Edit Pending Request](#512-withdraw-or-edit-pending-request)  
      - [5.1.3 Cancel Approved Request](#513-cancel-approved-request)  
6. [Data Model](#data-model)  
7. [Pseudocode](#pseudocode)  

---

## Vision  
The primary objective of this application is to enhance the organization's internal business processes, particularly by streamlining and accelerating the management of vacation time requests. By minimizing manual intervention and improving efficiency, the system aims to provide a seamless experience for both employees and managers.

---

### Functional Requirements  

1. **Rules-Based System**  
   The system operates based on predefined rules to ensure consistency and compliance.

2. **Manager Approval (Optional)**  
   Managers can approve or reject vacation requests as needed, with approval functionality being optional.

3. **E-Mail Notifications**  
   Automatic email notifications are sent to both managers and employees regarding the status of vacation requests.

4. **Authentication**  
   The system leverages the portal’s single-sign-on mechanisms for secure and seamless authentication.

5. **Activity Logs**  
   Comprehensive activity logs are maintained for all transactions to support auditing and transparency.

6. **HR and System Administration Overrides**  
   HR and system administrators have the ability to override rules, with all overrides being logged for auditing purposes.

7. **Awarding Personal Leave Time**  
   Managers can directly award personal leave time to employees when necessary.

8. **Integration Services**  
   The system integrates with other organizational services to ensure seamless data flow and functionality.


---

### Non-Functional Requirements  

1. **Uses Existing Hardware and Middleware**  
   The system must operate effectively with the organization's existing hardware and middleware infrastructure.

2. **Ease of Use**  
   The system should be intuitive and easy to use for all employees and managers, ensuring a smooth user experience.


---

### Constraints  

1. **Integrations**  
   The system must integrate with existing organizational systems and services.

2. **Legacy Hardware**  
   The system needs to be compatible with older hardware systems in use by the organization.

3. **Single-Sign-On**  
   The system must support single-sign-on for authentication across platforms.

4. **User Experience**  
   The system should respect the existing fonts, styles, and design patterns to maintain consistency with the main project.


---

## Use Cases  
### **Use Diagram**
![Use Case Diagram](https://github.com/user-attachments/assets/bc07b6d3-e49b-4529-a072-f1edb1f8c848)

### **Actors & Activities**

#### **1. Managers**
  - **Approve Request**
  - **Award Time**

#### **2. Employees**
  - **Manage Time**

#### **3. HR**
  - **Edit Employee Record**
  - **Manage Locations**
  - **Manage Leave Categories**
  - **Override Leave Record**

#### **4. System Admin**
  - **Backup System Logs**

 ---
### 5.1 Manage Time Use Case  
#### 5.1.1 Create Request  
- **Goal** :
 Employees can submit a vacation request by specifying the desired dates and type of leave.  

- **Preconditions** :
The employee is authenticated by the portal framework and identified as an employee of the company with privileges to manage his or her own vacation time.

- **Flow Chart**
![Create Request drawio](https://github.com/user-attachments/assets/c6bc4cd6-aea3-4561-bc7e-24bd2bb357c4)
---
#### 5.1.2 Withdraw or Edit Pending Request  
Employees can modify or withdraw vacation requests that have not yet been approved.  

#### 5.1.3 Cancel Approved Request  
Approved vacation requests can be canceled before the vacation start date.  

---

## Data Model  


---

## Pseudocode  


---
