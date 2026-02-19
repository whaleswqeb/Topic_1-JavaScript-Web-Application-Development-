**Milestone 1: Project Proposal**

**Course:** JavaScript Web Application Development
**Application Name:** Community Resource & Event Management System
**Author:** ADEWALE OLAOMO  
**Date:** 18 Feb 2026

# **Project Proposal**

---

## **Introduction**

The Community Resource & Event Management System is a web application
that helps churches, non profits, student groups and local clubs keep
track of shared items plus plan gatherings. Small groups often use paper
lists or spreadsheets, a practice that produces double bookings, hidden
shortages and last minute chaos.

The system gathers every item in one place - rooms, chairs, sound gear,
books or digital files. Any approved person sees what is free, reserves
it but also links it to a meeting, class or party. A single calendar and
a single list of owners show who has what as well as when it will be
returned.

The server runs on Node.js with Express and stores data in MySQL. Two
separate browser clients will be written - one with Angular, one with
React. Both clients call the same REST endpoints or offer the same
screens and rules - the team can measure Angular against React without
changing the logic or the data.

## **Domain and Products Managed by the Application**

The primary domain of the application is the management of community
resource and event management. The primary product of the application is
the Resource, which may be anything the organization owns or shares.

Examples of the resource include:

o Meeting rooms

o Projectors and audio equipment

o Books and other study materials

o Sports and event equipment

o Digital equipment

Besides the resource, the application also manages the concept of
Events, which may be anything the community wants to do, like a meeting,
workshop, prayer, or even training.

The application is simple, practical, and realistic. It avoids the
complexity of enterprise software.

## **Functionality Requirements (User Stories)**

### **Resource Management**

### As a user, I want to:

### View a list of all resources (so I know what's available).

### View detailed information about a resource (so I understand its status and where it's located).

### Add new resources (so they can be tracked in the system).

### Update the resource details (so the information stays accurate).

### 5. Delete a resource that is not being used anymore.

### **Event Management**

### To help our users:

### To attach an event to the community, we want the capability to add events to a calendar of organized events

### To have a clear view of what events are coming up

### To create schedules for resources being used and identify potential conflicts

### To make changes to scheduled events as they change

### **System Requirements**

9.  I would like to check any incoming data for errors before I save it,
    so I do not store any bad data.

10. I intend to create a way to save data to a database that is a
    relational database system.

11. I will create a means of allowing both my angular application and my
    react application to access my backend system via a RESTful style
    API.

## **Frameworks, Technologies, and Tools**

### **Backend**

- Node.js

- Express.js

- RESTful API architecture

### **Frontend**

- Angular (one client application)

- React (second client application)

- HTML, CSS, and TypeScript / JavaScript

### **Database**

- MySQL

- Relational schema with primary and foreign keys

### **Development Tools**

- Visual Studio Code

- Git and GitHub for version control

- Postman for API testing

### **System Architecture**

![System Architecture](system_arch.png)

## **Initial UI Sitemap**

![Site Map](sitemap.png)

## **Initial UI Wireframes**

### **Dashboard Page**

![Dashboard](dashboard.png)

###

###

###

###

###

###

###

###

### **Add / Edit Resource Page**

![Edit Resource](editresource.png)

###

### **Event Management Page**

![Event Management](editevent.png)

## **Initial Database Design (ER Diagram)**

### **ER Diagram**

###

### ![ERD](erd.png)

###

###

###

### **Relationships**

- One Resource can be assigned to multiple Events.

- Each Event references one Resource.

## **Initial UML Class Diagram**

### **UML**

![UML](uml.png)

## **General Technical Approach**

The application will follow a layered architecture:

### **Presentation Layer**

- Angular and React front-end applications

- Forms and tables for user interaction

- REST API consumption

### **Business Layer**

- Express controllers and services

- Validation and business rules

- Resource availability checks

### **Persistence Layer**

- MySQL database

- DAO-style database access

- Relational schema with foreign keys

This architecture ensures separation of concerns, scalability, and
maintainability.

## **Risks**

### **Technical Risks**

### • Ensuring that the Angular and React versions of the application are functionally equal.

### • There are problems with connecting the Angular and React versions to the API.

### • Issues with configuring and connecting to MySQL.

### **Functional Risks**

- Scope creep due to adding extra features

- Time constraints across milestones

- UI inconsistencies between frameworks

All risks will be tracked and addressed throughout the project
lifecycle.
