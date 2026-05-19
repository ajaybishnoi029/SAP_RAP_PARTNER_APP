# SAP_RAP_PARTNER_APP
SAP ABAP RAP PARTNER APP

**Overview**
The SAP ABAP RAP Partner App has been developed using the **RESTful ABAP Programming Model (RAP)** in an **Unmanaged Implementation** approach.
This application is designed to manage partner-related business Entires while providing a modern, service-based architecture using SAP RAP.

---

## Key Features

* RAP Unmanaged Business Object Implementation
* OData Service Exposure
* CRUD Operations Support
* CDS-Based Data Modeling
* Behavior Definition and Implementation
* Service Definition & Service Binding
* Fiori/UI Integration Ready
* Scalable and Extensible Architecture

---

## Technology Stack

* SAP ABAP RAP Framework
* Core Data Services (CDS)
* Behavior Definition (BDEF)
* Behavior Implementation Class
* OData V2 / V4 Services
* SAP Trail Account

---

## Project Structure
├── CDS Views
├── Behavior Definition
├── Behavior Implementation
├── Service Definition
├── Service Binding
├── Metadata Extensions
└── Application Logic

---

## RAP Model Type

This application is implemented using:

* **RAP Unmanaged Scenario**

  * Business logic handled manually in ABAP classes
  * Full control over database operations
  * Suitable for complex legacy integrations and custom processing

---

## Main Components

### 1. CDS View

Defines the data model and entity structure.

### 2. Behavior Definition

Defines supported operations such as:

* Create
* Update
* Delete
* Read
* Actions

### 3. Behavior Implementation

Contains custom ABAP logic for transactional processing.

### 4. Service Definition

Exposes business entities for external consumption.

### 5. Service Binding

Publishes the OData service for UI or API integration.

---

## Prerequisites

* SAP S/4HANA System
* ABAP Development Tools (ADT/Eclipse)
* RAP Enabled System Version
* Authorization for RAP Development

---

## Deployment Steps

1. Create CDS Views
2. Define Behavior Definition
3. Implement Behavior Logic
4. Create Service Definition
5. Create Service Binding
6. Publish OData Service
7. Test using Preview or Fiori Application

---

## Author
Developed using SAP ABAP RAP Framework by Ajay Bishnoi.
