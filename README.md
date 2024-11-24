<p align="center">
  <img src="hstu_logo_.png" alt="hstu_logo_.png" width="250" height="300">
</p>
<h1 align="center">
  <b>CrowdDrop: A Crowdsourced Delivery System</b>
</h1>
<h3 align="center">
  <br>
  <b>Level-3 Semester-I Project Report</b>  
</h3>
<h3 align="center">
  Course Code: CSE 305 
  Course Title: Software Engineering
</h3>
<br>
<h3 align="center">
  Submitted by 
</h3>
<h3 align="center">
<b>Eusha Sarwar Utal (ID: 2102045) </b> </h3>
<br>

<h3 align="center">
  Submitted To 
</h3>

<h3 align="center"><b>Pankaj Bhowmik  </b></h3>
<h3 align="center"><b>Lecturer, Department of CSE</b></h3>
<br>
<h3 align="center"> <b>Department of Computer Science and Engineering </b></h3>
<h3 align="center"><b>Hajee Mohammad Danesh Science and Technology University  
Dinajpur-5200</b></h3>

  ---

## **Table of Contents**
1. [Introduction](#1-introduction)
2. [Selected SDLC Model: Agile](#2-selected-sdlc-model-agile)
3. [Project Phases](#3-project-phases)
   - [Sprint 1: Planning](#31-sprint-1-planning)
   - [Sprint 2: Requirement Analysis](#32-sprint-2-requirement-analysis)
   - [Sprint 3: System Design](#33-sprint-3-system-design)
   - [Sprint 4-6: Development](#34-sprint-4-6-development)
   - [Sprint 7: Testing](#35-sprint-7-testing)
   - [Sprint 8: Deployment](#36-sprint-8-deployment)
   - [Sprint 9: Maintenance](#37-sprint-9-maintenance)
4. [Risk Management](#4-risk-management)
5. [Conclusion](#5-conclusion)
6. [References](#6-references)
---

## **1. Introduction**
CrowdDrop is a crowdsourced delivery system aimed at connecting senders and deliverers via an efficient, user-friendly platform. The system leverages the power of the crowd to fulfill delivery requests, ensuring fast, cost-effective, and reliable service.

### **Objective**
To develop a scalable, user-friendly crowdsourced delivery system that:
1. Matches senders with deliverers in real-time.
2. Tracks deliveries dynamically.
3. Ensures transparency and reliability via user ratings and secure payment systems.

---

## **2. Selected SDLC Model: Agile**
### **Why Agile?**
- **Iterative Development**: Enables continuous improvement through sprints.
- **Flexibility**: Adapts to changes in user requirements or market conditions.
- **Collaboration**: Encourages stakeholder involvement at every stage.
- **Transparency**: Allows frequent updates and reviews with stakeholders.

---

## **3. Project Phases**

### **3.1. Sprint 1: Planning**
#### Deliverables:
1. Requirements gathering with stakeholders.
2. Creation of User Stories:
   - **As a sender**, I want to request a delivery with specific details.
   - **As a deliverer**, I want to view and accept delivery requests.
3. Initial backlog creation.

#### Tools:
- JIRA/Trello for task management.
- Figma for UI/UX wireframing.

---

### **3.2. Sprint 2: Requirement Analysis**
#### Deliverables:
1. Define functional and non-functional requirements:
   - **Functional**: Real-time matching, delivery tracking, payment gateway.
   - **Non-Functional**: Scalability, security, user-friendly UI.
2. Establish roles and permissions for senders, deliverers, and admins.
3. Document APIs for backend/frontend communication.

#### Tools:
- Lucidchart for process diagrams.
- Swagger for API documentation.

---

### **3.3. Sprint 3: System Design**
#### Deliverables:
1. **Architecture**: Design a cloud-based microservices architecture.
2. **Database Schema**:
   - Users: Sender, Deliverer, Admin.
   - Delivery Requests: Pickup/Dropoff locations, status.
   - Transactions: Payment details.
3. **Prototypes**:
   - Design high-fidelity UI/UX screens.
4. Security Measures:
   - OAuth 2.0 for authentication.
   - Data encryption for sensitive information.

     ![uml](https://github.com/user-attachments/assets/ee903b52-3321-44ec-a6d3-2287db7346c9)


#### Tools:
- AWS for architecture design.
- MySQL/PostgreSQL for database design.
- Adobe XD/Figma for UI mockups.

---

### **3.4. Sprint 4-6: Development**
#### Deliverables:
1. **Backend Development**:
   - Node.js/Express for API creation.
   - Integration of Google Maps API for route optimization.
2. **Frontend Development**:
   - React/Next.js for a responsive web interface.
   - React Native for cross-platform mobile apps.
3. **Key Features**:
   - User Registration/Login.
   - Delivery Request and Acceptance.
   - Real-Time Tracking.
   - Secure Payments.

#### Tools:
- VS Code for coding.
- Postman for API testing.

---

### **3.5. Sprint 7: Testing**
#### Deliverables:
1. **Unit Testing**:
   - Test individual components/modules.
2. **Integration Testing**:
   - Test APIs with frontend and backend.
3. **User Acceptance Testing (UAT)**:
   - Gather feedback from beta users.
4. **Performance Testing**:
   - Ensure scalability for high traffic.

#### Tools:
- Selenium for automated UI testing.
- JMeter for performance testing.

---

### **3.6. Sprint 8: Deployment**
#### Deliverables:
1. Deploy the system on cloud services (AWS/GCP).
2. Ensure CI/CD pipelines for smooth updates.
3. Monitor system performance using logging tools like ELK stack.

---

### **3.7. Sprint 9: Maintenance**
#### Deliverables:
1. Gather user feedback for future updates.
2. Fix bugs and introduce new features based on user requirements.
3. Ensure system uptime with real-time monitoring.

#### Tools:
- Splunk for monitoring.
- GitHub for version control.

---

## **4. Risk Management**
| **Risk**               | **Mitigation Strategy**                                      |
|-------------------------|-------------------------------------------------------------|
| Security breaches       | Implement end-to-end encryption and regular security audits.|
| Scalability issues      | Use cloud-based microservices for horizontal scaling.       |
| Delayed deliverables    | Adopt Agile sprints for regular progress reviews.           |

---

## **5. Conclusion**
The Agile SDLC model ensures that CrowdDrop will evolve dynamically, meeting user needs efficiently. With iterative sprints and continuous feedback, the project will be delivered on time and within scope.

---

## **6. References**
- Agile Alliance. (2024). [Agile Development Principles](https://www.agilealliance.org).
- Google Maps API Documentation. (2024). [API Integration Guide](https://developers.google.com/maps/documentation).
