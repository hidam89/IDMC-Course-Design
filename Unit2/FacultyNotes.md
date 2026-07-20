<p align="center">
  <img src="../Assets/banners/unit2-banner.png" width="100%">
</p>
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
# Chapter 5

# User Groups

---

## Course Outcome

CO2

---

## Learning Objectives

After completing this chapter, students will be able to:

- Explain the purpose of User Groups in IICS.
- Create and manage User Groups.
- Assign users to groups.
- Differentiate between User Groups and User Roles.
- Apply User Groups in enterprise environments.

---

# Introduction

As organizations grow, managing permissions for hundreds or thousands of individual users becomes increasingly difficult. Assigning permissions to each user separately is time-consuming and prone to errors.

IICS addresses this challenge through **User Groups**, which allow administrators to organize users with similar responsibilities and manage them collectively.

---

# What is a User Group?

A **User Group** is a logical collection of users who share similar responsibilities or require similar access privileges.

Instead of assigning permissions individually, administrators can assign permissions to a group, and every member of that group inherits the assigned access.

---

# Why are User Groups Required?

Consider an organization with:

- 50 Data Engineers
- 20 Data Analysts
- 10 Administrators
- 30 Business Users

Assigning permissions individually to 110 users is inefficient.

Instead, the administrator creates groups:

- Data Engineers
- Data Analysts
- Administrators
- Business Users

Permissions are then managed at the group level.

---

# User Group Architecture

```
Organization

│

├── Administrators

├── Developers

├── Analysts

├── Business Users

└── Auditors
```

Each group contains multiple users who perform similar tasks.

---

# Advantages of User Groups

- Simplifies administration.
- Reduces repetitive configuration.
- Supports scalability.
- Improves consistency.
- Minimizes configuration errors.
- Simplifies auditing.

---

# Creating a User Group

General procedure:

1. Open the **Administrator** console.
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
- Edit groups
- Rename groups
- Add members
- Remove members
- Delete groups

---

# Group Membership

A user may belong to:

- One group
- Multiple groups

Example:

John belongs to:

- Developers
- API Team
- Cloud Migration Project

This enables flexible access management.

---

# Enterprise Example

ABC Bank has:

- Retail Banking
- Corporate Banking
- Loan Department
- Digital Banking
- IT Department

Each department becomes a separate User Group.

When a new employee joins the Loan Department, the administrator simply adds the user to the Loan Department group instead of configuring permissions manually.

---

# User Groups vs User Roles

| User Groups | User Roles |
|-------------|------------|
| Organize users | Define permissions |
| Administrative convenience | Access control |
| Users can belong to multiple groups | Users receive privileges through assigned roles |
| Logical grouping | Security implementation |

---

# Best Practices

- Create groups based on business functions.
- Use meaningful naming conventions.
- Review memberships regularly.
- Remove inactive members.
- Avoid creating unnecessary groups.

---

# Common Mistakes

❌ Creating duplicate groups.

✔ Maintain one group for each business function.

---

❌ Adding every user to every group.

✔ Add users only where necessary.

---

❌ Ignoring periodic reviews.

✔ Review memberships regularly.

---

# Classroom Activity

Design User Groups for a university.

Possible groups:

- Faculty
- Students
- Research Scholars
- Administration
- Library Staff

Discuss how grouping simplifies administration.

---

# Discussion Question

Is creating User Groups better than assigning permissions individually?

Justify your answer using a large enterprise example.

---

# Faculty Tips

Explain User Groups using:

- Microsoft Teams
- WhatsApp Groups
- Google Classroom

Students immediately understand grouping concepts because they already use these platforms.

---

# Chapter Summary

This chapter introduced:

- User Groups
- Group Creation
- Group Management
- Group Membership
- Enterprise Applications
- Best Practices
- Administrative Benefits

User Groups simplify administration while improving consistency and scalability.

---

# End of Chapter 5
# Chapter 6

# User Roles

---

## Course Outcome

CO2

---

## Learning Objectives

After completing this chapter, students will be able to:

- Explain the concept of User Roles.
- Describe Role-Based Access Control (RBAC).
- Differentiate between System-defined and Custom Roles.
- Create and assign custom roles.
- Apply the Principle of Least Privilege.
- Design secure access control policies.

---

# Introduction

In an enterprise environment, not every user should have the same level of access. A System Administrator requires complete administrative privileges, while a Business Analyst may only need permission to view reports.

To enforce controlled access, IICS uses **User Roles**.

A User Role defines **what a user is allowed to do** within the Informatica Intelligent Cloud Services (IICS) environment.

---

# What is a User Role?

A **Role** is a collection of permissions that determines which operations a user can perform.

Instead of assigning permissions one by one, administrators assign a predefined role to a user.

Roles improve:

- Security
- Administration
- Compliance
- Consistency
- Scalability

---

# Role-Based Access Control (RBAC)

Role-Based Access Control (RBAC) is an access control mechanism in which permissions are assigned to roles rather than directly to users.

Users obtain permissions by being assigned one or more roles.

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
John

↓

Developer Role

↓

Read
Create
Edit
Execute

↓

