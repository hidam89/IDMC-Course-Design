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
# Chapter 3

# User Management

---

## Introduction

User Management is a fundamental administrative function in Informatica Intelligent Cloud Services (IICS). It enables administrators to create, modify, monitor, and control user access to the platform.

Proper user management ensures that only authorized users can access enterprise resources while maintaining security, accountability, and compliance.

---

# Learning Objectives

After completing this chapter, students will be able to:

- Explain User Management in IICS.
- Describe authentication methods.
- Create and manage users.
- Explain user actions.
- Edit user information.
- Apply security best practices.

---

# What is User Management?

User Management is the process of administering users within an IICS organization.

It includes:

- User creation
- User authentication
- Role assignment
- Group assignment
- User monitoring
- User modification
- User deactivation

---

# User Lifecycle

```
Request User

↓

Create User

↓

Assign Role

↓

Assign Group

↓

Activate Account

↓

User Login

↓

Perform Tasks

↓

Deactivate/Delete User
```

---

# User Authentication

Authentication verifies the identity of a user before access is granted.

IICS supports multiple authentication methods.

The two commonly used methods are:

- Native Authentication
- Salesforce Authentication

---

# Native Authentication

In Native Authentication, the username and password are managed directly by Informatica Cloud.

### Features

- Credentials stored in IICS
- Simple configuration
- Suitable for small organizations
- No external identity provider required

### Advantages

- Easy to configure
- Independent authentication
- Quick user creation

### Limitations

- Separate password management
- No Single Sign-On (SSO)
- Additional administrative effort

---

# Salesforce Authentication

Salesforce Authentication allows users to log in using their Salesforce credentials.

### Features

- Single Sign-On (SSO)
- Centralized authentication
- Enterprise identity management

### Advantages

- Better user experience
- Reduced password management
- Improved enterprise security

### Limitations

- Requires Salesforce integration
- Additional configuration

---

# Authentication Comparison

| Feature | Native Authentication | Salesforce Authentication |
|----------|----------------------|---------------------------|
| Password Stored In | IICS | Salesforce |
| Single Sign-On | No | Yes |
| Easy Setup | Yes | Moderate |
| Enterprise Ready | Moderate | High |

---

# Creating a User

General procedure:

1. Open **Administrator Console**.
2. Navigate to **Users**.
3. Click **New User**.
4. Enter:
   - Name
   - Email
   - Authentication Type
   - Role
   - License
5. Save the user.

---

# User Actions

Administrators can perform several actions:

- Create User
- Edit User
- Lock User
- Unlock User
- Reset Password
- Activate User
- Deactivate User
- Delete User

---

# Edit User

User details that can be modified include:

- Name
- Email Address
- Authentication Method
- Assigned Role
- Group Membership
- Account Status

---

# Best Practices

- Assign unique accounts to every user.
- Follow the Principle of Least Privilege.
- Use strong passwords for Native Authentication.
- Disable inactive accounts.
- Review user access periodically.

---

# Enterprise Example

A software company has:

- 5 Administrators
- 20 Developers
- 15 Test Engineers
- 10 Business Analysts

Each user receives only the permissions required for their job role, reducing security risks and improving governance.

---

# Advantages of Proper User Management

- Improved security
- Better accountability
- Easier administration
- Regulatory compliance
- Efficient resource management

---

# Common Mistakes

❌ Sharing login credentials.

✔ Each user must have an individual account.

---

❌ Assigning Administrator privileges to all users.

✔ Grant only the permissions required for each role.

---

❌ Ignoring inactive users.

✔ Disable or remove unused accounts regularly.

---

# Important Points

✔ Every user must be authenticated.

✔ Authentication verifies identity.

✔ User Management controls access to organizational resources.

✔ Proper administration improves enterprise security.

---

# Examination Questions

### 2 Marks

1. Define User Management.
2. What is Native Authentication?
3. What is Salesforce Authentication?

---

### 5 Marks

1. Explain the User Creation process in IICS.
2. Differentiate Native Authentication and Salesforce Authentication.

---

### 10 Marks

Explain User Management in IICS with suitable examples.

---

# Quick Revision

| Remember |
|-----------|
| User Management controls user access |
| Native Authentication stores credentials in IICS |
| Salesforce Authentication supports Single Sign-On |
| Every user should have an individual account |
| Follow the Principle of Least Privilege |

---

# Chapter Summary

In this chapter, we learned:

- User Management
- User Authentication
- Native Authentication
- Salesforce Authentication
- User Creation
- User Actions
- Editing Users
- Security Best Practices

