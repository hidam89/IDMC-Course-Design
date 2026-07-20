# UNIT 2

# Faculty Notes

# Session 1

# IICS Organization Architecture

---

## Course Outcome

CO2

---

## Session Learning Objectives

At the end of this session, students will be able to:

- Explain the Informatica Intelligent Cloud Services (IICS) organizational structure.
- Describe the organization hierarchy.
- Explain the purpose of organizations and sub-organizations.
- Understand the administrative responsibilities of an Organization Administrator.

---

# Introduction

Enterprise cloud platforms require structured administration to manage users, resources, licenses, and security.

In Informatica Intelligent Cloud Services (IICS), organizations provide the administrative boundary within which users, assets, runtime environments, and licenses are managed.

The organization hierarchy helps enterprises manage multiple departments, business units, subsidiaries, or geographical locations while maintaining centralized governance.

---

# What is an Organization?

An **Organization** is the highest administrative unit in Informatica Intelligent Cloud Services (IICS).

It provides:

- User management
- License management
- Asset management
- Runtime environment management
- Security administration

Every organization has at least one administrator responsible for managing these resources.

---

# Why Do Organizations Need Hierarchies?

Large enterprises often have multiple business units.

Example:

```
ABC Corporation

│

├── India

│      ├── Sales

│      ├── HR

│      └── Finance

│

├── USA

│      ├── Sales

│      └── Support

│

└── Europe

       ├── Marketing

       └── Operations
```

Managing all users in one organization becomes difficult.

IICS solves this problem using **Sub-Organizations**.

---

# Organization Hierarchy

```
Enterprise Organization

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

# Components of an Organization

An organization contains:

- Users
- User Groups
- Roles
- Assets
- Secure Agents
- Runtime Environments
- Licenses

---

# Organization Administrator Responsibilities

An administrator is responsible for:

- Creating users
- Managing authentication
- Assigning licenses
- Creating sub-organizations
- Managing Secure Agents
- Monitoring organization activity

---

# Enterprise Example

### XYZ Bank

The bank operates in:

- India
- Singapore
- UAE

Instead of managing every employee in one organization, the bank creates separate sub-organizations for each region.

Benefits:

- Better security
- Easier administration
- Independent license management
- Controlled access

---

# Advantages

- Centralized administration
- Better scalability
- Easier user management
- Improved governance
- Better security

---

# Limitations

- Requires proper planning
- Incorrect hierarchy increases administrative complexity
- License allocation must be monitored

---

# Classroom Discussion

Question:

Why is an organization hierarchy important for multinational companies?

Expected Discussion Points:

- Regional management
- Security
- Governance
- Scalability

---

# Faculty Tips

Explain using the university hierarchy.

Example:

```
University

↓

School of Computing

↓

Department

↓

Faculty

↓

Students
```

Students immediately understand organizational hierarchy when it is compared with their own institution.

---

# Common Misconceptions

❌ Organization and Sub-Organization are the same.

✔ Organization is the parent administrative entity.

✔ Sub-Organization is a child administrative entity.

---

# Summary

Today's session introduced:

- Organization
- Organization hierarchy
- Administrative responsibilities
- Enterprise examples
- Advantages of structured administration

---

# End of Session 1
# Session 2

# IICS Sub-Organizations

---

## Course Outcome

CO2

---

## Session Learning Objectives

At the end of this session, students will be able to:

- Explain the concept of Sub-Organizations.
- Differentiate Organization and Sub-Organization.
- Create Sub-Organizations.
- Explain Parent–Child relationships.
- Understand enterprise implementation of Sub-Organizations.

---

# Introduction

Large organizations often consist of multiple departments, business units, regional offices, and subsidiaries.

Managing all users, projects, assets, and licenses under a single organization becomes difficult.

To solve this problem, Informatica Intelligent Cloud Services (IICS) provides **Sub-Organizations**.

Sub-Organizations divide a large enterprise into smaller, independently manageable administrative units while maintaining centralized governance.

---

# What is a Sub-Organization?

A **Sub-Organization** is a logical administrative division created under a parent organization.

It allows enterprises to:

- Separate departments
- Separate geographical locations
- Allocate licenses independently
- Delegate administration
- Improve security

A Sub-Organization inherits governance from the parent organization but manages its own users and resources.

---

# Organization Hierarchy

```
Enterprise Organization

│

├── Finance

├── Human Resources

├── Sales

├── Marketing

└── IT
```

Each department can operate as an independent Sub-Organization.

---

# Parent–Child Relationship

```
Corporate Organization

↓

India

↓

Bangalore Office

↓

Sales Team
```

Each child organization belongs to one parent organization.

---

# Why Do We Need Sub-Organizations?

Without Sub-Organizations

- Difficult user management
- Mixed resources
- Complex administration
- Higher security risks

With Sub-Organizations

- Better access control
- Easier administration
- Department-wise management
- Independent resource allocation
- Improved governance

---

# Enterprise Example

ABC Technologies operates in:

- India
- USA
- Germany
- Singapore

Instead of maintaining one organization, the administrator creates:

```
ABC Technologies

├── India

├── USA

├── Germany

└── Singapore
```

Each regional administrator manages only their own users, projects, and assets.

---

# Creating a Sub-Organization

General steps:

1. Log in as Organization Administrator.
2. Open the **Administrator** console.
3. Navigate to **Sub-Organizations**.
4. Select **Create Sub-Organization**.
5. Enter:
   - Organization Name
   - Description
   - Parent Organization
6. Save the configuration.
7. Assign licenses.
8. Create users.

---

# Components of a Sub-Organization

Each Sub-Organization can contain:

- Users
- User Groups
- Roles
- Assets
- Secure Agents
- Runtime Environments
- Connections
- Licenses (allocated by the parent organization)

---

# Best Practices

- Create Sub-Organizations based on business units or geography.
- Use meaningful naming conventions.
- Allocate only the required licenses.
- Apply the Principle of Least Privilege.
- Regularly review user access.

---

# Advantages

- Easier administration
- Better scalability
- Improved security
- Department-wise control
- Better governance
- Simplified license management

---

# Limitations

- Requires proper planning.
- Poor hierarchy design increases administrative effort.
- License allocation must be monitored carefully.

---

# Classroom Activity

### Activity

Design an organization hierarchy for your university.

Example:

```
University

↓

School of Computing

↓

Department of CSE

↓

Faculty

↓

Students
```

Discuss how users and resources would be managed at each level.

---

# Discussion Question

A multinational company has offices in India, USA, and Europe.

Should it create one organization or separate Sub-Organizations?

Justify your answer considering:

- Security
- Administration
- License management
- Scalability

---

# Teaching Tips

Relate the concept to familiar organizational structures such as:

- Universities
- Banks
- Hospitals
- Government Departments

Students understand hierarchy more easily when linked to real institutions.

---

# Common Mistakes

❌ Creating too many unnecessary Sub-Organizations.

✔ Create them only when there is a clear administrative need.

---

❌ Allocating excessive licenses to every Sub-Organization.

✔ Allocate licenses based on actual usage.

---

❌ Giving all administrators full privileges.

✔ Follow Role-Based Access Control (RBAC).

---

# Summary

In this session, students learned:

- Definition of Sub-Organizations
- Parent–Child hierarchy
- Creation process
- Enterprise use cases
- Best practices
- Advantages and limitations

Sub-Organizations provide a scalable and secure way to manage users, resources, and licenses within large enterprises.

---

# End of Session 2