Mappings
Tasks
Connections
```

---

# Why RBAC?

Without RBAC

- Difficult administration
- Inconsistent permissions
- Higher security risks
- Increased human errors

With RBAC

- Centralized permission management
- Better governance
- Easier auditing
- Improved security
- Faster onboarding

---

# System-defined Roles

IICS provides several predefined roles.

Examples include:

- Organization Administrator
- Application Administrator
- Security Administrator
- Developer
- Operator
- Monitor
- Business User (depending on licensed services)

These roles contain predefined permission sets and are recommended for common administrative tasks.

---

# Organization Administrator

Responsibilities include:

- Manage users
- Manage groups
- Manage roles
- Manage licenses
- Configure Secure Agents
- Monitor organization resources

This role has the highest level of administrative authority within the organization.

---

# Developer Role

Typical responsibilities:

- Create mappings
- Configure tasks
- Develop integrations
- Test workflows
- Deploy assets

Developers generally do not manage users or organizational settings.

---

# Operator Role

Operators are responsible for day-to-day execution and monitoring.

Typical activities:

- Run jobs
- Monitor execution
- Restart failed tasks
- Review logs
- Generate reports

---

# Custom Roles

Organizations often require permissions that are not fully addressed by predefined roles.

IICS allows administrators to create **Custom Roles**.

A Custom Role combines only the permissions required for a particular job function.

---

# Creating a Custom Role

General steps:

1. Open Administrator Console.
2. Navigate to **Roles**.
3. Select **Create Role**.
4. Enter:
   - Role Name
   - Description
5. Select required permissions.
6. Save the role.
7. Assign users.

---

# Assigning Roles

Roles can be assigned to:

- Individual Users
- User Groups

Assigning roles to groups simplifies administration for large organizations.

---

# Principle of Least Privilege (PoLP)

The Principle of Least Privilege states:

> A user should receive only the permissions necessary to perform assigned duties.

Benefits:

- Reduced attack surface
- Improved compliance
- Lower risk of accidental changes
- Better security

---

# Enterprise Example

A multinational healthcare organization has:

- System Administrators
- Data Engineers
- Data Quality Analysts
- Business Analysts
- Auditors

Recommended role assignments:

| Role | Responsibilities |
|------|------------------|
| Administrator | Complete administration |
| Data Engineer | Develop mappings and integrations |
| Analyst | Read reports and monitor jobs |
| Auditor | Read-only access for compliance |

---

# User Roles vs User Groups

| User Groups | User Roles |
|-------------|------------|
| Organize users | Define permissions |
| Administrative grouping | Security mechanism |
| Multiple memberships possible | Multiple roles can be assigned (as per policy) |
| Simplify management | Control access |

---

# Best Practices

- Follow the Principle of Least Privilege.
- Use System-defined Roles whenever possible.
- Create Custom Roles only when necessary.
- Review role assignments periodically.
- Document all custom roles.
- Remove unnecessary permissions.

---

# Common Misconfigurations

❌ Assigning Organization Administrator to every user.

✔ Grant administrative privileges only to authorized personnel.

---

❌ Creating many overlapping Custom Roles.

✔ Keep role definitions simple and well documented.

---

❌ Never reviewing permissions.

✔ Perform periodic access reviews.

---

# Security Considerations

Improper role assignments may result in:

- Unauthorized access
- Data leakage
- Compliance violations
- Accidental deletion of assets
- Increased insider threats

RBAC is therefore a critical component of enterprise cloud security.

---

# Classroom Activity

Design role assignments for a university.

Identify suitable roles for:

- System Administrator
- Faculty
- Students
- Examination Cell
- Library Staff
- Guest Users

Explain why each role should have different permissions.

---

# Discussion Questions

1. Why is RBAC preferred over assigning permissions individually?

2. How does the Principle of Least Privilege improve cloud security?

3. Under what circumstances should an organization create a Custom Role instead of using a System-defined Role?

---

# Faculty Tips

Use familiar examples such as:

- Windows Administrator vs Standard User
- Google Workspace Admin vs Teacher vs Student
- Moodle Administrator vs Faculty vs Student
- Microsoft Teams Owner vs Member

Students can quickly relate these examples to enterprise RBAC concepts.

---

# Interview Questions

1. What is RBAC?
2. Why are User Roles important?
3. Differentiate User Groups and User Roles.
4. What is the Principle of Least Privilege?
5. When should Custom Roles be created?
6. What are System-defined Roles?

---

# Examination Tips

Students should be able to:

- Define User Roles.
- Explain RBAC with a diagram.
- Compare User Groups and User Roles.
- Discuss System-defined and Custom Roles.
- Explain the Principle of Least Privilege with an example.

---

# Chapter Summary

In this chapter, students learned:

- User Roles
- Role-Based Access Control (RBAC)
- System-defined Roles
- Custom Roles
- Role Assignment
- Principle of Least Privilege
- Enterprise Applications
- Security Best Practices

A well-designed RBAC model strengthens security, simplifies administration, and supports compliance in enterprise cloud environments.

---

# End of Chapter 6
# Chapter 7

# IICS Runtime Environments

---

## Course Outcome

CO2

---

## Learning Objectives

After completing this chapter, students will be able to:

- Explain the concept of Runtime Environments.
- Describe the purpose of Runtime Environments in IICS.
- Differentiate between Cloud Hosted Agent and Secure Agent.
- Explain Runtime Environment Architecture.
- Select appropriate Runtime Environments for enterprise deployments.

---

# Introduction

Enterprise data integration involves connecting numerous systems such as databases, cloud applications, APIs, ERP systems, CRM platforms, and on-premises servers.

While Informatica Intelligent Cloud Services (IICS) provides cloud-based design tools, the actual execution of integration tasks requires a Runtime Environment.

A Runtime Environment acts as the execution engine responsible for processing mappings, synchronization tasks, API calls, and data movement.

Without a Runtime Environment, mappings designed in IICS cannot be executed.

---

# What is a Runtime Environment?

A Runtime Environment is the execution platform where Informatica integration jobs run.

It is responsible for:

- Executing mappings
- Running synchronization tasks
- Processing transformations
- Connecting to source systems
- Loading target systems
- Managing execution logs

It forms the bridge between the IICS cloud platform and enterprise data sources.

---

# Runtime Environment Architecture

```
                 Informatica Cloud

                         │

                Administrator Console

                         │

                Runtime Environment

               ┌─────────┴─────────┐

         Hosted Runtime       Secure Agent

               │                    │

        Cloud Sources       On-Premises Systems

                             Databases

                             Applications

                             ERP

                             File Servers