Effective User Management is essential for maintaining a secure, scalable, and well-governed Informatica Cloud environment.

---

# End of Chapter 3
# Chapter 4

# User Statistics

---

## Introduction

Managing users is only one part of administration. Administrators must also monitor user activities to ensure that organizational resources are used efficiently and securely.

User Statistics in Informatica Intelligent Cloud Services (IICS) provide valuable information about user accounts, login activity, license usage, and system utilization.

These statistics help administrators make informed decisions regarding user management and system optimization.

---

# Learning Objectives

After completing this chapter, students will be able to:

- Explain User Statistics.
- Describe List View and Chart View.
- Interpret user activity reports.
- Explain the importance of monitoring users.
- Analyze user utilization trends.

---

# What are User Statistics?

User Statistics are administrative reports that provide information about users and their activities within an organization.

The statistics help administrators monitor:

- User activity
- Login history
- Account status
- License utilization
- User roles
- Authentication methods

---

# Why are User Statistics Important?

User Statistics help organizations to:

- Improve security.
- Monitor active users.
- Detect inactive accounts.
- Optimize license allocation.
- Support auditing and compliance.
- Improve administrative decision-making.

---

# User Statistics Dashboard

The User Statistics Dashboard provides an overview of user information.

Typical information includes:

- Total Users
- Active Users
- Inactive Users
- Locked Accounts
- Last Login
- Assigned Roles
- License Usage

---

# List View

## What is List View?

List View displays user information in a table.

Example information:

| User | Role | Status | Last Login |
|------|------|---------|------------|
| Admin | Organization Administrator | Active | Today |
| Rahul | Developer | Active | Yesterday |
| Priya | Analyst | Inactive | 30 Days Ago |

---

# Advantages of List View

- Detailed information
- Easy searching
- Sorting capability
- Filtering support
- Administrative management

---

# Chart View

Chart View displays user statistics graphically.

Common charts include:

- Active vs Inactive Users
- User Role Distribution
- Authentication Types
- License Utilization
- Login Trends

Charts help administrators quickly identify patterns and trends.

---

# Benefits of Chart View

- Easy visualization
- Better reporting
- Trend analysis
- Executive dashboards
- Capacity planning

---

# Comparison: List View vs Chart View

| Feature | List View | Chart View |
|----------|-----------|------------|
| Detailed Records | ✔ | ✘ |
| Graphical Display | ✘ | ✔ |
| Trend Analysis | Limited | Excellent |
| Executive Reporting | Moderate | Excellent |
| Data Filtering | ✔ | Limited |

---

# Monitoring User Activity

Administrators should regularly monitor:

- Failed login attempts
- Inactive users
- Locked accounts
- New user registrations
- License usage
- User roles
- Authentication methods

Regular monitoring helps maintain a secure and efficient environment.

---

# Enterprise Example

A university has:

- 600 Users
- 500 Active Users
- 70 Inactive Users
- 30 Locked Accounts

After reviewing the User Statistics Dashboard, the administrator decides to:

- Disable unused accounts.
- Reallocate licenses.
- Unlock valid user accounts.
- Investigate repeated failed login attempts.

---

# Best Practices

- Review user statistics weekly.
- Remove inactive users.
- Monitor failed login attempts.
- Generate monthly reports.
- Optimize license allocation.

---

# Advantages

- Better administration
- Improved security
- Efficient license utilization
- Better compliance
- Easier auditing

---

# Common Mistakes

❌ Ignoring inactive users.

✔ Disable unused accounts periodically.

---

❌ Not monitoring failed logins.

✔ Investigate repeated authentication failures.

---

❌ Allocating licenses without reviewing statistics.

✔ Use reports to optimize license usage.

---

# Important Points

✔ User Statistics help administrators monitor system usage.

✔ List View provides detailed records.

✔ Chart View provides graphical analysis.

✔ Statistics improve security and resource management.

---

# Examination Questions

### 2 Marks

1. What are User Statistics?
2. Define List View.
3. Define Chart View.

---

### 5 Marks

1. Differentiate List View and Chart View.
2. Explain the importance of User Statistics.

---

### 10 Marks

Discuss User Statistics in IICS and explain how they support effective user administration.

---

# Quick Revision

| Remember |
|-----------|
| User Statistics monitor user activity |
| List View provides detailed records |
| Chart View provides graphical analysis |
| Statistics improve security |
| Helps optimize license utilization |

---

# Chapter Summary

In this chapter, we studied:

- User Statistics
- User Statistics Dashboard
- List View
- Chart View
- Monitoring user activity
- Enterprise applications
- Best practices

User Statistics enable administrators to monitor users effectively, improve security, and optimize organizational resources.

---

# End of Chapter 4
# Chapter 5

# User Groups

---

## Introduction

As organizations grow, the number of users increases significantly. Managing permissions individually for every user becomes difficult and time-consuming.

To simplify administration, Informatica Intelligent Cloud Services (IICS) provides **User Groups**. A User Group is a logical collection of users with similar responsibilities, allowing administrators to manage multiple users together.

---

# Learning Objectives

After completing this chapter, students will be able to:

- Define User Groups.
- Explain the purpose of User Groups.
- Describe the process of creating User Groups.
- Explain how User Groups simplify administration.
- Differentiate User Groups from User Roles.

---

# What is a User Group?

A **User Group** is a collection of users who perform similar tasks or require similar access within an organization.

Instead of assigning permissions to each individual user, administrators manage users collectively through groups.

---

# Why are User Groups Required?

Consider an organization with:

- 100 Developers
- 50 Business Analysts
- 20 Data Engineers
- 10 Administrators

Assigning permissions individually to every employee would be difficult.

Instead, administrators create groups such as:

- Developers
- Business Analysts
- Data Engineers
- Administrators

Users are simply added to the appropriate group.

---

# User Group Structure

```
Organization

│

├── Administrators

├── Developers

├── Data Engineers

├── Business Analysts

└── Auditors
```

Each group contains users with similar responsibilities.

---

# Benefits of User Groups

- Simplifies administration
- Reduces repetitive configuration
- Improves consistency
- Supports scalability
- Makes permission management easier
- Facilitates auditing

---

# Creating a User Group

General procedure:

1. Open **Administrator Console**.
2. Navigate to **User Groups**.
3. Select **Create User Group**.
4. Enter:
   - Group Name
   - Description
5. Save the group.
6. Add users.
7. Verify membership.

---

# Managing User Groups

Administrators can:

- Create groups
- Rename groups
- Edit group details
- Add users
- Remove users
- Delete groups

---

# Group Membership

A user may belong to:

- One group
- Multiple groups

Example:

**Rahul**

- Developers
- API Development Team
- Cloud Migration Team

This provides flexibility in managing users.

---

# Enterprise Example

ABC Bank has the following departments:

- Retail Banking
- Corporate Banking
- Loans
- Information Technology
- Human Resources

Each department is represented by a separate User Group.

When a new employee joins the IT department, the administrator only needs to add the user to the **IT Group**.

---

# User Groups vs User Roles

| User Groups | User Roles |
|--------------|------------|
| Organize users | Define permissions |
| Administrative convenience | Security control |
| Logical grouping | Access control |
| Simplifies management | Controls system access |

---

# Advantages

- Easy administration
- Better organization
- Reduced configuration effort
- Consistent user management
- Improved scalability

---

# Limitations

- Groups alone do not define permissions.
- Poor group design increases management complexity.
- Periodic review of memberships is necessary.

---

# Best Practices

- Create groups based on business functions.
- Use meaningful group names.
- Review memberships regularly.
- Remove inactive users.
- Avoid duplicate groups.

---

# Common Mistakes

❌ Creating unnecessary groups.

✔ Create groups only when required.

---

❌ Adding all users to the same group.

✔ Organize users according to their responsibilities.

---

❌ Never reviewing group memberships.

✔ Perform periodic membership reviews.

---

# Important Points

✔ User Groups simplify administration.

✔ A user may belong to multiple groups.

✔ User Groups organize users but do not directly assign permissions.

✔ Groups improve scalability and consistency.

---

# Examination Questions

### 2 Marks

1. Define User Group.
2. State two benefits of User Groups.

---

### 5 Marks

1. Explain the process of creating a User Group.
2. Differentiate User Groups and User Roles.

---

### 10 Marks

Explain User Groups in IICS with suitable examples and architecture.

---

# Quick Revision

| Remember |
|-----------|
| Logical collection of users |
| Simplifies administration |
| Users can belong to multiple groups |
| Does not directly define permissions |
| Supports enterprise scalability |

---

# Chapter Summary

In this chapter, we studied:

- User Groups
- Group creation
- Group management
- Group membership
- Enterprise applications
- Benefits and limitations

User Groups help administrators manage large numbers of users efficiently while maintaining an organized and scalable administrative structure.

---

# End of Chapter 5