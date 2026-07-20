# UNIT 2

# Student Notes

## Informatica Intelligent Cloud Services (IICS)

---

# Course Outcome

**CO2**

Demonstrate the configuration of IICS Sub-organizations, User Management, and Secure Agent Installation, and analyze their impact on data integration processes.

---

# Learning Objectives

After completing this unit, students will be able to:

- Explain the IICS organization hierarchy.
- Configure Sub-Organizations.
- Create and manage users.
- Explain authentication methods.
- Create User Groups and Roles.
- Explain Runtime Environments.
- Describe Secure Agent Architecture.
- Explain Secure Agent Installation.

---

# Chapter 1

# IICS Organization Architecture

---

## Introduction

An organization is the highest administrative entity in Informatica Intelligent Cloud Services (IICS).

It provides a centralized environment for managing:

- Users
- Assets
- Runtime Environments
- Licenses
- Security
- Administration

Every Informatica Cloud customer owns at least one Organization.

---

# Organization Hierarchy

```

Organization

↓

Sub-Organization

↓

Users

↓

Groups

↓

Roles

↓

Assets

↓

Runtime Environment

```

---

# Why Organization Hierarchy?

Large organizations require separate administration for:

- Departments
- Branch Offices
- Countries
- Business Units

The hierarchy helps manage these efficiently.

---

# Benefits

- Centralized administration
- Better security
- Easier user management
- License management
- Enterprise scalability

---

# Components of an Organization

| Component | Purpose |
|-----------|---------|
| Users | Access the platform |
| Groups | Organize users |
| Roles | Assign permissions |
| Runtime Environment | Execute jobs |
| Secure Agent | Connect on-premises systems |
| Assets | Store mappings and tasks |

---

# Enterprise Example

ABC Corporation

```

Organization

├── India

├── USA

└── Europe

```

Each regional office can be managed independently using Sub-Organizations.

---

# Key Points

✔ Organization is the highest administrative entity.

✔ It contains users, assets, and runtime environments.

✔ Enterprise administration becomes easier using Organization Hierarchy.

---

# Examination Questions

### 2 Marks

Define Organization in IICS.

### 5 Marks

Explain Organization Hierarchy.

### 10 Marks

Discuss Organization Architecture with a neat diagram.

---

# Quick Revision

| Remember |
|-----------|
| Highest administrative unit |
| Contains users and assets |
| Supports enterprise administration |
| Parent of Sub-Organizations |

---

# Chapter Summary

In this chapter, we learned:

- Organization
- Organization hierarchy
- Components
- Enterprise example
- Benefits

---

# End of Chapter 1
# Chapter 2

# IICS Sub-Organizations

---

## Introduction

Large organizations often have multiple departments, branches, regional offices, or business units. Managing all users and resources under a single organization becomes difficult as the enterprise grows.

To overcome this challenge, Informatica Intelligent Cloud Services (IICS) provides **Sub-Organizations**, allowing administrators to divide an organization into smaller, independently managed units while maintaining centralized governance.

---

# Learning Objectives

After studying this chapter, students will be able to:

- Define a Sub-Organization.
- Explain the Organization Hierarchy.
- Describe the Parent–Child relationship.
- Explain Sub-Organization licenses.
- Identify enterprise use cases.
- Explain the benefits of Sub-Organizations.

---

# What is a Sub-Organization?

A **Sub-Organization** is a child administrative unit created under a parent organization.

It allows enterprises to:

- Separate departments
- Separate geographical locations
- Delegate administration
- Allocate licenses
- Improve governance
- Strengthen security

---

# Organization Structure

```
Enterprise Organization

│

├── India

│      ├── Bangalore

│      ├── Chennai

│      └── Delhi

│

├── USA

│      ├── New York

│      └── California

│

└── Europe

       ├── Germany

       └── France
```

Each branch can function as an independent Sub-Organization.

---

# Why are Sub-Organizations Required?

Without Sub-Organizations:

- Difficult administration
- Complex user management
- Poor scalability
- Resource conflicts
- Security risks

With Sub-Organizations:

- Better organization
- Easier administration
- Department-wise control
- Regional management
- Improved governance

---

# Characteristics

A Sub-Organization:

- Belongs to one parent organization.
- Has its own users.
- Has its own administrators.
- Uses allocated licenses.
- Can manage its own assets.

---

# Creating a Sub-Organization

General Steps:

1. Log in as Organization Administrator.
2. Open the **Administrator Console**.
3. Select **Sub-Organizations**.
4. Click **Create**.
5. Enter:
   - Name
   - Description
   - Parent Organization
6. Save the configuration.
7. Allocate licenses.
8. Add users.

---

# Parent–Child Relationship

```
Corporate Organization

↓

Regional Office

↓

Department

↓

Users
```

Each Sub-Organization inherits governance from the parent while managing its own resources.

---

# Sub-Organization Licenses

Licenses are assigned by the parent organization.

Examples include:

- Data Integration licenses
- API Integration licenses
- Data Quality licenses
- Administrator licenses

Administrators should allocate licenses based on actual business requirements.

---

# Working with Sub-Organizations

Common administrative tasks include:

- Create Sub-Organization
- Modify details
- Allocate licenses
- Create users
- Assign administrators
- Monitor usage
- Remove unused organizations

---

# Advantages

- Better scalability
- Improved administration
- Easier user management
- Enhanced security
- Flexible license allocation
- Department-level control

---

# Limitations

- Requires planning
- Poor hierarchy design increases complexity
- License allocation must be monitored

---

# Real-World Example

**XYZ University**

```
University

│

├── School of Computing

├── School of Management

├── School of Law

└── School of Architecture
```

Each school can be managed as a Sub-Organization with its own faculty, students, and administrators.

---

# Comparison

| Organization | Sub-Organization |
|--------------|------------------|
| Highest administrative unit | Child administrative unit |
| Created during organization setup | Created by Administrator |
| Controls overall governance | Manages departmental resources |
| Allocates licenses | Uses allocated licenses |

---

# Important Points

✔ A Sub-Organization always belongs to a parent organization.

✔ It simplifies administration in large enterprises.

✔ Licenses are allocated by the parent organization.

✔ Each Sub-Organization can have its own users and administrators.

---

# Examination Questions

### 2 Marks

Define Sub-Organization.

---

### 5 Marks

Explain the Parent–Child relationship in IICS.

---

### 10 Marks

Explain Sub-Organizations with a suitable architecture diagram.

---

# Quick Revision

| Remember |
|-----------|
| Child administrative unit |
| Improves scalability |
| Parent allocates licenses |
| Supports independent administration |
| Used by large enterprises |

---

# Chapter Summary

In this chapter, we studied:

- Sub-Organizations
- Parent–Child hierarchy
- License allocation
- Enterprise examples
- Advantages and limitations

Sub-Organizations help enterprises organize users, resources, and administration efficiently while maintaining centralized governance.

---

# End of Chapter 2