```

---

# Why Runtime Environments are Required

The Runtime Environment performs several critical functions:

- Executes integration jobs.
- Communicates with enterprise systems.
- Transfers data securely.
- Processes transformations.
- Monitors execution.
- Generates execution logs.

---

# Types of Runtime Environments

IICS primarily supports two Runtime Environments:

1. Informatica Cloud Hosted Agent
2. Informatica Cloud Secure Agent

---

# Informatica Cloud Hosted Agent

The Hosted Agent is managed entirely by Informatica.

The execution infrastructure is maintained in Informatica Cloud.

---

## Characteristics

- No installation required.
- Fully managed by Informatica.
- Automatic maintenance.
- Automatic software updates.
- Suitable for cloud-to-cloud integrations.

---

## Advantages

- Zero infrastructure maintenance.
- Fast deployment.
- High availability.
- Automatic upgrades.
- Reduced operational overhead.

---

## Limitations

- Cannot directly access on-premises systems.
- Limited customization.
- Depends on internet connectivity.

---

# Secure Agent Runtime

The Secure Agent is installed within the customer's infrastructure.

It enables secure communication between Informatica Cloud and enterprise resources.

Typical deployment locations include:

- Windows Server
- Linux Server
- Virtual Machine
- Cloud Virtual Machine

---

## Advantages

- Supports hybrid integration.
- Access to on-premises databases.
- Better enterprise security.
- Flexible deployment.
- Local execution.

---

## Limitations

- Installation required.
- Requires maintenance.
- Hardware resources needed.
- Administrator responsibility.

---

# Hosted Agent vs Secure Agent

| Feature | Hosted Agent | Secure Agent |
|----------|--------------|--------------|
| Installation | Not Required | Required |
| Managed By | Informatica | Customer |
| On-Premises Access | No | Yes |
| Cloud-to-Cloud Integration | Excellent | Excellent |
| Hybrid Integration | Limited | Excellent |
| Maintenance | Automatic | Customer Managed |
| Infrastructure | Informatica Cloud | Customer Environment |

---

# Enterprise Deployment Scenarios

### Scenario 1

Company uses:

- Salesforce
- Workday
- ServiceNow

All applications are cloud-based.

Recommended Runtime:

✔ Hosted Agent

---

### Scenario 2

Company uses:

- Oracle Database
- SAP ERP
- Local File Server
- Active Directory

Recommended Runtime:

✔ Secure Agent

---

### Scenario 3

Company uses:

- Salesforce
- Oracle Database
- SQL Server
- SAP

Recommended Runtime:

✔ Secure Agent

because cloud applications must communicate with on-premises resources.

---

# Runtime Selection Guidelines

Use Hosted Agent when:

- All applications are cloud-based.
- Minimal administration is desired.
- No on-premises connectivity is required.

Use Secure Agent when:

- Enterprise databases are involved.
- Hybrid cloud architecture is used.
- Internal applications must be accessed.
- Enhanced control is required.

---

# Runtime Environment Responsibilities

A Runtime Environment performs:

- Job execution
- Connection management
- Data transfer
- Logging
- Monitoring
- Error handling
- Communication with Informatica Cloud

---

# Enterprise Example

A multinational retail company stores:

- Customer Orders in Salesforce
- Inventory in Oracle Database
- Employee Information in SAP

Because Oracle and SAP are on-premises, Secure Agent is installed inside the corporate network to securely transfer data between local systems and Informatica Cloud.

---

# Best Practices

- Select the Runtime Environment based on business requirements.
- Monitor runtime performance regularly.
- Keep Secure Agent updated.
- Minimize network latency.
- Use separate runtimes for development, testing, and production when appropriate.

---

# Common Mistakes

❌ Using Hosted Agent for on-premises database integration.

✔ Use Secure Agent for hybrid environments.

---

❌ Installing one Secure Agent for every project without planning.

✔ Design Runtime Environments based on organizational architecture and workload.

---

❌ Ignoring runtime monitoring.

✔ Monitor job execution and performance continuously.

---

# Classroom Activity

Given the following organizations, identify the appropriate Runtime Environment:

1. Online Retail Company using only cloud SaaS applications.
2. Government Office with Oracle Database on-premises.
3. Hospital using SAP and local Electronic Medical Records (EMR).
4. University integrating Moodle Cloud with an internal Student Information System.

Discuss your reasoning.

---

# Discussion Questions

1. Why is a Runtime Environment essential in IICS?

2. Compare Hosted Agent and Secure Agent.

3. Which Runtime Environment would you recommend for a hybrid cloud enterprise? Justify your answer.

---

# Faculty Tips

Relate Runtime Environments to familiar concepts:

- A Runtime Environment is like the **engine** of a car.
- The cloud platform designs the workflow, but the Runtime Environment actually executes it.

This analogy helps students distinguish between design-time and run-time components.

---

# Interview Questions

1. What is a Runtime Environment?

2. Why is it required?

3. Differentiate Hosted Agent and Secure Agent.

4. Which Runtime Environment is suitable for hybrid cloud?

5. Can Hosted Agent connect directly to an on-premises Oracle Database? Explain.

---

# Examination Tips

Students should be able to:

- Define Runtime Environment.
- Draw the Runtime Environment architecture.
- Compare Hosted Agent and Secure Agent.
- Explain runtime selection with enterprise examples.

---

# Chapter Summary

In this chapter, students learned:

- Runtime Environment
- Hosted Agent
- Secure Agent
- Runtime Architecture
- Enterprise Deployment
- Runtime Selection
- Best Practices

Understanding Runtime Environments prepares students for the next chapter, which focuses on the Secure Agent—the core execution component of hybrid cloud integration.

---

# End of Chapter 7
# Chapter 8

# Informatica Cloud Secure Agent

## Part A – Overview, Architecture and Components

---

## Course Outcome

CO2

---

# Learning Objectives

After completing this chapter, students will be able to:

- Explain the purpose of the Secure Agent.
- Describe the Secure Agent Architecture.
- Identify Secure Agent components.
- Explain how Secure Agent communicates with Informatica Cloud.
- Describe the minimum system requirements.
- Understand Secure Agent deployment models.

---

# Introduction

Modern organizations store their data in multiple environments:

- Oracle Database
- SQL Server
- SAP
- Salesforce
- AWS
- Azure
- Flat Files
- REST APIs

Most enterprise databases remain inside the organization's private network.

Since Informatica Intelligent Cloud Services (IICS) is cloud-based, it cannot directly access these protected internal resources.

To bridge this gap, Informatica provides the **Secure Agent**.

The Secure Agent establishes a secure communication channel between Informatica Cloud and enterprise systems without exposing internal resources to the public Internet.

---

# What is Secure Agent?

A Secure Agent is a lightweight application installed inside the customer's network.

It performs all runtime activities required by Informatica Cloud.

The Secure Agent:

- Executes mappings
- Connects to databases
- Transfers data
- Runs synchronization jobs
- Executes APIs
- Performs transformations
- Sends execution status to Informatica Cloud

Think of the Secure Agent as the **execution engine** of Informatica Cloud.

---

# Why is Secure Agent Required?

Without Secure Agent:

❌ Informatica Cloud cannot access:

- Oracle Database
- SQL Server
- SAP
- File Systems
- Internal APIs

With Secure Agent:

✔ Secure communication is established.

✔ Data remains protected.

✔ Firewall rules remain simple.

✔ No inbound ports are required.

---

# Secure Agent Architecture

```
                     Informatica Cloud

                           │

                    HTTPS (TLS/SSL)

                           │

                 --------------------

                 Secure Communication

                 --------------------

                           │

                    Secure Agent

          ┌────────────┼────────────┐

      Database      Applications      Files

          │              │             │

     Oracle        Salesforce      CSV

     SQL Server    SAP             XML

     MySQL         REST APIs       JSON
