# UNIT 1 – FACULTY NOTES

# Informatica Intelligent Data Management Cloud (IDMC)

---

# Unit Overview

This unit introduces students to enterprise data management and the Informatica Intelligent Data Management Cloud (IDMC) platform. It establishes the foundation for the remaining units by explaining why organizations require integrated cloud-based data management solutions and how Informatica addresses enterprise data integration, application integration, data quality, governance, and master data management challenges.

This document is intended for instructors and serves as a classroom teaching guide rather than student notes.

---

# Unit Information

| Item | Details |
|------|---------|
| Course | Informatica Intelligent Data Management Cloud |
| Unit | Unit 1 |
| Total Sessions | 7 |
| Teaching Hours | 7 Hours |
| Course Outcome | CO1 |
| Bloom Level | L2 – Understand |
| Teaching Mode | Interactive Lecture + Discussion + Case Study |

---

# Teaching Philosophy

This unit should **not** begin with technical definitions.

Instead, students should first understand **why enterprise organizations need cloud data management**.

Always begin with a business problem before introducing Informatica products.

Students remember problems much better than product names.

---

# Unit Flow

Enterprise Data Management

↓

Challenges

↓

Evolution of Informatica

↓

IDMC Platform

↓

CDI

↓

CAI

↓

CDQ

↓

MDM

↓

CDGC

↓

CIH

↓

CDMP

↓

Enterprise Case Study

---

# Session 1

# Enterprise Data Management

Duration

60 Minutes

---

## Learning Objectives

Students should be able to

- Explain enterprise data management.
- Describe enterprise data challenges.
- Explain why organizations require cloud-based data management.

---

## Instructor Preparation

Before class prepare

- Whiteboard
- PPT
- Retail enterprise example
- Banking example

---

# Classroom Opening

Never begin with

"What is Informatica?"

Instead ask

> How many apps have you used today?

Write every answer on the board.

Typical answers

- WhatsApp

- Gmail

- YouTube

- Instagram

- Amazon

- Flipkart

- PhonePe

Now ask

> Where is this information stored?

Students answer

Database.

Now ask

> Only one database?

Students become curious.

This is the motivation.

---

# Blackboard Diagram

Draw

```
              Enterprise

      CRM

      ERP

      HRMS

      Finance

      Inventory

      Marketing

      Customer Support

             ↓

     Enterprise Data Management

             ↓

       Better Decisions
```

---

# Faculty Explanation

Explain

Every department owns data.

But management requires

one version

of truth.

Enterprise Data Management

makes this possible.

Do not introduce Informatica yet.

Students must first understand the business problem.

---

# Industrial Story

Suppose Amazon receives

1 million orders

today.

Customer information exists in

- Website

- Mobile App

- Warehouse

- Delivery

- Payment

- Customer Support

Ask

How does Amazon know

which customer ordered

which product

at what time

using which payment

and where it should be delivered?

Students realize

data integration is necessary.

---

# Think–Pair–Share

Scenario

A hospital maintains

Registration

Laboratory

Radiology

Billing

Pharmacy

Insurance

Students discuss

What problems occur

if these systems are isolated?

---

# Teaching Tip

Do not answer immediately.

Allow discussion.

Learning becomes active.

---

# Common Student Misconceptions

| Misconception | Clarification |
|---------------|---------------|
| Database and Enterprise Data Management are identical. | Enterprise Data Management includes integration, quality, governance, security, and lifecycle management. |
| Cloud Storage solves all enterprise problems. | Storage alone cannot provide integration or trusted enterprise data. |
| More data always means better decisions. | High-quality, integrated data leads to better decisions—not simply larger volumes of data. |

---

# Summary

Students should conclude that

Organizations require

- Integration

- Quality

- Governance

- Security

- Automation

This naturally leads to

Informatica.

---

# Transition

Ask

Who provides

Enterprise Data Management

as a cloud platform?

Students answer

Don't know.

Now begin

Evolution of Informatica.

---

# Session 2

# Evolution of Informatica

Duration

60 Minutes

---

## Learning Objectives

Students should understand

- History of Informatica
- ETL evolution
- Cloud transformation
- IICS
- IDMC

---

# Storytelling Approach

Instead of showing a timeline slide immediately, tell the story of how enterprise data management evolved.

Start by explaining that in the 1990s, organizations primarily managed data on-premises using ETL tools. As cloud computing, SaaS applications, and hybrid environments became common, traditional approaches became difficult to scale and maintain.

Guide students through this evolution:

PowerCenter

↓

Cloud Integration

↓

Informatica Intelligent Cloud Services (IICS)

↓

Informatica Intelligent Data Management Cloud (IDMC)

Explain that this transition reflects changing business requirements rather than simply new software versions.

---

# Classroom Discussion

Ask students:

- Why did organizations move from on-premises systems to cloud platforms?
- What limitations might traditional ETL tools face in hybrid cloud environments?

Encourage students to identify advantages such as scalability, accessibility, and integration with cloud services.

---

# Blackboard Plan

Draw a simple timeline:

1993

↓

Traditional ETL

↓

PowerCenter

↓

Cloud Adoption

↓

IICS

↓

IDMC

Explain each stage briefly before moving to the next.

---

# Teaching Tip

