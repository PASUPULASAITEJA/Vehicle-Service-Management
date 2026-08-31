# 🚗 Vehicle Service Management Application

**National Internship Program (NIP) - Pega Platform Project**

---

##  Project Overview

**Vehicle Service Management** is a Pega Platform application built for UrbanFleet Operations to streamline vehicle service requests from submission to completion. The application enables customers to raise service requests, allows service advisors to inspect vehicles and generate estimates, captures customer approvals, and assigns technicians for service execution.

### 👨‍💻 Developer
- **Name:** PASUPULA SAI TEJA
- **College:** SVKM's NMIMS deemed to be University Hyderabad
- **Course:** [Your Course]
- **State:** Telangana
- **Email:** [Your Email]

---

## 🎯 Project Objectives

- Allow customers to raise vehicle service requests
- Enable service advisors to inspect vehicles and provide estimates
- Capture customer approvals before service execution
- Assign technicians and track service completion
- Implement SLA-driven prioritization
- Automate notifications and work distribution

---

## 🏗️ Application Architecture

### Application Details
- **Application Name:** NIP-VehicleService-PASUPULA-SAI-TEJA
- **Case Type:** Vehicle Service Request
- **Blueprint ID:** BP-2423183
- **Industry:** Automotive/Transportation
- **Organization:** UPlus

### Case Lifecycle Stages
1. **Submit** - Customer submits vehicle service request
2. **Inspection** - Service advisor performs inspection and generates estimate
3. **Approval** - Customer reviews and approves/rejects estimate
4. **Service Execution** - Technician assigned and service performed
5. **Resolution** - Service completed and customer notified

---

## ✨ Features Implemented

### User Stories Completed (10/10)

✅ **US-001:** Submit Vehicle Service Request  
✅ **US-002:** Perform Vehicle Inspection  
✅ **US-003:** Generate Service Estimate (with auto-calculated Total Cost)  
✅ **US-004:** Approve Service Estimate  
✅ **US-005:** Maintain Vehicle Data (reusable data object)  
✅ **US-006:** Review Service Estimate  
✅ **US-007:** Auto Assign Technician  
✅ **US-008:** Notify Service Completion (Email correspondence)  
✅ **US-009:** Define Service SLA (Goal: 2 days, Deadline: 3 days)  
✅ **US-010:** Route by Vehicle Type (HeavyVehicleQueue/LightVehicleQueue)

---

## 🔧 Technologies & Tools Used

- **Pega Platform** - Low-code application development
- **Pega Blueprint** - Application design and scaffolding
- **Pega App Studio** - Application configuration
- **Pega Dev Studio** - Advanced rule configuration

---

##  Key Components

### Data Objects
- **Vehicle** - Vehicle ID, Model, Type
- **Customer** - Customer details
- **Service Estimate** - Labor Cost, Parts Cost, Total Cost
- **Technician Assignment** - Routing and assignment details

### Business Rules
- **CalculateTotalCost** - Declare Expression for cost calculation
- **RouteByVehicleType** - Decision Table for work queue routing
- **ServiceCompletionEmail** - Correspondence rule for notifications

### Work Queues
- **HeavyVehicleQueue** - For heavy vehicle service requests
- **LightVehicleQueue** - For light/sedan vehicle service requests

### Personas
- Customer
- Service Advisor
- Technician

---

##  Installation & Setup

### Prerequisites
- Pega Platform access (Pega Academy instance)
- Pega Blueprint portal access

### Setup Instructions
1. Access Pega Academy: https://academy.pega.com/mission/business-architect/v8/exercise
2. Initialize Pega instance
3. Build application from Blueprint (BP-2423183)
4. Configure application settings:
   - Application Name: NIP-VehicleService-PASUPULA-SAI-TEJA
   - Organization: UPlus
   - Division: Consumer
   - Unit: Fraud

---

## 📸 Screenshots

### User Story Screenshots
- US-001: Submit Vehicle Service Request
- US-002: Perform Vehicle Inspection
- US-003: Generate Service Estimate
- US-004: Approve Service Estimate
- US-005: Maintain Vehicle Data
- US-006: Review Service Estimate
- US-007: Auto Assign Technician
- US-008: Notify Service Completion
- US-009: Define Service SLA
- US-010: Route by Vehicle Type

*(Screenshots available in the submission document)*

---

## 📊 Business Impact

- **Efficiency:** Automated workflow reduces manual processing time
- **Transparency:** Real-time visibility into service request status
- **Customer Satisfaction:** Automated notifications and clear communication
- **Quality:** SLA enforcement ensures timely service completion
- **Scalability:** Reusable data objects and configurable rules

---

## 🎓 Learning Outcomes

- Case lifecycle design and configuration
- Data modeling with reusable data objects
- Business rule implementation (Declare Expressions, Decision Tables)
- SLA configuration and urgency management
- Correspondence rule creation
- Work queue routing and assignment
- Blueprint-driven application development

---

## 📄 Submission Details

- **Submission Document:** VehicleService_PASUPULA_SAI_TEJA.docx
- **Pega Instance URL:** [Your Pega Instance URL]
- **Operator Name:** PASUPULA SAI TEJA
- **Submission Date:** [Date]

---

## 🔐 Access Information

**Demo Credentials:**
- Username: author@uplus
- Password: pega123!

**Custom Operator:**
- Operator ID: PASUPULA.SAI.TEJA
- Name: PASUPULA SAI TEJA

---

## 📞 Contact

For any queries regarding this project, please contact:
- **Email:** [Your Email]
- **LinkedIn:** [Your LinkedIn Profile - Optional]

---

## ⭐ Acknowledgments

- **National Internship Program (NIP)** - For providing this learning opportunity
- **Pega Academy** - For the Pega Platform training and resources
- **Pegasystems** - For Pega Blueprint and development tools

---

**© 2026 PASUPULA SAI TEJA - National Internship Program Project**