```

---

# Communication Flow

Step 1

Administrator creates a mapping in Informatica Cloud.

↓

Step 2

The mapping task is submitted.

↓

Step 3

Secure Agent receives execution instructions.

↓

Step 4

Secure Agent connects to the source system.

↓

Step 5

Data is extracted.

↓

Step 6

Transformation logic executes.

↓

Step 7

Target system receives transformed data.

↓

Step 8

Execution status is sent back to Informatica Cloud.

---

# Major Components

The Secure Agent contains several services.

Major components include:

- Agent Core
- Data Integration Service
- Process Server
- Metadata Service
- Connector Services
- Secure Communication Module
- Log Manager

Each component performs a specialized task.

---

# Secure Agent Services

The Secure Agent automatically starts multiple background services.

Examples include:

- Data Integration Service
- Cloud Integration Service
- Process Engine
- API Runtime
- Metadata Processing
- Logging Service

These services work together to execute integration jobs.

---

# Secure Agent Deployment

Secure Agent may be installed on:

- Windows Desktop
- Windows Server
- Linux Server
- VMware Virtual Machine
- Hyper-V
- AWS EC2
- Microsoft Azure VM
- Google Cloud VM

---

# Minimum System Requirements

Typical requirements include:

### Operating System

- Windows 10
- Windows 11
- Windows Server
- Linux (supported distributions)

---

### Processor

64-bit CPU

Minimum Dual Core

Recommended Quad Core or higher

---

### Memory

Minimum:

8 GB RAM

Recommended:

16 GB RAM

Large enterprise workloads:

32 GB or more

---

### Disk Space

Minimum:

10 GB Free Space

Recommended:

25 GB+

---

### Java

Supported Java Runtime Environment

(as specified in the current Informatica documentation)

---

### Internet Connectivity

Reliable broadband connection

HTTPS access to Informatica Cloud endpoints

---

# Secure Agent Security

Secure Agent uses:

- TLS Encryption
- HTTPS Communication
- Authentication Tokens
- Secure Certificates

Sensitive information is encrypted during transmission.

---

# Advantages

✔ Easy installation

✔ Lightweight

✔ Secure communication

✔ Supports hybrid cloud

✔ Supports cloud and on-premises systems

✔ Automatic updates

✔ Enterprise scalability

---

# Limitations

- Requires local installation

- Depends on network availability

- Requires periodic monitoring

- Local resources affect performance

---

# Enterprise Example

ABC Bank stores customer records in Oracle Database.

Developers design mappings in Informatica Cloud.

The Secure Agent installed inside the bank's data center performs:

- Oracle connection
- Data extraction
- Data transformation
- Data loading
- Execution monitoring

No direct database exposure to the Internet is required.

---

# Best Practices

- Install Secure Agent on a dedicated server.

- Avoid installing on user desktops.

- Monitor CPU and memory usage.

- Keep the Secure Agent updated.

- Backup configuration regularly.

- Use separate Secure Agents for Development, Testing, and Production.

---

# Classroom Activity

Scenario:

A hospital stores patient data in:

- Oracle Database
- Laboratory Server
- PACS Imaging System

Question:

Why is Secure Agent required?

Which systems will it communicate with?

Draw the communication architecture.

---

# Discussion Question

Can Informatica Cloud directly connect to an Oracle Database inside a private network without Secure Agent?

Explain your answer.

---

# Faculty Tips

Explain Secure Agent using the analogy of a **trusted courier**.

- Informatica Cloud sends instructions.
- Secure Agent receives them.
- Secure Agent safely enters the organization's network.
- Secure Agent completes the assigned work.
- Results are securely returned.

This analogy helps students understand why Secure Agent is essential in hybrid cloud environments.

---

# Interview Questions

1. What is Secure Agent?

2. Why is Secure Agent required?

3. Explain Secure Agent Architecture.

4. Can multiple Secure Agents be deployed?

5. Where should Secure Agent be installed?

6. How does Secure Agent communicate securely?

---

# Examination Tips

Students should be able to:

- Define Secure Agent.
- Draw Secure Agent Architecture.
- Explain communication flow.
- List system requirements.
- Discuss advantages and limitations.
- Explain enterprise deployment scenarios.

---

# Chapter Summary

This section introduced:

- Secure Agent
- Secure Agent Architecture
- Communication Flow
- Components
- Deployment
- System Requirements
- Security Features
- Enterprise Applications

The next section explains the internal working of the Secure Agent, including Agent Manager, Agent Core, service startup, and execution lifecycle.

---

# End of Chapter 8 – Part A
# Chapter 8

# Informatica Cloud Secure Agent

## Part B – Agent Manager, Agent Core and Service Startup

---

## Learning Objectives

After completing this section, students will be able to:

- Explain the internal architecture of Secure Agent.
- Describe the responsibilities of Agent Manager.
- Explain the Agent Core component.
- Understand the Secure Agent startup sequence.
- Differentiate between Local User and Network User execution.
- Analyze Secure Agent performance.

---

# Internal Architecture

The Secure Agent consists of multiple services working together.

```
                Secure Agent

        ┌─────────────────────────┐
        │     Agent Manager       │
        └────────────┬────────────┘
                     │
        ┌────────────┴────────────┐
        │       Agent Core        │
        └────────────┬────────────┘
                     │
    ┌────────┬────────┬─────────┬─────────┐
    │        │        │         │         │
 Data     Process   API      Metadata   Log