Present the evolution as a response to business needs, not as a product history. Students remember technology changes more effectively when they understand the underlying business drivers.

---

# Transition

Conclude by asking:

"If Informatica evolved into IDMC, what exactly is IDMC and what services does it provide?"

This question naturally introduces the next session.
---

# Session 3

# Introduction to Informatica Intelligent Data Management Cloud (IDMC)

Duration

60 Minutes

Course Outcome

CO1

Bloom Level

L2 – Understand

---

# Learning Objectives

At the end of this session students should be able to

- Explain Informatica Intelligent Data Management Cloud (IDMC).
- Describe the architecture of IDMC.
- Identify the major cloud services available in IDMC.
- Explain the relationship among CDI, CAI, CDQ, MDM, CDGC, CIH and CDMP.
- Recommend an appropriate Informatica service for a given enterprise requirement.

---

# Instructor Preparation

Before class prepare

- Unit 1 PPT (IDMC Overview)
- Whiteboard
- Marker
- Enterprise architecture diagram
- Retail case study

---

# Teaching Strategy

This session should **not** begin by listing IDMC services.

Students first need to understand why a single platform is necessary.

Teaching Sequence

Business Problem

↓

Enterprise Data Challenges

↓

Need for Unified Platform

↓

Introduction to IDMC

↓

IDMC Architecture

↓

Cloud Services

↓

Business Scenarios

---

# Classroom Opening

Ask students

Imagine you are the CIO of a multinational company.

Your organization uses

- Salesforce
- SAP
- Oracle Database
- Microsoft SQL Server
- AWS S3
- Snowflake
- ServiceNow

Question

> Can one software manage all these systems?

Allow students to discuss.

Most students will answer

"No."

Now ask

> Then how do large enterprises manage all these applications together?

This creates the need for IDMC.

---

# Faculty Explanation

Explain that modern organizations rarely depend on a single application.

Different business functions require different specialized systems.

Examples include

- ERP for finance
- CRM for customer management
- HRMS for employees
- Data warehouse for analytics
- SaaS applications for collaboration

Without a unified platform, organizations face:

- Data silos
- Duplicate records
- Inconsistent reports
- Delayed decision making
- Complex integrations
- Increased maintenance costs

Introduce IDMC as a cloud-native platform that provides multiple integrated services to solve these enterprise challenges.

---

# Definition

**Informatica Intelligent Data Management Cloud (IDMC)** is a cloud-native, AI-powered enterprise data management platform that enables organizations to integrate, manage, govern, protect, and analyze data across cloud, hybrid, and on-premises environments through a unified set of services.

Explain that IDMC is **a platform**, not a single application.

---

# Blackboard Diagram

Draw the following simplified architecture.

```
                    Users

                      │

              IDMC Platform

 ┌────────┬────────┬────────┬────────┐
 │  CDI   │  CAI   │  CDQ   │  MDM   │
 └────────┴────────┴────────┴────────┘

 ┌────────┬────────┬────────┬────────┐
 │ CDGC   │ CIH    │ CDMP   │ Others │
 └────────┴────────┴────────┴────────┘

                      │

     Cloud • Hybrid • On-Premises Systems
```

Explain that every service performs a different role while sharing a common platform.

---

# Explaining Each Service

Introduce each service at a high level only. Detailed explanations will follow in later sessions.

### Cloud Data Integration (CDI)

Purpose

Move and transform data between systems.

Example

Transfer sales data from Oracle Database to Snowflake.

---

### Cloud Application Integration (CAI)

Purpose

Connect enterprise applications and automate business processes.

Example

Automatically create an invoice in SAP after a Salesforce opportunity is closed.

---

### Cloud Data Quality (CDQ)

Purpose

Improve data accuracy, consistency, and completeness.

Example

Detect duplicate customer records before they enter the data warehouse.

---

### Master Data Management (MDM)

Purpose

Create a trusted single version of enterprise master data.

Example

Maintain one accurate customer profile across CRM, ERP, and billing systems.

---

### Cloud Data Governance & Catalog (CDGC)

Purpose

Discover, classify, govern, and document enterprise data assets.

Example

Identify sensitive customer information and apply governance policies.

---

### Cloud Integration Hub (CIH)

Purpose

Share trusted data among multiple consuming applications using a publish–subscribe model.

Example

Distribute validated product information to sales, marketing, and analytics systems.

---

### Cloud Data Marketplace (CDMP)

Purpose

Enable users to discover and request enterprise data assets through a governed marketplace.

Example

A business analyst searches for certified sales datasets without contacting IT.

---

# Service Selection Activity

Divide students into small groups.

Provide each group with one business scenario.

Examples:

### Scenario 1

A company wants to move customer data from Oracle to Snowflake every night.

Expected Answer

CDI

---

### Scenario 2

Customer information contains duplicate records.

Expected Answer

CDQ

---

### Scenario 3

The finance department and CRM maintain different customer names.

Expected Answer

MDM

---

### Scenario 4

A company wants to automate the approval of purchase orders across multiple applications.

Expected Answer

CAI

---

### Scenario 5

The compliance team needs to know where sensitive customer data is stored.

Expected Answer

CDGC

---

# Discussion Questions

1. Why does IDMC consist of multiple services rather than one application?
2. Can CDI replace CAI? Why or why not?
3. Why is data quality important before analytics?
4. How does governance improve enterprise decision making?
5. Which IDMC service would be most important for regulatory compliance?

