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
# Chapter 6

# User Roles

---

## Introduction

In an enterprise environment, every user does not require the same level of access. For example, an Organization Administrator needs full administrative privileges, whereas a Data Analyst may only need permission to view reports.

To manage access efficiently and securely, Informatica Intelligent Cloud Services (IICS) uses **User Roles**. A User Role is a collection of permissions assigned to users or user groups based on their responsibilities.

---

# Learning Objectives

After completing this chapter, students will be able to:

- Define User Roles.
- Explain Role-Based Access Control (RBAC).
- Describe System-defined Roles.
- Explain Custom Roles.
- Apply the Principle of Least Privilege.
- Differentiate User Roles from User Groups.

---

# What is a User Role?

A **User Role** is a collection of permissions that determines what actions a user can perform within the IICS environment.

Roles control access to:

- Assets
- Connections
- Mappings
- Tasks
- Runtime Environments
- Administrative functions

Instead of assigning permissions individually, administrators assign a role containing the required permissions.

---

# Why are User Roles Required?

Without User Roles:

- Difficult permission management
- Increased security risks
- Higher chance of configuration errors
- Complex administration

With User Roles:

- Centralized permission management
- Improved security
- Easier administration
- Better compliance
- Faster onboarding of new users

---

# Role-Based Access Control (RBAC)

**Role-Based Access Control (RBAC)** is a security model where permissions are assigned to roles rather than directly to individual users.

Users inherit permissions through the roles assigned to them.

---

# RBAC Architecture

```
Users

↓

Assigned Role

↓

Permissions

↓

Assets and Resources
```

Example:

```
Priya

↓

Developer Role

↓

Read
Create
Modify
Execute

↓

Mappings
Tasks
Connections
```

---

# System-defined Roles

IICS provides predefined roles for common administrative and operational tasks.

Examples include:

- Organization Administrator
- Application Administrator
- Security Administrator
- Developer
- Operator
- Monitor

These roles contain predefined permission sets and are suitable for most organizations.

---

# Organization Administrator

### Responsibilities

- Manage users
- Manage groups
- Create roles
- Configure Secure Agents
- Allocate licenses
- Monitor organization resources

This role has the highest administrative privileges.

---

# Developer Role

Typical responsibilities:

- Create mappings
- Develop integration tasks
- Configure transformations
- Test workflows
- Deploy assets

Developers generally do not manage users or organizational settings.

---

# Operator Role

Operators are responsible for monitoring and executing integration tasks.

Typical activities include:

- Running jobs
- Monitoring execution
- Restarting failed tasks
- Reviewing logs
- Generating reports

---

# Custom Roles

Organizations may require permissions that are not available in predefined roles.

A **Custom Role** allows administrators to create a role with a specific combination of permissions.

Example:

A "Data Quality Reviewer" role may require:

- Read access
- Execute profiling jobs
- View reports

without requiring administrative privileges.

---

# Creating a Custom Role

General procedure:

1. Open **Administrator Console**.
2. Navigate to **Roles**.
3. Select **Create Role**.
4. Enter:
   - Role Name
   - Description
5. Select required permissions.
6. Save the role.
7. Assign users or groups.

---

# Assigning Roles

Roles can be assigned to:

- Individual Users
- User Groups

Assigning roles to groups simplifies administration in large organizations.

---

# Principle of Least Privilege (PoLP)

The **Principle of Least Privilege** states that:

> Every user should receive only the permissions required to perform assigned responsibilities.

### Benefits

- Improved security
- Reduced accidental changes
- Lower insider risk
- Better compliance
- Easier auditing

---

# User Roles vs User Groups

| User Roles | User Groups |
|------------|-------------|
| Define permissions | Organize users |
| Security mechanism | Administrative grouping |
| Control system access | Simplify user management |
| Permission-based | Membership-based |

---

# Enterprise Example

A multinational bank has:

- Organization Administrator
- Data Engineers
- Business Analysts
- Auditors

Recommended role assignments:

| User | Assigned Role |
|------|---------------|
| IT Administrator | Organization Administrator |
| Data Engineer | Developer |
| Business Analyst | Monitor |
| Internal Auditor | Read-only Custom Role |

This ensures each user receives only the permissions necessary for their responsibilities.

---

# Advantages

- Better security
- Easier administration
- Centralized permission management
- Supports compliance
- Reduces configuration errors

---

# Best Practices

- Use System-defined Roles whenever possible.
- Create Custom Roles only when necessary.
- Review role assignments regularly.
- Document custom permissions.
- Apply the Principle of Least Privilege.

---

# Common Mistakes