Integration Server Runtime   Service   Manager
```

Each component has a dedicated responsibility, allowing the Secure Agent to execute integration jobs efficiently.

---

# Agent Manager

## What is Agent Manager?

The **Agent Manager** is the primary service responsible for controlling the Secure Agent.

It performs the following functions:

- Starts services
- Stops services
- Monitors health
- Downloads updates
- Communicates with Informatica Cloud
- Restarts failed services
- Collects logs

The Agent Manager acts as the supervisor of the Secure Agent.

---

## Responsibilities of Agent Manager

- Service lifecycle management
- Automatic updates
- Registration with Informatica Cloud
- Configuration management
- Health monitoring
- Failure recovery
- Status reporting

---

# Agent Core

## What is Agent Core?

The **Agent Core** is the execution engine of the Secure Agent.

It is responsible for:

- Executing mappings
- Managing runtime resources
- Loading connectors
- Scheduling tasks
- Executing workflows
- Monitoring execution

If Agent Manager is the "supervisor," Agent Core is the "worker" that performs the actual integration tasks.

---

# Responsibilities of Agent Core

- Execute integration jobs
- Load runtime services
- Connect to data sources
- Apply transformations
- Transfer data
- Handle exceptions
- Generate execution logs

---

# Secure Agent Service Startup

When the Secure Agent starts, several background services are initialized automatically.

Typical startup sequence:

1. Operating System starts the Secure Agent service.
2. Agent Manager initializes.
3. Configuration files are loaded.
4. Agent Core starts.
5. Runtime services are initialized.
6. Connectors are loaded.
7. Secure connection to Informatica Cloud is established.
8. Agent status is updated to **Running**.

Only after this sequence is complete can the Secure Agent execute jobs.

---

# Service Startup Routine

```
Operating System

↓

Secure Agent Service

↓

Agent Manager

↓

Configuration Loading

↓

Agent Core

↓

Connector Services

↓

Runtime Services

↓

Secure Cloud Connection

↓

Ready for Execution
```

---

# Secure Communication

The Secure Agent always initiates the connection to Informatica Cloud using outbound HTTPS communication.

Key points:

- No inbound firewall ports are required.
- Communication is encrypted using TLS.
- Authentication is performed using secure tokens.
- Configuration data is transmitted securely.

This design minimizes security risks while enabling hybrid cloud connectivity.

---

# Running Secure Agent as Local User

The Secure Agent can run using a **Local Windows User Account**.

### Advantages

- Easy to configure.
- Suitable for standalone installations.
- Minimal administrative overhead.

### Limitations

- Limited access to network resources.
- Cannot access some shared folders or network services without additional configuration.

### Recommended For

- Development environments
- Small organizations
- Personal testing

---

# Running Secure Agent as Network User

The Secure Agent can also run under a **Windows Domain (Network) User Account**.

### Advantages

- Access to network drives.
- Access to shared folders.
- Integration with Active Directory.
- Better enterprise authentication.

### Limitations

- Requires domain administration.
- Additional configuration is needed.

### Recommended For

- Production environments
- Enterprise deployments
- Hybrid cloud infrastructures

---

# Local User vs Network User

| Feature | Local User | Network User |
|---------|------------|--------------|
| Local File Access | ✔ | ✔ |
| Shared Folder Access | Limited | ✔ |
| Active Directory Integration | ✘ | ✔ |
| Enterprise Authentication | ✘ | ✔ |
| Production Ready | Limited | ✔ |

---

# Performance Considerations

Secure Agent performance depends on:

- CPU utilization
- Available memory
- Disk I/O
- Network bandwidth
- Number of concurrent jobs
- Data volume
- Connector performance

Administrators should monitor these factors regularly to maintain efficient execution.

---

# Monitoring Secure Agent

Administrators should monitor:

- Service status
- CPU usage
- Memory usage
- Job execution time
- Failed jobs
- Queue length
- Connector status
- Disk utilization

Regular monitoring helps detect performance issues before they affect business operations.

---

# Common Problems

Problem | Possible Cause
--------|----------------
Agent Offline | Network connectivity issue
Job Failure | Database connection error
High CPU Usage | Too many concurrent tasks
Slow Performance | Insufficient memory
Authentication Failure | Invalid credentials
Agent Not Starting | Configuration or service issue

---

# Enterprise Example

A manufacturing company installs a Secure Agent on a Windows Server joined to the corporate domain.

The Secure Agent runs under a domain service account, allowing it to:

- Access SQL Server
- Read files from shared network storage
- Connect to ERP systems
- Execute scheduled integrations

This configuration supports secure, centralized administration.

---

# Best Practices

- Run production agents using dedicated service accounts.
- Allocate sufficient CPU and RAM.
- Monitor services regularly.
- Review logs periodically.
- Separate Development, Testing, and Production environments.
- Keep Secure Agent updated.
- Document service account permissions.

---

# Classroom Activity

An enterprise has the following requirements:

- Access to SQL Server on the corporate network.
- Read files from a shared folder.
- Authenticate using Active Directory.

Questions:

1. Should the Secure Agent run as a Local User or Network User?
2. Explain your reasoning.
3. Identify any additional permissions that may be required.

---

# Discussion Questions

1. What is the difference between Agent Manager and Agent Core?
2. Why does the Secure Agent establish outbound connections instead of accepting inbound connections?
3. In what situations should a Network User account be preferred over a Local User account?

---

# Faculty Tips

A useful analogy:

- **Agent Manager** is the **factory manager** who oversees operations.
- **Agent Core** is the **production line** where the actual work is performed.
- **Connector Services** are the **workers** specialized for different tasks (database, file, API, etc.).

This analogy helps students understand how different Secure Agent components collaborate.

---

# Interview Questions

1. What is the role of Agent Manager?
2. What responsibilities are handled by Agent Core?
3. Describe the Secure Agent startup sequence.
4. Compare Local User and Network User execution.
5. What factors affect Secure Agent performance?

---

# Examination Tips

Students should be able to:

- Explain Agent Manager.
- Explain Agent Core.
- Draw the Secure Agent startup sequence.
- Compare Local User and Network User.
- Discuss performance considerations.

---

# Summary

In this section, students learned:

- Agent Manager
- Agent Core
- Service Startup
- Startup Routine
- Secure Communication
- Local User vs Network User
- Performance Monitoring
- Enterprise Deployment Best Practices

These concepts prepare students for the final section, where they will install and configure the Secure Agent on Windows and learn troubleshooting techniques.

---

# End of Chapter 8 – Part B
# Chapter 8

# Informatica Cloud Secure Agent

## Part C – Installation, Verification, Troubleshooting and Lab Activity

---

## Learning Objectives

After completing this section, students will be able to:

- Install Secure Agent on Windows.
- Register Secure Agent with Informatica Cloud.
- Verify a successful installation.
- Troubleshoot common installation issues.
- Maintain Secure Agent.
- Apply best practices for enterprise deployment.

---

# Installing Secure Agent on Windows

Secure Agent installation is straightforward and typically takes only a few minutes.

The installation consists of:

1. Download Secure Agent
2. Launch Installer
3. Authenticate with Informatica Cloud
4. Register the Agent
5. Verify Services
6. Execute Test Connection

---

# Pre-Installation Checklist

Before installation verify:

✓ Windows operating system is supported

✓ Administrator privileges available

✓ Stable Internet connection

✓ Minimum 8 GB RAM

✓ 10 GB Free Disk Space

✓ HTTPS Port (443) accessible

✓ Antivirus exclusions configured (if required)

✓ Proxy configuration available (if organization uses proxy)

---

# Installation Workflow

```
Download Secure Agent