---

# Common Student Misconceptions

| Misconception | Instructor Clarification |
|---------------|--------------------------|
| IDMC is a single software product. | IDMC is a platform offering multiple integrated cloud services. |
| CDI and CAI perform the same function. | CDI focuses on data movement and transformation, while CAI integrates applications and automates workflows. |
| Data quality is required only after integration. | Data quality should be maintained throughout the data lifecycle. |
| Governance is only for security teams. | Governance benefits business users, analysts, auditors, and IT teams alike. |

---

# Teaching Tips

- Introduce services through business problems rather than definitions.
- Avoid explaining all service features in detail during this session.
- Continuously relate each service to an enterprise scenario.
- Encourage students to identify the appropriate service before revealing the answer.

---

# Session Summary

Students should understand that

- IDMC is an enterprise cloud data management platform.
- Different enterprise problems require different cloud services.
- All IDMC services work together to support trusted, integrated, and governed enterprise data.

Students are **not expected to master each service yet**. The objective is to build a conceptual map that will guide the remaining sessions.

---

# Exit Ticket

Ask students to answer:

1. Why is IDMC considered a platform instead of a single application?
2. Which IDMC service would you recommend for integrating data from multiple databases? Explain your choice.

---

# Transition to Session 4

Conclude with the question:

> "Now that we know IDMC provides multiple services, how does Cloud Data Integration (CDI) actually move and transform enterprise data between different systems?"

Inform students that the next session will explore **Cloud Data Integration (CDI)** in detail, including architecture, workflows, real-world use cases, and enterprise case studies.
---

# Session 4

# Cloud Data Integration (CDI)

Duration

60 Minutes

Course Outcome

CO1

Bloom's Level

L2 – Understand

Teaching Method

Interactive Lecture + Case Study + Group Discussion

---

# Learning Objectives

At the end of this session students will be able to:

- Explain the purpose of Cloud Data Integration (CDI).
- Differentiate ETL and ELT approaches.
- Describe the architecture of CDI.
- Identify common data integration tasks.
- Recommend CDI for appropriate enterprise scenarios.

---

# Instructor Preparation

Before class:

- Review the CDI PPT.
- Keep the Retail Data Integration case study ready.
- Prepare an ETL vs ELT comparison diagram on the board.
- Prepare examples involving Oracle, Salesforce, and Snowflake.

---

# Teaching Strategy

Do not start with the definition of CDI.

Instead, begin with a business problem.

Business Problem

↓

Need for Data Integration

↓

Traditional ETL

↓

Limitations

↓

Cloud Data Integration

↓

CDI Architecture

↓

Enterprise Example

---

# Classroom Opening

Ask students:

"A company stores customer information in Salesforce, sales transactions in Oracle Database, and analytics in Snowflake. The CEO wants a daily sales dashboard. How can these systems work together?"

Allow students to discuss for three minutes.

Write their ideas on the board.

Explain that this challenge is known as **enterprise data integration**.

---

# Faculty Explanation

Every organization stores data in multiple systems.

Examples:

- ERP
- CRM
- HRMS
- Excel
- Cloud Applications
- Data Warehouse

If these systems remain isolated:

- Reports become inconsistent.
- Duplicate information appears.
- Analytics become unreliable.
- Decision making is delayed.

Cloud Data Integration (CDI) enables organizations to extract, transform, and load data across cloud and on-premises environments using a unified cloud platform.

---

# Definition

Cloud Data Integration (CDI) is an Informatica Intelligent Data Management Cloud (IDMC) service used to design, execute, and monitor data integration workflows between heterogeneous data sources and destinations.

Emphasize that CDI focuses on **data movement and transformation**, not application workflow automation.

---

# Blackboard Diagram

Draw the following architecture.

```
        Oracle DB

              │

      Salesforce CRM

              │

        SQL Server

              │

        Flat Files

              │

        Cloud Data Integration

              │

      Transform & Validate

              │

        Snowflake

              │

       Power BI / Tableau
```

Explain each component and the direction of data flow.

---

# ETL vs ELT

Present the following comparison.

| ETL | ELT |
|-----|-----|
| Transform before loading | Transform after loading |
| Suitable for traditional data warehouses | Suitable for cloud-native platforms |
| Processing occurs on ETL server | Processing occurs inside target platform |
| Limited scalability | Highly scalable |

Discussion Question:

"When would an organization prefer ELT over ETL?"

Guide students toward cloud data warehouses such as Snowflake or BigQuery.

---

# CDI Architecture

Explain the major components:

- Source Systems
- Secure Agent
- Mapping Designer
- Transformation Logic
- Target Systems
- Monitoring Console

Describe the role of each component using a simple workflow.

---

# Enterprise Example

### Retail Data Integration

Scenario:

A retail organization receives sales data from:

- Website
- Mobile Application
- Physical Stores
- ERP
- Warehouse Management System

Business Requirement:

Generate a unified sales report every morning.

Explain how CDI extracts data from all source systems, applies transformations, validates the data, and loads it into a cloud data warehouse for reporting.

Connect this explanation to the Retail Data Integration case study from your teaching materials.

---

# Classroom Activity

Activity Title:

**Design a Data Integration Workflow**

Students work in groups of four.

Scenario:

A hospital maintains:

- Patient Registration
- Laboratory
- Pharmacy
- Billing
- Insurance

Task:

Identify:

1. Source systems
2. Target system
3. Data transformations required
4. Possible data quality issues

Groups present their proposed workflow.

---

# Discussion Questions

1. Why is data integration necessary in modern enterprises?
2. Can a data warehouse function effectively without integration?
3. How does cloud computing improve enterprise data integration?
4. What challenges arise when integrating heterogeneous systems?

---

# Common Student Misconceptions

| Misconception | Clarification |
|---------------|---------------|
| CDI stores enterprise data permanently. | CDI moves and transforms data; storage occurs in source or target systems. |
| CDI replaces databases. | CDI integrates databases; it does not replace them. |
| Data integration only copies records. | Integration also transforms, validates, enriches, and monitors data. |

---

# Teaching Tips

- Begin with a real business problem.
- Draw architecture before introducing Informatica terminology.
- Avoid deep discussion of mapping transformations during the introductory session.
- Encourage students to justify why integration is needed before explaining how CDI performs it.

---

# Summary

Students should understand:

- Enterprise systems generate distributed data.
- Integration is essential for reliable analytics.
- CDI provides cloud-native data integration capabilities.
- ETL and ELT are complementary approaches depending on architecture and business requirements.

---

# Exit Ticket

Ask students:

1. Explain CDI in your own words.
2. List two differences between ETL and ELT.
3. Identify one business scenario where CDI would be an appropriate solution.

---

# Transition to Session 5

Conclude by asking:

"Data can now move between systems, but what if different enterprise applications must communicate in real time?"

Explain that the next session introduces **Cloud Application Integration (CAI)** and explores how applications—not just data—can be integrated and automated.
---

# Session 5

# Cloud Application Integration (CAI)

Duration

60 Minutes

Course Outcome

CO1

Bloom's Level

L2 – Understand

Teaching Method

Interactive Lecture + Role Play + Case Study

---

# Learning Objectives

At the end of this session, students will be able to:

- Explain the purpose of Cloud Application Integration (CAI).
- Differentiate Cloud Data Integration (CDI) from Cloud Application Integration (CAI).
- Describe event-driven application integration.
- Identify common enterprise application integration scenarios.
- Recommend CAI for workflow automation.

---

# Instructor Preparation

Before class prepare:

- CAI PPT
- CDI vs CAI comparison sheet
- Customer 360 case study
- Whiteboard and marker

---

# Teaching Strategy

Begin with a business process instead of a definition.

Business Process

↓

Disconnected Applications

↓

Manual Work

↓

Need for Automation

↓

Cloud Application Integration

↓

Enterprise Workflow

---

# Classroom Opening

Ask students:

"A customer places an online order. Which applications are involved before the product reaches the customer?"

Guide students to identify:

- E-commerce Portal
- Payment Gateway
- Inventory System
- ERP
- Warehouse
- Courier Service
- CRM
- Email Notification Service

Ask:

"What happens if employees manually update each application?"

Students quickly realize the process is slow and error-prone.

Introduce the need for application integration.

---

# Faculty Explanation

Cloud Application Integration (CAI) focuses on integrating applications and automating business processes.

Unlike CDI, which moves and transforms data, CAI coordinates interactions between applications in real time.

Examples include:

- Creating invoices automatically after order confirmation.
- Sending email notifications after successful payment.
- Updating inventory immediately after a sale.
- Creating support tickets automatically from customer requests.

---

# Definition

Cloud Application Integration (CAI) is an Informatica IDMC service that enables real-time integration, workflow automation, API orchestration, and event-driven communication among enterprise applications.

---

# Blackboard Diagram

Draw the following workflow:

```
Customer

    │

Website

    │

Payment Gateway

    │

ERP

    │

Warehouse

    │

Courier

    │

Customer Notification
```

Explain that CAI coordinates the workflow across applications.

---

# CDI vs CAI

| Cloud Data Integration (CDI) | Cloud Application Integration (CAI) |
|------------------------------|-------------------------------------|
| Integrates data | Integrates applications |
| Batch or scheduled processing | Event-driven and real-time |
| ETL / ELT operations | Workflow orchestration |
| Data movement | Business process automation |
| Analytics focused | Operational process focused |

---

# Enterprise Example

### Customer Order Processing

A customer places an online order.

Without CAI:

- Sales team receives email.
- Inventory is updated manually.
- Finance creates invoice manually.
- Warehouse receives delayed instructions.

With CAI:

- Order confirmation triggers an automated workflow.
- Payment is verified.
- ERP is updated.
- Inventory is reduced.
- Warehouse receives a pick list.
- Customer receives confirmation.
- Delivery partner is notified.

Students should recognize that CAI automates the business process rather than moving data for reporting.

---

# Classroom Activity

### Activity: Workflow Mapping

Divide students into groups.

Scenario:

An airline booking system.

Applications involved:

- Booking Portal
- Payment Gateway
- Seat Allocation
- Customer Notification
- Loyalty Program

Task:

Draw the workflow and identify where CAI automates communication between applications.

Each group presents its workflow.

---

# Discussion Questions