❌ Assigning Administrator privileges to every user.

✔ Grant only the permissions required.

---

❌ Creating too many Custom Roles.

✔ Keep role definitions simple and reusable.

---

❌ Never reviewing user permissions.

✔ Conduct periodic access reviews.

---

# Important Points

✔ Roles define permissions.

✔ RBAC improves enterprise security.

✔ Custom Roles provide flexibility.

✔ Follow the Principle of Least Privilege.

---

# Examination Questions

### 2 Marks

1. Define User Role.
2. What is RBAC?
3. What is the Principle of Least Privilege?

---

### 5 Marks

1. Explain System-defined Roles and Custom Roles.
2. Differentiate User Roles and User Groups.

---

### 10 Marks

Explain Role-Based Access Control (RBAC) in IICS with a suitable diagram and enterprise example.

---

# Quick Revision

| Remember |
|-----------|
| User Roles define permissions |
| RBAC assigns permissions through roles |
| System-defined Roles are built into IICS |
| Custom Roles are created for specific requirements |
| Apply the Principle of Least Privilege |

---

# Chapter Summary

In this chapter, we learned:

- User Roles
- Role-Based Access Control (RBAC)
- System-defined Roles
- Custom Roles
- Role Assignment
- Principle of Least Privilege
- Enterprise applications
- Best practices

User Roles are a fundamental security mechanism in IICS, ensuring that users receive appropriate permissions while protecting organizational resources.

---

# End of Chapter 6
# Chapter 7

# IICS Runtime Environments

---

## Introduction

Designing an integration task is only one part of the integration process. The designed task must be executed in an environment capable of connecting to data sources, processing transformations, and loading data into target systems.

This execution platform is known as the **Runtime Environment**.

In Informatica Intelligent Cloud Services (IICS), Runtime Environments execute mappings, synchronization tasks, APIs, and workflows.

---

# Learning Objectives

After completing this chapter, students will be able to:

- Define Runtime Environment.
- Explain the purpose of Runtime Environments.
- Describe Hosted Agent.
- Describe Secure Agent Runtime.
- Compare Hosted Agent and Secure Agent.
- Recommend suitable Runtime Environments for different enterprise scenarios.

---

# What is a Runtime Environment?

A **Runtime Environment** is the execution platform where Informatica integration jobs are processed.

It performs the following tasks:

- Executes mappings
- Runs synchronization tasks
- Connects to data sources
- Applies transformations
- Loads target systems
- Generates execution logs
- Reports execution status

Without a Runtime Environment, mappings created in IICS cannot be executed.

---

# Runtime Environment Architecture

```
                Informatica Cloud

                        │

             Administrator Console

                        │

               Runtime Environment

             ┌──────────┴──────────┐

      Hosted Runtime        Secure Agent

             │                     │

      Cloud Applications     Enterprise Systems

                              Oracle

                              SQL Server

                              SAP

                              Files

                              APIs
```

---

# Functions of Runtime Environment

A Runtime Environment is responsible for:

- Executing jobs
- Managing connections
- Processing transformations
- Monitoring execution
- Logging activities
- Communicating with Informatica Cloud

---

# Types of Runtime Environments

IICS supports two primary Runtime Environments:

1. Hosted Agent
2. Secure Agent

---

# Hosted Agent

The Hosted Agent is fully managed by Informatica.

No installation is required.

### Features

- Cloud-managed
- Automatic updates
- No maintenance
- Supports cloud-to-cloud integration

### Advantages

- Easy deployment
- No infrastructure management
- Automatic maintenance
- High availability

### Limitations

- Cannot directly access on-premises databases
- Limited customization

---

# Secure Agent

Secure Agent is installed inside the customer's network.

It securely connects Informatica Cloud with enterprise resources.

### Features

- Installed locally
- Supports hybrid cloud
- Connects to on-premises systems
- Customer-managed

### Advantages

- Access to enterprise databases
- Supports hybrid integration
- Greater deployment flexibility
- Better control

### Limitations

- Installation required
- Requires maintenance
- Depends on local hardware resources

---

# Hosted Agent vs Secure Agent

| Feature | Hosted Agent | Secure Agent |
|----------|--------------|--------------|
| Installation | Not Required | Required |
| Managed By | Informatica | Customer |
| Cloud Integration | Excellent | Excellent |
| On-Premises Connectivity | No | Yes |
| Infrastructure | Cloud | Local Server |
| Maintenance | Automatic | Customer Managed |

---

# Runtime Selection

Use **Hosted Agent** when:

- All applications are cloud-based.
- No on-premises systems are involved.
- Fast deployment is required.