↓

Run Installer

↓

Accept License Agreement

↓

Select Installation Directory

↓

Enter Informatica Credentials

↓

Register Secure Agent

↓

Download Components

↓

Start Services

↓

Verify Installation
```

---

# Step 1 – Download Secure Agent

Login to Informatica Intelligent Cloud Services.

Navigate to:

Administrator

↓

Runtime Environments

↓

Secure Agents

↓

Download Secure Agent

Select the Windows installer.

---

# Step 2 – Launch Installer

Double-click the installer.

The installation wizard starts.

Choose:

Next

↓

Accept License

↓

Installation Folder

↓

Next

---

# Step 3 – Login to Informatica Cloud

Enter

- Username
- Password
- Organization

The installer authenticates with Informatica Cloud.

---

# Step 4 – Register Secure Agent

The installer automatically registers the Secure Agent.

The organization now recognizes the new Runtime Environment.

---

# Step 5 – Download Runtime Components

After registration

Secure Agent downloads

- Runtime Engine
- Connectors
- Services
- Updates

The duration depends on Internet speed.

---

# Step 6 – Start Services

Windows starts

Agent Manager

↓

Agent Core

↓

Runtime Services

↓

Connector Services

↓

Monitoring Services

The Secure Agent status changes to:

Running

---

# Verifying Installation

Open Administrator Console.

Navigate to

Runtime Environments

↓

Secure Agent

Verify:

✔ Online Status

✔ Running

✔ Latest Version

✔ Services Healthy

---

# Secure Agent Directory Structure

Example

```
SecureAgent

│

├── apps

├── conf

├── logs

├── downloads

├── temp

├── updates

└── services
```

---

# Important Folders

### conf

Configuration files.

---

### logs

Execution logs.

---

### apps

Installed runtime applications.

---

### temp

Temporary files.

---

### updates

Automatic software updates.

---

# Secure Agent Logs

Logs are used for troubleshooting.

Typical information:

- Startup Events
- Login Status
- Job Execution
- Errors
- Warnings
- Connector Messages

Administrators should review logs regularly.

---

# Common Installation Errors

## Error 1

Secure Agent Offline

Possible Causes

- No Internet
- Firewall Blocking
- Proxy Configuration
- Authentication Failure

Resolution

- Verify Internet
- Check Firewall
- Verify Proxy
- Restart Agent

---

## Error 2

Registration Failed

Possible Causes

- Invalid Credentials
- Wrong Organization
- Expired Password

Resolution

- Verify Login
- Reset Password
- Confirm Organization Name

---

## Error 3

Service Failed to Start

Possible Causes

- Windows Service Error
- Antivirus Blocking
- Insufficient Permissions

Resolution

- Run as Administrator
- Check Windows Services
- Review Event Viewer

---

## Error 4

Database Connection Failure

Possible Causes

- Database Offline
- Incorrect Port
- Wrong Credentials
- Firewall

Resolution

- Verify Database
- Test Connection
- Validate Credentials

---

## Error 5

Low Performance

Possible Causes

- Low RAM
- High CPU
- Heavy Workload
- Large Data Volume

Resolution

- Increase RAM
- Optimize Jobs
- Separate Runtime Environments

---

# Troubleshooting Checklist

Whenever Secure Agent fails

Check:

✔ Internet

✔ Agent Status

✔ Windows Service

✔ Firewall

✔ Proxy

✔ Credentials

✔ Logs

✔ Runtime Version

✔ Available Memory

✔ CPU Usage

---

# Secure Agent Maintenance

Administrators should

- Review logs weekly
- Monitor CPU
- Monitor Memory
- Remove unnecessary files
- Install updates
- Backup configuration
- Review Runtime Health

---

# Enterprise Deployment Recommendation

Large organizations should maintain separate Secure Agents for:

Development

↓

Testing

↓

User Acceptance Testing

↓

Production

This reduces operational risks.

---

# Lab Activity 1

## Installing Secure Agent on Windows

### Objective

Install and verify Secure Agent.

---

### Requirements

- Windows Computer
- Internet
- Informatica Account
- Administrator Rights

---

### Procedure

Step 1

Login to Informatica Cloud.

Step 2

Download Secure Agent.

Step 3

Run Installer.

Step 4

Register Agent.

Step 5

Verify Runtime.

Step 6

Capture Screenshots.

Step 7

Submit Installation Report.

---

### Expected Outcome

Students should observe

✔ Secure Agent Running

✔ Runtime Online

✔ Successful Registration

---

# Lab Activity 2

## Create Runtime Environment

Students should

- Identify Runtime
- Verify Status
- Explain Components
- Describe Communication Flow

---

# Classroom Discussion

A company reports that all integration jobs have stopped.

Discuss:

- What should the administrator verify first?
- Which logs should be reviewed?
- Which services are involved?

---

# Best Practices

✔ Install on dedicated server

✔ Use SSD storage

✔ Allocate sufficient RAM

✔ Use Network Service Account

✔ Separate environments

✔ Enable monitoring

✔ Maintain backups

✔ Keep software updated

---

# Security Best Practices

- Never share administrator credentials.
- Restrict Secure Agent server access.
- Monitor audit logs.
- Apply operating system security patches.
- Follow Principle of Least Privilege.
- Regularly rotate service account passwords.

---

# Faculty Tips

During demonstration,

explain

```
Design

↓

Runtime

↓

Execution

↓