1. Why is application integration important in digital transformation?
2. Can CAI replace CDI? Explain.
3. What advantages does event-driven architecture provide?
4. Which industries benefit most from workflow automation?

---

# Common Student Misconceptions

| Misconception | Clarification |
|---------------|---------------|
| CAI replaces CDI. | CAI and CDI solve different business problems and often work together. |
| CAI stores enterprise data. | CAI coordinates applications; it is not a data repository. |
| Workflow automation eliminates human involvement completely. | Many workflows include approval steps and human decision points. |

---

# Teaching Tips

- Emphasize business processes rather than software features.
- Use real-life examples students already understand.
- Encourage students to identify events that trigger workflows.
- Compare manual and automated processes side by side.

---

# Expected Student Questions

**Q:** Why do organizations need both CDI and CAI?

**Suggested Answer:** CDI integrates and transforms data for analytics and reporting, while CAI automates communication and workflows among applications. Most enterprises require both.

---

**Q:** Can CAI integrate on-premises and cloud applications?

**Suggested Answer:** Yes. CAI supports hybrid integration using connectors and APIs.

---

# Interview Corner

### Question 1

Differentiate CDI and CAI with an enterprise example.

---

### Question 2

What is workflow orchestration?

---

### Question 3

Explain event-driven integration.

---

### Question 4

What is API orchestration?

---

# Blackboard Sketch

```
Customer

↓

Website

↓

CAI Workflow

↓

ERP

↓

Warehouse

↓

Courier

↓

Customer
```

---

# Further Reading

- Unit 1 CAI PPT
- CDI vs CAI Comparison Notes
- Customer 360 Case Study
- Informatica Application Integration Documentation

---

# Summary

Students should understand that:

- CAI integrates enterprise applications.
- CAI automates workflows.
- CAI is event-driven.
- CDI and CAI complement each other.
- Workflow automation improves operational efficiency.

---

# Exit Ticket

Ask students:

1. Explain CAI in one sentence.
2. List three applications that can be integrated using CAI.
3. Why can't CDI alone automate enterprise workflows?

---

# Transition to Session 6

Conclude by asking:

"Applications can now communicate automatically, but what happens if the data itself contains duplicate, incomplete, or incorrect information?"

Explain that the next session introduces **Cloud Data Quality (CDQ)** and explores how organizations ensure trusted, accurate, and consistent data before using it for analytics or operational decisions.
---

# Session 6

# Cloud Data Quality (CDQ)

Duration

60 Minutes

Course Outcome

CO1

Bloom's Level

L2 – Understand

Teaching Method

Interactive Lecture + Case Study + Collaborative Learning

---

# Learning Objectives

At the end of this session students will be able to:

- Explain the importance of data quality in enterprise systems.
- Describe the dimensions of data quality.
- Explain data profiling, cleansing, standardization and matching.
- Identify common data quality issues.
- Recommend Cloud Data Quality (CDQ) for enterprise scenarios.

---

# Instructor Preparation

Before class prepare:

- CDQ PPT
- Banking Data Quality Case Study
- Sample customer dataset (with duplicates and errors)
- Whiteboard and marker

---

# Teaching Strategy

Start with a simple example instead of defining CDQ.

Incorrect Data

↓

Business Problems

↓

Need for Data Quality

↓

Cloud Data Quality

↓

Data Quality Dimensions

↓

Enterprise Case Study

---

# Classroom Opening

Ask students:

"A customer has three records in a bank."

Example:

Record 1:
Ramesh Kumar

Record 2:
R. Kumar

Record 3:
Ramesh K.

Ask:

> How many customers does the bank have?

Most students answer:

"One."

Then ask:

> What if the software counts three customers?

Students immediately recognize the business problem.

Introduce **Cloud Data Quality**.

---

# Faculty Explanation

Organizations cannot make good decisions using poor-quality data.

Poor data quality results in:

- Duplicate records
- Missing information
- Incorrect reports
- Failed marketing campaigns
- Regulatory compliance issues
- Customer dissatisfaction

Cloud Data Quality (CDQ) provides tools for profiling, cleansing, standardizing, validating and monitoring enterprise data.

---

# Definition

Cloud Data Quality (CDQ) is an Informatica IDMC service that improves the accuracy, completeness, consistency and reliability of enterprise data through profiling, cleansing, validation and standardization.

---

# Blackboard Diagram

Draw:

```
Customer Data

↓

Profile

↓

Validate

↓

Cleanse

↓

Standardize

↓

Match

↓

Trusted Data
```

Explain each step.

---

# Data Quality Dimensions

Discuss the six commonly used dimensions.

### Accuracy

Is the data correct?

Example:

Correct Date of Birth

---

### Completeness

Is any required information missing?

Example:

Phone Number missing.

---

### Consistency

Is the same information represented consistently?

Example:

Customer name differs across systems.

---

### Validity

Does the data follow business rules?

Example:

Email format is valid.

---

### Uniqueness

Are duplicate records removed?

Example:

Customer appears only once.

---

### Timeliness

Is the information up-to-date?

Example:

Current address is available.

---

# Enterprise Case Study

### Banking Customer Database

A bank has multiple systems:

- Savings Accounts
- Credit Cards
- Loans
- Internet Banking

Each system stores customer information separately.

Problems:

- Duplicate customer records.
- Different spellings of names.
- Missing phone numbers.
- Invalid email addresses.
- Incorrect addresses.

Ask students:

"What problems might arise?"

Guide the discussion toward:

- Incorrect KYC
- Compliance risks
- Customer complaints
- Incorrect reporting
- Fraud detection issues

Explain how CDQ helps profile, cleanse, standardize, validate and monitor the data.

---

# Classroom Activity

### Data Cleansing Exercise

Provide a small dataset.

Example:

| Customer | Phone | Email |
|----------|-------|--------|
| Ramesh Kumar | 987654321 | ramesh@gmail |
| R Kumar | 9876543210 | rk@gmail.com |
| Ramesh K | NULL | ramesh@gmail.com |

Task:

Students identify:

- Duplicate records
- Missing values
- Invalid formats
- Standardization requirements

Groups explain how CDQ would improve the dataset.

---

# Discussion Questions

1. Why is high-quality data important for analytics?
2. Which data quality dimension is most critical for banking systems?
3. Can data integration alone guarantee trusted data?
4. What business risks arise from duplicate customer records?

---

# Common Student Misconceptions

| Misconception | Clarification |
|---------------|---------------|
| Data quality only removes duplicates. | CDQ includes profiling, validation, cleansing, standardization, matching and monitoring. |
| Data quality is performed only once. | Enterprise data quality is a continuous process. |
| Integration automatically improves quality. | Integrated data can still contain errors and inconsistencies. |

---

# Teaching Tips

- Use real examples from banking, healthcare and e-commerce.
- Encourage students to identify data quality problems before introducing CDQ features.
- Reinforce that quality is everyone's responsibility, not only the IT team's.

---

# Expected Student Questions

### Q1

Why is duplicate data harmful?

Suggested Answer:

Duplicate records increase storage costs, reduce reporting accuracy, create customer confusion and may violate compliance requirements.

---

### Q2

Can CDQ correct every data quality problem automatically?

Suggested Answer:

No. CDQ automates many tasks, but business rules and human validation are often required.

---

### Q3

Is data profiling the same as data cleansing?

Suggested Answer:

No. Profiling identifies problems, while cleansing corrects them.

---

# Interview Corner

### Question 1

Explain the six dimensions of data quality.

---

### Question 2

Differentiate data profiling and data cleansing.

---

### Question 3

What is data standardization?

---

### Question 4

How does CDQ support enterprise decision making?

---

# Blackboard Sketch

```
Raw Data

↓

Profile

↓

Cleanse

↓

Validate

↓

Standardize

↓

Match

↓

Trusted Enterprise Data
```

---

# Further Reading

- Unit 1 CDQ PPT
- Banking Data Quality Case Study
- Informatica Cloud Data Quality Documentation

---

# Summary

Students should understand:

- Enterprise decisions depend on trusted data.
- CDQ improves data quality through multiple processes.
- High-quality data is essential before analytics, governance and master data management.
- Data quality is a continuous enterprise activity.

---

# Exit Ticket

Ask students:

1. Explain one data quality dimension with an example.
2. Differentiate profiling and cleansing.
3. Why is data quality important before data integration?

---

# Transition to Session 7

Conclude by asking:

"Suppose customer data has been integrated and cleansed. How can an organization maintain one trusted customer record across all departments?"

Explain that the next session introduces **Master Data Management (MDM)** along with **Cloud Data Governance & Catalog (CDGC)**, **Cloud Integration Hub (CIH)** and **Cloud Data Marketplace (CDMP)** to complete the enterprise data management lifecycle.
---

# Session 7A

# Master Data Management (MDM)

Duration

60 Minutes

Course Outcome

CO1

Bloom's Level

L2 – Understand

Teaching Method

Interactive Lecture + Customer 360 Case Study + Group Discussion

---

# Learning Objectives

At the end of this session students should be able to

- Explain Master Data Management (MDM).
- Differentiate transactional data and master data.
- Explain the concept of a "Single Source of Truth".
- Identify enterprise applications of MDM.
- Explain Customer 360.

---

# Instructor Preparation

Before class prepare

- MDM PPT
- Customer 360 Diagram
- Whiteboard
- Retail Customer Case Study

---

# Teaching Strategy

Customer Information

↓

Duplicate Records

↓

Business Problems

↓

Master Data

↓

Single Source of Truth

↓

Customer 360

↓

Enterprise Benefits

---

# Classroom Opening

Ask students

Suppose one customer purchases

- Laptop

- Mobile Phone

- Television

during three different years.

The company stores customer information in

CRM

ERP

Warranty System

Customer Support

Finance

Marketing

Ask

How many customer records should exist?

Students answer

One.

Now ask

What if every system stores

different addresses

different phone numbers

different email IDs?

Students immediately understand

the problem.

---

# Faculty Explanation

Explain

Master Data

is the

core business information

shared across the organization.

Examples

Customer

Employee

Supplier

Product

Location

Vendor

Master Data rarely changes.

Transactional Data changes every second.

---

# Blackboard Diagram

Draw

```
CRM

↓

ERP

↓

Finance

↓

Support

↓

Marketing

↓

Master Data Hub

↓

Single Customer Record
```

Explain

Every application

reads

the same customer information.

---

# Definition

Master Data Management (MDM)

is the process of creating

maintaining

and governing

a single trusted version

