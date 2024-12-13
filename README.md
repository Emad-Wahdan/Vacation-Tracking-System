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

## Non-Functional Requirements  
Highlight the qualities and constraints of the system.  
*(e.g., The system should handle up to 1,000 concurrent users and respond to requests within 2 seconds.)*

---

## Constraints  
List any constraints or limitations of your system.  
*(e.g., The system will only support employees within the company domain.)*

---

## Use Cases  

### 5.1 Manage Time Use Case  
#### 5.1.1 Create Request  
Employees can submit a vacation request by specifying the desired dates and type of leave.  

#### 5.1.2 Withdraw or Edit Pending Request  
Employees can modify or withdraw vacation requests that have not yet been approved.  

#### 5.1.3 Cancel Approved Request  
Approved vacation requests can be canceled before the vacation start date.  

---

## Data Model  
Provide an overview or diagram of the data structure used in your system.  
*(Consider using diagrams such as an Entity-Relationship Diagram for clarity.)*  

---

## Pseudocode  
Include high-level pseudocode or flowcharts that outline the system's logic.  
*(e.g., Provide steps for submitting and approving requests.)*  

---
