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

# Chapter 3

# User Management

---

## Learning Objectives

After completing this chapter, students will be able to:

- Explain user management in IICS.
- Describe different authentication methods.
- Create and manage users.
- Edit user profiles.
- Perform user administration tasks.
- Apply security best practices.

---

# Introduction

User Management is one of the most important administrative functions in Informatica Intelligent Cloud Services (IICS).

Every user who accesses the platform must be authenticated, assigned appropriate roles, and granted only the permissions required to perform assigned tasks.

Proper user management ensures:

- Secure access
- Accountability
- Regulatory compliance
- Efficient administration

---

# What is User Management?

User Management refers to the process of:

- Creating users
- Authenticating users
- Assigning roles
- Managing permissions
- Monitoring activity
- Disabling or deleting users

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

User Login

↓

Perform Tasks

↓

Monitor Activity

↓

Deactivate User
```

---

# User Authentication

Authentication verifies the identity of a user before granting access to IICS.

IICS supports multiple authentication mechanisms.

---

## Native Authentication

In Native Authentication, user credentials are stored within Informatica Cloud.

### Characteristics

- Username and password managed by IICS.
- Simple to configure.
- Suitable for small organizations.
- Independent of external identity providers.

### Advantages

- Easy setup
- Minimal configuration
- Quick onboarding

### Limitations

- Separate password management
- Additional administrative effort
- Not ideal for large enterprises

---

## Salesforce Authentication

Salesforce Authentication enables users to log in using Salesforce credentials.

### Benefits

- Single Sign-On (SSO)
- Centralized identity management
- Reduced password fatigue
- Improved user experience

---

## Authentication Comparison

| Feature | Native | Salesforce |
|----------|--------|------------|
| Password Stored In | IICS | Salesforce |
| SSO Support | No | Yes |
| Enterprise Ready | Moderate | High |
| Administration | Simple | Centralized |

---

# Creating a User

General Procedure:

1. Open Administrator Console.
2. Navigate to **Users**.
3. Click **New User**.
4. Enter:
   - Username
   - Email Address
   - Authentication Type
   - Role
   - License
5. Save the configuration.
6. Notify the user.

---

# User Actions

Administrators can perform several actions:

- Create User
- Edit User
- Reset Password
- Lock User
- Unlock User
- Activate User
- Deactivate User
- Delete User

---

# Editing a User

User properties that can be modified include:

- Name
- Email
- Authentication Method
- Role
- Group Membership
- Status

Changes should be documented according to organizational policies.

---

# Security Best Practices

- Use Multi-Factor Authentication (MFA) where available.
- Follow the Principle of Least Privilege.
- Remove inactive accounts regularly.
- Review user permissions periodically.
- Use strong password policies for Native Authentication.

---

# Enterprise Example

A multinational bank has:

- 5 Administrators
- 20 Developers
- 150 Business Users
- 50 Analysts

Each user category receives different permissions based on their responsibilities.

This minimizes security risks and ensures compliance.

---

# Classroom Activity

Design a user management plan for a university.

Identify:

- Administrator
- Faculty
- Students
- External Users

Specify authentication methods and access permissions.

---

# Discussion Question

Should every employee have Administrator privileges?

Justify your answer based on security and operational efficiency.

---

# Common Mistakes

❌ Assigning Administrator role to all users.

✔ Assign only the minimum required privileges.

---

❌ Leaving inactive accounts enabled.

✔ Disable or remove inactive accounts promptly.

---

❌ Sharing login credentials.

✔ Every user must have an individual account.

---

# Summary

This chapter covered:

- User Management
- User Authentication
- Native Authentication
- Salesforce Authentication
- User Creation
- User Administration
- Security Best Practices

Effective user management is fundamental to maintaining a secure and well-governed IICS environment.

---

# End of Chapter 3
# Chapter 4

# User Statistics

---

## Learning Objectives

After completing this chapter, students will be able to:

- Explain the purpose of User Statistics.
- Interpret List View and Chart View.
- Monitor user activity.
- Analyze user behavior using administrative dashboards.
- Use statistics for capacity planning and security monitoring.

---

# Introduction

In enterprise cloud environments, simply creating users is not enough. Administrators must continuously monitor user activity to ensure efficient resource utilization, maintain security, and comply with organizational policies.

IICS provides User Statistics to help administrators understand how users interact with the platform.

User Statistics help answer questions such as:

- Who is actively using the system?
- How many users logged in today?
- Which users are inactive?
- Are licenses being fully utilized?
- Are there unusual login patterns?

---

# What are User Statistics?

User Statistics provide summarized information about:

- Active Users
- Inactive Users
- Login Frequency
- User Activity
- License Consumption
- Authentication Status

These statistics assist administrators in making informed decisions about user management and license allocation.

---

# Why are User Statistics Important?

Monitoring user statistics helps organizations to:

- Improve security.
- Detect inactive accounts.
- Optimize license usage.
- Identify unusual access patterns.
- Support compliance and auditing.

---

# User Statistics Dashboard

The User Statistics Dashboard provides a centralized view of user-related information.

Typical metrics include:

- Total Users
- Active Users
- Inactive Users
- Last Login
- Authentication Type
- Assigned Roles
- License Usage

---

# List View

## What is List View?

List View displays user information in a tabular format.

Example columns include:

- User Name
- Email Address
- Role
- Authentication Type
- Status
- Last Login
- License Type

### Advantages

- Easy to search.
- Supports sorting.
- Supports filtering.
- Useful for administrative tasks.

---

# Example List View

| User | Role | Status | Last Login |
|------|------|---------|------------|
| Admin | Administrator | Active | Today |
| John | Developer | Active | Yesterday |
| Alice | Analyst | Inactive | 30 Days Ago |

---

# Chart View

Chart View presents statistical information graphically.

Common charts include:

- Active vs Inactive Users
- Authentication Methods
- Role Distribution
- License Usage
- Login Trends

---

# Benefits of Chart View

- Easy visualization.
- Quick trend identification.
- Executive reporting.
- Better decision-making.
- Capacity planning.

---

# Comparing List View and Chart View

| Feature | List View | Chart View |
|----------|-----------|------------|
| Detailed Information | ✔ | ✘ |
| Trend Analysis | ✘ | ✔ |
| Filtering | ✔ | Limited |
| Executive Dashboard | ✘ | ✔ |

---

# Monitoring User Activity

Administrators should monitor:

- Failed Login Attempts
- Dormant Accounts
- Frequent Login Failures
- Sudden Increase in Users
- License Utilization

Regular monitoring helps maintain a secure and efficient environment.

---

# Enterprise Scenario

A university has:

- 1 Organization Administrator
- 30 Faculty Members
- 300 Students

After reviewing User Statistics, the administrator discovers:

- 50 student accounts have never been used.
- 10 faculty accounts have been inactive for six months.
- Several licenses remain unused.

The administrator can:

- Disable unused accounts.
- Reallocate licenses.
- Improve resource utilization.

---

# Best Practices

- Review user statistics weekly.
- Remove inactive users.
- Monitor license utilization.
- Investigate unusual login activity.
- Generate periodic reports.

---

# Classroom Activity

Analyze the following scenario:

An organization has:

- 500 Users
- 300 Active
- 150 Inactive
- 50 Locked Accounts

Discuss:

- What concerns should the administrator investigate?
- Which corrective actions should be taken?

---

# Discussion Question

How can User Statistics improve organizational security and operational efficiency?

---

# Faculty Tips

Explain User Statistics using examples from:

- Learning Management Systems (Moodle)
- Microsoft Teams
- Google Classroom
- University ERP Systems

Students can easily relate to login statistics and user dashboards from these platforms.

---

# Common Mistakes

❌ Ignoring inactive accounts.

✔ Regularly review and disable unused accounts.

---

❌ Allocating licenses without reviewing usage.

✔ Use statistics to optimize license allocation.

---

❌ Monitoring only login counts.

✔ Analyze overall user behavior and trends.

---

# Summary

This chapter introduced:

- User Statistics
- List View
- Chart View
- User Monitoring
- Dashboard Analysis
- Enterprise Reporting
- Best Practices

Effective use of User Statistics enables administrators to improve security, optimize resource allocation, and support informed decision-making.

---

# End of Chapter 4