Monitoring
```

Students often confuse designing mappings with executing mappings.

Emphasize that **Secure Agent performs execution**, not design.

---

# Interview Questions

1. What is Secure Agent?

2. Explain Secure Agent Architecture.

3. Describe Agent Manager.

4. Explain Agent Core.

5. How is Secure Agent installed?

6. How do you verify installation?

7. Where are Secure Agent logs stored?

8. Explain Runtime Environment.

9. What causes Secure Agent to go Offline?

10. How would you troubleshoot installation failures?

---

# Examination Tips

Students should be able to

- Draw Secure Agent Architecture.
- Explain installation steps.
- Explain startup sequence.
- Discuss troubleshooting.
- Compare Local User and Network User.
- Explain enterprise deployment.

---

# Chapter Summary

This chapter covered

- Secure Agent Overview
- Architecture
- Components
- Agent Manager
- Agent Core
- Runtime Services
- Startup Routine
- Local User
- Network User
- Installation
- Verification
- Logs
- Troubleshooting
- Maintenance
- Best Practices
- Lab Activities

The Secure Agent is the core execution component of Informatica Intelligent Cloud Services, enabling secure communication between cloud services and enterprise resources while supporting reliable, scalable, and secure data integration.

---

# End of Chapter 8
# Chapter 9

# Guided Classroom Activities and Demonstrations

---

## Course Outcome

CO2

---

# Purpose

This chapter provides instructor-guided demonstrations and classroom activities that reinforce the concepts of User Management and Secure Agent administration. These activities are designed for a theory course and can be conducted as instructor-led demonstrations, guided discussions, or simulated hands-on exercises.

---

# Activity 1

# Create a User with Native Authentication

## Learning Objective

Students will understand how a user is created using Informatica's built-in authentication mechanism.

---

## Prerequisites

- Access to Informatica Intelligent Cloud Services (IICS)
- Organization Administrator privileges

---

## Demonstration Steps

1. Log in to the IICS Administrator Console.
2. Navigate to **Administrator → Users**.
3. Click **New User**.
4. Enter:
   - User Name
   - Email Address
   - Authentication Type: Native
5. Assign an appropriate role.
6. Assign a license.
7. Save the configuration.
8. Explain the generated activation process.

---

## Classroom Discussion

Discuss:

- When should Native Authentication be used?
- What are its advantages and limitations?
- Is it suitable for large enterprises?

---

## Expected Learning Outcome

Students should be able to:

- Explain Native Authentication.
- Identify scenarios where it is appropriate.
- Describe the user creation process.

---

# Activity 2

# Create a User with Salesforce Authentication

---

## Learning Objective

Students will understand Single Sign-On (SSO) integration using Salesforce Authentication.

---

## Demonstration Steps

1. Open **Administrator → Users**.
2. Select **Create User**.
3. Choose **Salesforce Authentication**.
4. Enter user details.
5. Assign the required role.
6. Save the configuration.
7. Explain how authentication is delegated to Salesforce.

---

## Comparison Activity

Ask students to compare:

| Native Authentication | Salesforce Authentication |
|-----------------------|---------------------------|
| Credentials stored in IICS | Credentials managed by Salesforce |
| Separate login | Single Sign-On |
| Easier setup | Better enterprise integration |
| Suitable for small organizations | Suitable for large enterprises |

---

## Discussion Questions

- Why do enterprises prefer SSO?
- What are the security benefits of centralized authentication?

---

# Activity 3

# Secure Agent Installation Demonstration

---

## Learning Objective

Students will observe the installation and registration of a Secure Agent.

---

## Demonstration Requirements

- Windows machine (or virtual machine)
- Internet connection
- Informatica Cloud account
- Administrator privileges

---

## Demonstration Workflow

1. Download Secure Agent.
2. Launch the installer.
3. Accept the license agreement.
4. Enter Informatica Cloud credentials.
5. Register the Secure Agent.
6. Allow runtime components to download.
7. Verify that the agent status changes to **Running**.

---

## Instructor Explanation

During the demonstration, explain:

- Runtime Environment
- Agent Manager
- Agent Core
- Connector Services
- Secure communication with Informatica Cloud

---

# Activity 4

# Runtime Environment Analysis

---

## Scenario

An organization has:

- Oracle Database
- Salesforce
- SAP ERP
- Local File Server

Students should identify:

1. Which Runtime Environment should be used?
2. Why is Secure Agent required?
3. Where should the Secure Agent be installed?

---

## Expected Answer

Students should recommend:

- Secure Agent
- Installation inside the organization's private network
- Communication using secure outbound HTTPS

---

# Activity 5

# User Role Assignment Exercise

---

## Scenario

Assign appropriate roles for:

- Organization Administrator
- Data Engineer
- Business Analyst
- Auditor
- Operator

Students should justify each role assignment based on responsibilities.

---

# Activity 6

# Group Discussion

## Topic

"How do User Groups and User Roles improve security in enterprise cloud environments?"

Students should discuss:

- Administrative efficiency
- Role-Based Access Control (RBAC)
- Principle of Least Privilege
- Scalability

---

# Activity 7

# Case Study

## XYZ Healthcare

A healthcare organization operates hospitals in:

- Bangalore
- Chennai
- Hyderabad

Requirements:

- Separate administrators for each hospital.
- Shared central governance.
- Secure access to patient records.
- Hybrid cloud integration.

### Questions

1. Design the organization hierarchy.
2. Recommend User Groups.
3. Assign User Roles.
4. Select the appropriate Runtime Environment.
5. Explain why Secure Agent is necessary.

---

# Activity 8

# Classroom Quiz

Suggested topics:

- Organization Hierarchy
- Sub-Organizations
- User Management
- User Statistics
- User Groups
- User Roles
- Runtime Environment
- Secure Agent

Recommended format:

- 20 MCQs
- 5 Scenario-based questions
- 2 Discussion questions

---

# Faculty Notes

Throughout these activities:

- Encourage students to relate concepts to enterprise environments.
- Use architecture diagrams wherever possible.
- Compare IICS with familiar platforms such as Google Workspace or Microsoft 365.
- Reinforce the relationship between Users, Groups, Roles, Runtime Environments, and Secure Agents.

---

# Learning Outcomes

After completing these guided activities, students will be able to:

- Create and manage users.
- Explain authentication methods.
- Organize users using groups and roles.
- Recommend suitable Runtime Environments.
- Explain Secure Agent architecture.
- Describe Secure Agent installation and verification.
- Analyze enterprise administration scenarios.

---

# End of Chapter 9
# Chapter 10

# Unit Summary, Revision and Examination Preparation

---

## Course Outcome

**CO2:** Demonstrate the configuration of IICS Sub-organizations, User Management, and Secure Agent Installation, and analyze their impact on data integration processes.

---

# Unit Overview

This unit introduced the administrative capabilities of Informatica Intelligent Cloud Services (IICS). Students learned how organizations manage users, security, runtime environments, and execution infrastructure.

The unit progressed from organizational administration to runtime execution, providing the foundation required for subsequent units on integration development and administration.

---

# Unit Concept Map

```
IICS Administration