Use **Secure Agent** when:

- Oracle or SQL Server databases are on-premises.
- SAP or ERP systems are inside the enterprise network.
- Hybrid cloud architecture is used.
- Greater administrative control is required.

---

# Enterprise Example

### Scenario 1

Applications:

- Salesforce
- Workday
- ServiceNow

Recommended Runtime:

✔ Hosted Agent

---

### Scenario 2

Applications:

- Oracle Database
- SAP ERP
- Local File Server

Recommended Runtime:

✔ Secure Agent

---

### Scenario 3

Applications:

- Salesforce
- Oracle Database
- SQL Server

Recommended Runtime:

✔ Secure Agent

because cloud applications must securely communicate with internal systems.

---

# Advantages of Runtime Environments

- Secure execution
- Reliable job processing
- Enterprise scalability
- Flexible deployment
- Efficient monitoring

---

# Best Practices

- Choose the appropriate Runtime Environment based on business requirements.
- Monitor runtime performance regularly.
- Separate Development, Testing, and Production environments.
- Keep Secure Agents updated.
- Allocate sufficient system resources.

---

# Common Mistakes

❌ Using Hosted Agent for on-premises database access.

✔ Use Secure Agent for hybrid environments.

---

❌ Installing multiple Secure Agents without planning.

✔ Design Runtime Environments according to organizational architecture.

---

# Important Points

✔ Runtime Environment executes integration tasks.

✔ Hosted Agent is managed by Informatica.

✔ Secure Agent is managed by the customer.

✔ Hybrid cloud environments require Secure Agent.

---

# Examination Questions

### 2 Marks

1. Define Runtime Environment.
2. What is Hosted Agent?
3. What is Secure Agent?

---

### 5 Marks

1. Compare Hosted Agent and Secure Agent.
2. Explain the functions of Runtime Environment.

---

### 10 Marks

Explain Runtime Environments in IICS with suitable architecture and enterprise examples.

---

# Quick Revision

| Remember |
|-----------|
| Runtime Environment executes integration jobs |
| Hosted Agent is cloud-managed |
| Secure Agent is locally installed |
| Secure Agent supports hybrid cloud |
| Runtime Environment connects cloud and enterprise systems |

---

# Chapter Summary

In this chapter, we studied:

- Runtime Environment
- Hosted Agent
- Secure Agent
- Runtime Architecture
- Runtime Selection
- Enterprise Deployment
- Best Practices

Runtime Environments are responsible for executing integration tasks and enabling secure communication between Informatica Cloud and enterprise systems.

---

# End of Chapter 7
# Chapter 8

# Informatica Cloud Secure Agent

---

## Introduction

Modern enterprises store data across cloud platforms, on-premises databases, ERP systems, APIs, and file servers. Since Informatica Intelligent Cloud Services (IICS) is cloud-based, it requires a secure mechanism to communicate with internal enterprise systems.

This mechanism is provided by the **Secure Agent**.

The Secure Agent acts as the execution engine of IICS, securely transferring data between Informatica Cloud and enterprise resources.

---

# Learning Objectives

After completing this chapter, students will be able to:

- Define Secure Agent.
- Explain Secure Agent Architecture.
- Describe Agent Manager and Agent Core.
- Explain the startup process.
- Differentiate Local User and Network User execution.
- Describe Secure Agent installation.
- Explain common troubleshooting techniques.

---

# What is Secure Agent?

A **Secure Agent** is a lightweight application installed within an organization's network.

It enables secure communication between Informatica Intelligent Cloud Services (IICS) and enterprise resources.

The Secure Agent performs:

- Data extraction
- Data loading
- Transformation execution
- Job execution
- API execution
- Monitoring
- Logging

---

# Why is Secure Agent Required?

Without Secure Agent:

- Cloud cannot directly access internal databases.
- Hybrid cloud integration is not possible.
- Enterprise resources remain isolated.

With Secure Agent:

- Secure communication is established.
- Enterprise systems remain protected.
- Data integration becomes possible.

---

# Secure Agent Architecture

```
             Informatica Cloud

                    │

             HTTPS (TLS)

                    │

             Secure Agent

        ┌─────────┼─────────┐

     Database   Applications   Files

      Oracle       SAP         CSV

    SQL Server   Salesforce    XML

      MySQL       REST API     JSON
```

---

# Communication Flow

```
Create Mapping

↓

Submit Job

↓

Secure Agent Receives Task

↓

Connect Source

↓

Read Data

↓

Apply Transformations

↓

Load Target

↓

Send Status to Cloud
```

---

# Components of Secure Agent

Major components include:

- Agent Manager
- Agent Core
- Data Integration Service
- Process Server
- Connector Services
- Metadata Service
- Logging Service

Each component performs a specialized function.

---

# Agent Manager

The **Agent Manager** controls the Secure Agent.

Responsibilities include:

- Starting services
- Stopping services
- Monitoring services
- Downloading updates
- Restarting failed services
- Reporting status

Think of the Agent Manager as the **supervisor** of the Secure Agent.

---

# Agent Core

The **Agent Core** performs the actual integration work.

Responsibilities include:

- Executing mappings
- Running workflows
- Loading connectors
- Processing transformations
- Managing execution

Agent Core is the **execution engine** of the Secure Agent.

---

# Secure Agent Startup

The startup process follows these steps:

1. Windows starts the Secure Agent service.
2. Agent Manager initializes.
3. Configuration files are loaded.
4. Agent Core starts.
5. Runtime services initialize.
6. Secure connection with Informatica Cloud is established.
7. Agent status changes to **Running**.

---

# Local User vs Network User

| Local User | Network User |
|-------------|--------------|
| Local machine access | Domain/network access |
| Simple setup | Enterprise deployment |
| Limited shared resource access | Access to shared folders and Active Directory |
| Suitable for development | Suitable for production |

---

# Minimum System Requirements

| Component | Recommended |
|-----------|-------------|
| Processor | 64-bit Dual Core or higher |
| RAM | 8 GB minimum (16 GB recommended) |
| Disk Space | 10 GB minimum |
| Internet | Stable HTTPS connectivity |
| Operating System | Supported Windows or Linux versions |

---

# Installing Secure Agent

General installation steps:

1. Log in to IICS.
2. Navigate to **Administrator → Runtime Environments**.
3. Download Secure Agent.
4. Run the installer.
5. Accept the license agreement.
6. Enter Informatica credentials.
7. Register the Secure Agent.
8. Wait for components to download.
9. Verify the agent status.

---

# Verifying Installation

After installation, verify:

- Agent Status = Running
- Runtime Environment = Online
- Services = Healthy
- Latest Version Installed

A successful installation indicates that the Secure Agent is ready to execute integration jobs.

---

# Common Installation Errors

| Problem | Possible Cause | Solution |
|----------|----------------|----------|
| Agent Offline | Network issue | Check internet and firewall |
| Registration Failed | Incorrect credentials | Verify login details |
| Service Not Starting | Permission issue | Run as Administrator |
| Database Connection Failed | Invalid configuration | Check connection settings |
| Slow Performance | Low system resources | Increase RAM or CPU |

---

# Best Practices

- Install on a dedicated server.
- Keep the Secure Agent updated.
- Monitor CPU and memory usage.
- Review logs regularly.
- Separate Development, Testing, and Production environments.
- Use secure service accounts for enterprise deployments.

---

# Enterprise Example

A manufacturing company stores production data in an on-premises Oracle Database while using Salesforce CRM in the cloud.

A Secure Agent installed inside the corporate network enables secure data exchange between Oracle Database and Salesforce without exposing the internal database to the Internet.

---

# Advantages

- Secure communication
- Hybrid cloud integration
- Reliable execution
- Enterprise scalability
- Flexible deployment

---

# Limitations

- Requires installation
- Needs local hardware resources
- Requires periodic maintenance

---

# Important Points

✔ Secure Agent is the execution engine of IICS.

✔ It connects cloud services with enterprise resources.

✔ Agent Manager controls services.

✔ Agent Core executes integration jobs.

✔ Secure Agent uses secure outbound HTTPS communication.

---

# Examination Questions

### 2 Marks

1. Define Secure Agent.
2. What is Agent Manager?
3. What is Agent Core?

---

### 5 Marks

1. Explain Secure Agent Architecture.
2. Describe the Secure Agent startup process.
3. Differentiate Local User and Network User.

---

### 10 Marks

Explain Secure Agent Architecture, components, installation, and troubleshooting with suitable diagrams.

---

# Quick Revision

| Remember |
|-----------|
| Secure Agent executes integration jobs |
| Agent Manager manages services |
| Agent Core performs execution |
| Secure communication uses HTTPS |
| Hybrid cloud requires Secure Agent |

---

# Chapter Summary

In this chapter, we learned:

- Secure Agent
- Architecture
- Components
- Agent Manager
- Agent Core
- Startup sequence
- Installation
- Verification
- Troubleshooting
- Best practices

The Secure Agent is the core execution component of Informatica Intelligent Cloud Services, enabling secure and reliable integration between cloud applications and enterprise systems.

---

# End of Chapter 8