of enterprise master data

shared across all business systems.

---

# Customer 360

Introduce

Customer 360

Explain

Instead of

five customer profiles

organization maintains

one trusted profile.

Show

Customer

↓

Orders

↓

Payments

↓

Support

↓

Marketing

↓

Loyalty

↓

Analytics

Everything connected.

---

# Enterprise Example

Retail Company

Departments

Sales

Marketing

Finance

Customer Support

Inventory

All require

same customer information.

Without MDM

Different reports.

Duplicate customers.

Incorrect marketing.

Poor customer experience.

With MDM

One customer.

One profile.

One version of truth.

---

# Classroom Activity

Activity

Customer Matching

Provide

five customer records

with

slightly different names.

Students identify

duplicates

and create

one master record.

Discuss

How would MDM solve this?

---

# Discussion Questions

1 Why is master data important?

2 Difference between Master Data and Transaction Data?

3 Why is Customer 360 valuable?

4 Which industries benefit most from MDM?

---

# Common Student Misconceptions

| Misconception | Clarification |
|---------------|---------------|
| MDM stores every enterprise record. | MDM stores trusted master entities, not all transactions. |
| MDM replaces databases. | MDM coordinates master data across systems; databases still store operational data. |
| Customer 360 is only a CRM feature. | Customer 360 integrates information from multiple enterprise systems. |

---

# Teaching Tips

Use

Bank

Hospital

Retail

examples.

Students understand

Customer 360

very quickly.

---

# Expected Student Questions

Q

Can one organization have multiple master datasets?

Answer

Yes.

Customer

Supplier

Employee

Product

Location

Vendor

all may have separate master domains.

---

Q

Can MDM improve AI models?

Answer

Yes.

High-quality master data improves analytics, machine learning and decision making.

---

# Interview Corner

Explain

Customer 360

with example.

---

Difference between

Master Data

and

Transactional Data.

---

Why do enterprises require

Single Source of Truth?

---

# Blackboard Sketch

```
Customer

↓

CRM

↓

ERP

↓

Marketing

↓

Support

↓

Master Data Hub

↓

Customer 360
```

---

# Summary

Students should understand

Master Data

↓

Trusted Information

↓

Customer 360

↓

Enterprise Decision Making

---

# Exit Ticket

Explain

Single Source of Truth

using one enterprise example.

---

# Transition

Now ask

If organizations maintain

trusted data

who ensures

this data

is properly governed

documented

secured

and shared?

Answer

Cloud Data Governance.
---

# Session 7B

# Cloud Data Governance & Catalog (CDGC), Cloud Integration Hub (CIH), Cloud Data Marketplace (CDMP), and Unit Integration

Duration

60 Minutes

Course Outcome

CO1

Bloom's Level

L2 – Understand

Teaching Method

Interactive Lecture + Enterprise Architecture Discussion + Case Study + Student Presentation

---

# Learning Objectives

At the end of this session students will be able to:

- Explain the purpose of Cloud Data Governance & Catalog (CDGC).
- Describe the role of Cloud Integration Hub (CIH).
- Explain Cloud Data Marketplace (CDMP).
- Differentiate governance, integration, and data sharing.
- Explain how all IDMC services work together to solve enterprise data management challenges.

---

# Instructor Preparation

Before class prepare:

- CDGC PPT
- CIH PPT
- CDMP PPT
- Enterprise Architecture Diagram
- Whiteboard
- Marker

---

# Teaching Strategy

Review Previous Services

↓

Need for Governance

↓

Cloud Data Governance

↓

Need for Controlled Data Sharing

↓

Cloud Integration Hub

↓

Need for Business Self-Service

↓

Cloud Data Marketplace

↓

Integrated Enterprise Architecture

↓

Case Study

---

# Classroom Opening

Begin with the following question.

Suppose an organization has

✔ Integrated Data

✔ High Quality Data

✔ Master Data

Now ask

Who decides

- Who can access the data?
- Which version is trusted?
- Which department owns the data?
- Whether sensitive information should be visible?

Allow discussion.

Students realize

Integration alone

does not solve governance.

---

# Faculty Explanation

Explain

Enterprise Data Management has three major objectives.

1.

Create trusted data.

2.

Govern trusted data.

3.

Deliver trusted data to the right users.

This is where

CDGC

CIH

CDMP

become important.

---

# Cloud Data Governance & Catalog (CDGC)

Definition

Cloud Data Governance & Catalog (CDGC) enables organizations to discover, classify, govern, document, and monitor enterprise data assets while maintaining compliance and trust.

Explain

Governance answers questions such as:

- Who owns the data?
- Who can modify it?
- Is the data certified?
- Is the data sensitive?
- Where did the data originate?
- How has the data changed?

---

# Enterprise Example

Hospital

Patient Records

↓

Laboratory

↓

Radiology

↓

Insurance

↓

Research

Question

Should every employee access patient information?

Students answer

No.

Explain

Governance controls

access

ownership

lineage

compliance

security

---

# Blackboard Diagram

Draw

```
Enterprise Data

↓

Discover

↓

Classify

↓

Govern

↓

Monitor

↓

Trusted Enterprise Data
```

---

# Cloud Integration Hub (CIH)

Faculty Explanation

Explain

Traditional integration creates

multiple