│

├── Organization Hierarchy

│      └── Sub-Organizations

│

├── User Management

│      ├── Authentication

│      ├── Users

│      ├── User Groups

│      ├── User Roles

│      └── User Statistics

│

├── Runtime Environment

│      ├── Hosted Agent

│      └── Secure Agent

│

└── Secure Agent

       ├── Agent Manager

       ├── Agent Core

       ├── Services

       ├── Installation

       ├── Monitoring

       └── Troubleshooting
```

---

# Key Concepts

Students should clearly understand the following concepts:

- Organization
- Sub-Organization
- Organization Hierarchy
- User Management
- Native Authentication
- Salesforce Authentication
- User Statistics
- User Groups
- User Roles
- Role-Based Access Control (RBAC)
- Runtime Environment
- Hosted Agent
- Secure Agent
- Agent Manager
- Agent Core
- Runtime Services
- Secure Communication

---

# Important Definitions

### Organization

The highest administrative entity within IICS used to manage users, assets, licenses, and runtime environments.

---

### Sub-Organization

A child administrative unit created under an organization to simplify administration and improve governance.

---

### User Group

A logical collection of users used to simplify administration.

---

### User Role

A predefined or custom set of permissions assigned to users or groups.

---

### Runtime Environment

The execution platform where integration tasks are processed.

---

### Secure Agent

A lightweight runtime application installed within an organization's network that securely executes IICS tasks.

---

### Agent Manager

The service responsible for controlling, monitoring, and maintaining Secure Agent services.

---

### Agent Core

The component responsible for executing integration jobs and managing runtime operations.

---

# Chapter-wise Recap

## Chapter 1

- Organization Architecture
- Administrative hierarchy
- Enterprise structure

---

## Chapter 2

- Sub-Organizations
- Parent-child hierarchy
- License allocation

---

## Chapter 3

- User Management
- Authentication
- User creation
- User administration

---

## Chapter 4

- User Statistics
- List View
- Chart View
- Monitoring

---

## Chapter 5

- User Groups
- Group administration
- Enterprise grouping

---

## Chapter 6

- User Roles
- RBAC
- System-defined roles
- Custom roles

---

## Chapter 7

- Runtime Environment
- Hosted Agent
- Secure Agent
- Runtime architecture

---

## Chapter 8

- Secure Agent
- Agent Manager
- Agent Core
- Startup sequence
- Installation
- Troubleshooting

---

## Chapter 9

- Guided demonstrations
- Authentication
- Runtime verification
- Enterprise scenarios

---

# Frequently Asked University Questions

## 2-Mark Questions

1. Define Sub-Organization.
2. What is Native Authentication?
3. What is a User Group?
4. Define Runtime Environment.
5. What is Secure Agent?
6. What is Agent Core?

---

## 5-Mark Questions

1. Explain User Management.
2. Differentiate User Groups and User Roles.
3. Explain Runtime Environment.
4. Describe Secure Agent Architecture.
5. Explain Hosted Agent vs Secure Agent.

---

## 10-Mark Questions

1. Explain Organization Hierarchy with a suitable diagram.
2. Describe User Management in IICS.
3. Explain Secure Agent Architecture and Components.
4. Explain Secure Agent Installation.
5. Discuss Runtime Environments with enterprise examples.

---

## 15-Mark Questions

1. Explain the complete User Administration process in IICS.
2. Discuss Secure Agent Architecture, installation, monitoring, and troubleshooting.
3. Explain the importance of Runtime Environments in enterprise cloud integration.
4. Explain RBAC and User Role management with examples.

---

# Frequently Asked Interview Questions

1. Why are Sub-Organizations required?
2. What is RBAC?
3. Explain User Groups.
4. Explain Hosted Agent.
5. Explain Secure Agent.
6. What is Agent Manager?
7. What is Agent Core?
8. Why is Secure Agent required?
9. Explain Runtime Environment.
10. How would you troubleshoot an Offline Secure Agent?

---

# Common Misconceptions

| Misconception | Correct Understanding |
|--------------|-----------------------|
| Organization and Sub-Organization are identical. | A Sub-Organization is a child administrative unit. |
| User Groups define permissions. | User Groups organize users; Roles define permissions. |
| Hosted Agent can access on-premises databases directly. | Secure Agent is required for on-premises connectivity. |
| Secure Agent stores enterprise data permanently. | It executes tasks and securely transfers data. |
| Every user should receive Administrator privileges. | Apply the Principle of Least Privilege. |

---

# Faculty Teaching Checklist

Before completing Unit 2, verify that students can:

- Explain Organization Hierarchy.
- Create Sub-Organizations.
- Describe User Authentication methods.
- Create and manage Users.
- Explain User Groups and Roles.
- Compare Hosted Agent and Secure Agent.
- Describe Secure Agent Architecture.
- Explain installation and verification steps.
- Identify common troubleshooting techniques.

---

# Student Revision Checklist

Before the examination, students should be able to:

- Define all key terms.
- Draw Organization Hierarchy.
- Explain RBAC.
- Compare User Groups and Roles.
- Compare Hosted Agent and Secure Agent.
- Draw Secure Agent Architecture.
- Explain Secure Agent startup sequence.
- Describe installation steps.
- Explain troubleshooting methods.

---

# Course Outcome Achievement

| Skill | CO2 Mapping |
|-------|-------------|
| Organization Administration | ✓ |
| User Management | ✓ |
| Authentication | ✓ |
| User Groups | ✓ |
| User Roles | ✓ |
| Runtime Environment | ✓ |
| Secure Agent | ✓ |
| Installation | ✓ |
| Troubleshooting | ✓ |

---

# End of Unit Summary

This unit established the administrative and runtime foundation of Informatica Intelligent Cloud Services (IICS). Students are now prepared to explore data integration development, asset management, and advanced platform capabilities in the subsequent units.

---

# End of Faculty Notes – Unit 2