point-to-point connections.

Example

```
System A → B

System A → C

System A → D

System B → D
```

Very difficult to maintain.

Now explain

Cloud Integration Hub

uses

Publish

↓

Subscribe

architecture.

Draw

```
          CIH

      /   |   \

Sales Marketing Finance

     \    |    /

   Analytics CRM ERP
```

Explain

Data is published once

consumed many times.

---

# Enterprise Example

Product Information

Published once.

Consumed by

- Sales

- Marketing

- ERP

- Mobile App

- Website

- Analytics

No duplicate integrations.

---

# Cloud Data Marketplace (CDMP)

Faculty Explanation

Students understand

Amazon Marketplace.

Now ask

Can data also have a marketplace?

Students become curious.

Explain

Business users

search

discover

request

approved datasets

without contacting IT.

Benefits

- Faster analytics
- Self-service access
- Certified datasets
- Governance compliance

---

# Enterprise Example

Marketing department

needs customer sales data.

Instead of emailing IT

they search

Enterprise Data Marketplace.

Request access.

Manager approves.

Data becomes available.

---

# Complete IDMC Ecosystem

Now integrate everything.

Draw slowly.

```
Enterprise Systems

ERP

CRM

HRMS

Finance

Warehouse

↓

Cloud Data Integration

↓

Cloud Data Quality

↓

Master Data Management

↓

Cloud Data Governance

↓

Cloud Integration Hub

↓

Cloud Data Marketplace

↓

Analytics

AI

Business Users
```

Explain

Every service

has one responsibility.

Together

they create

Enterprise Data Management.

---

# Integrated Case Study

Scenario

A multinational retail company wants to

- Integrate sales data
- Improve customer data quality
- Maintain Customer 360
- Govern sensitive customer information
- Share trusted datasets with analysts

Ask students

Which Informatica services should be used?

Expected Answer

CDI

↓

CDQ

↓

MDM

↓

CDGC

↓

CIH

↓

CDMP

---

# Classroom Activity

Activity

Enterprise Solution Design

Groups

receive one business scenario.

Example

Hospital

Bank

University

Manufacturing

Students prepare

Enterprise Architecture

using

appropriate IDMC services.

Presentation

5 minutes.

---

# Discussion Questions

1. Why is governance necessary after data integration?

2. Difference between MDM and CDGC?

3. Why is CIH more scalable than point-to-point integration?

4. Why should business users access certified datasets?

5. Which IDMC service provides self-service data discovery?

---

# Common Student Misconceptions

| Misconception | Clarification |
|---------------|---------------|
| Governance is only security. | Governance includes ownership, quality, lineage, compliance, stewardship and policies. |
| CIH replaces CDI. | CIH distributes trusted data; CDI integrates and transforms data. |
| CDMP stores enterprise data. | CDMP provides governed access to certified datasets. |

---

# Teaching Tips

Teach

business process

before

software.

Students understand

business value

much faster.

---

# Expected Student Questions

Q

Can one organization implement

only CDI?

Answer

Yes.

But mature organizations usually implement

multiple services

depending on business maturity.

---

Q

Why is governance important?

Answer

Without governance

trusted data

becomes untrusted again.

---

Q

Can AI work without governance?

Answer

Poor governance

produces

poor AI.

Trusted AI

requires

trusted data.

---

# Interview Corner

Explain

Complete IDMC Architecture.

---

Difference between

CDI

CAI

CDQ

MDM

CDGC

CIH

CDMP.

---

Why is

Customer 360

important?

---

Explain

Publish–Subscribe

Architecture.

---

# Blackboard Sketch

```
Business Problem

↓

CDI

↓

CDQ

↓

MDM

↓

CDGC

↓

CIH

↓

CDMP

↓

Trusted Enterprise Data

↓

Business Intelligence

↓

AI

↓

Decision Making
```

---

# Unit Summary

Students should now understand

Enterprise Data Problems

↓

Cloud Data Integration

↓

Application Integration

↓

Data Quality

↓

Master Data

↓

Governance

↓

Enterprise Data Sharing

↓

Business Intelligence

↓

Enterprise Decisions

The complete IDMC platform provides an integrated approach to managing enterprise data across cloud, hybrid, and on-premises environments.

---

# Unit Review Activity

Conduct a "Service Selection Challenge."

Prepare 10 business scenarios.

Students identify

which IDMC service

should solve

each problem.

Examples

Duplicate Customer Data

→ CDQ

Real-Time Order Processing

→ CAI

Customer 360

→ MDM

Data Governance

→ CDGC

Enterprise Data Distribution

→ CIH

Certified Dataset Discovery

→ CDMP

---

# Exit Ticket

Each student answers

1. Which IDMC service do you think is the most important? Why?

2. Draw the complete IDMC architecture from memory.

3. Explain how CDI, CDQ and MDM work together.

---

# End of Unit Reflection

Ask students to write one paragraph on:

> "How does Informatica Intelligent Data Management Cloud help organizations transform raw enterprise data into trusted business intelligence?"

---

# Transition to Unit 2

Conclude with:

> "In Unit 1, we explored what IDMC is and the services it provides. In Unit 2, we will move from concepts to administration by learning how to configure organizations, manage users, install Secure Agents, and prepare the Informatica Cloud environment for enterprise deployment."