# UNIT 3

# Faculty Notes

## Secure Agent Management, Performance Tuning, Asset Management and Monitoring

---

# Course Outcome (CO3)

Configure Secure Agent Groups, Runtime Services, Connections, Asset Management, Scheduling, Performance Optimization, and Monitoring capabilities in Informatica Intelligent Data Management Cloud (IDMC).

---

# Session 1

# Secure Agent Groups

Duration: 2 Hours

---

# Learning Objectives

After this session students should be able to:

- Explain Secure Agent Groups.
- Describe benefits of grouping multiple agents.
- View object dependencies.
- Enable and disable Secure Agent components.
- Explain enterprise deployment scenarios.

---

# Introduction

As enterprise environments grow, a single Secure Agent becomes insufficient to handle increasing workloads.

Organizations often deploy multiple Secure Agents across different locations or departments.

Managing them individually becomes complex.

To simplify administration, IDMC provides **Secure Agent Groups**, allowing multiple Secure Agents to work together as a logical unit.

---

# What is a Secure Agent Group?

A Secure Agent Group is a logical collection of multiple Secure Agents.

Instead of assigning jobs to an individual agent, administrators assign jobs to the group.

The runtime automatically selects an available agent.

---

# Why Secure Agent Groups?

Without Agent Groups:

- Single point of failure
- Uneven workload
- Poor scalability
- Difficult maintenance

With Agent Groups:

- Load balancing
- High availability
- Simplified administration
- Fault tolerance
- Better resource utilization

---

# Architecture

```

Cloud Data Integration

↓

Secure Agent Group

├── Agent 1

├── Agent 2

├── Agent 3

└── Agent 4

↓

Enterprise Resources

Oracle

SAP

SQL Server

REST APIs

```

---

# Benefits of Grouping Multiple Agents

## 1. High Availability

If one Secure Agent becomes unavailable, another agent in the group continues processing jobs.

---

## 2. Load Balancing

Jobs are distributed among multiple agents, reducing processing delays.

---

## 3. Improved Performance

Parallel execution enables faster processing of integration tasks.

---

## 4. Fault Tolerance

Agent failures do not interrupt business operations.

---

## 5. Scalability

Additional Secure Agents can be added without redesigning the architecture.

---

# Enterprise Example

ABC Bank operates in:

- Bangalore
- Mumbai
- Delhi
- Hyderabad

Instead of deploying one Secure Agent, each data center hosts a Secure Agent.

All four agents are combined into a Secure Agent Group.

Benefits:

- Automatic workload distribution
- Reduced downtime
- Increased availability

---

# Object Dependencies

Many assets depend upon other assets.

Examples include:

Mapping

↓

Connection

↓

Runtime Environment

↓

Secure Agent Group

When moving assets between environments, dependencies must also be transferred.

---

# Enable and Disable Components

Administrators can enable or disable components for:

- Maintenance
- Upgrades
- Troubleshooting
- Resource optimization

Typical components include:

- Data Integration
- Application Integration
- Process Server
- Metadata Service

---

# Demonstration

Demonstrate:

1. Open Administrator Console.
2. Navigate to Runtime Environments.
3. Create Secure Agent Group.
4. Add Secure Agents.
5. Verify Agent Status.
6. View Dependencies.

---

# Teaching Tips

Discuss:

"What happens if one Secure Agent fails during execution?"

Lead students toward concepts such as:

- High Availability
- Automatic Failover
- Load Balancing

---

# Classroom Discussion

Should every organization deploy multiple Secure Agents?

Discuss scenarios involving:

- Small organizations
- Large enterprises
- Hybrid cloud

---

# Lab Activity

Create a Secure Agent Group.

Add two Secure Agents.

Observe runtime selection.

Record observations.

---

# Interview Questions

1. What is a Secure Agent Group?

2. Why is load balancing important?

3. Explain High Availability.

4. How are jobs distributed?

5. What are Object Dependencies?

---

# Examination Questions

### 2 Marks

Define Secure Agent Group.

---

### 5 Marks

Explain benefits of Agent Groups.

---

### 10 Marks

Discuss Secure Agent Groups with suitable architecture and enterprise examples.

---

# Key Points

✔ Logical collection of Secure Agents

✔ Supports High Availability

✔ Supports Load Balancing

✔ Improves Scalability

✔ Simplifies Administration

---

# Summary

In this session students learned:

- Secure Agent Groups
- Benefits
- Architecture
- Object Dependencies
- Component Management
- Enterprise Deployment

---

# End of Session 1
# Session 2

# Working with Secure Agent

**Duration:** 2 Hours

---

# Learning Objectives

After completing this session, students will be able to:

- View Secure Agent details.
- Interpret Secure Agent statuses.
- Explain Secure Agent services.
- Configure upgrade settings.
- Monitor Secure Agent health.
- Apply best practices for enterprise administration.

---

# Introduction

Once a Secure Agent is installed, administrators must continuously monitor and maintain it to ensure reliable execution of integration jobs.

IDMC provides several administrative features to:

- Monitor Secure Agent health
- View runtime details
- Manage services
- Configure automatic upgrades
- Troubleshoot operational issues

Understanding these features helps administrators maintain a stable and secure integration environment.

---

# Viewing Secure Agent Details

Administrators can view detailed information about every Secure Agent from the **Administrator Console**.

Typical information includes:

- Agent Name
- Agent Group
- Runtime Environment
- Operating System
- Agent Version
- Installed Services
- Status
- Last Communication Time
- Upgrade Status

---

# How to View Secure Agent Details

1. Log in to IDMC.
2. Open **Administrator**.
3. Select **Runtime Environments**.
4. Choose the required Secure Agent.
5. Review the details displayed.

---

# Information Available

| Property | Description |
|-----------|-------------|
| Agent Name | Name of the Secure Agent |
| Version | Installed Secure Agent version |
| Status | Current operational state |
| Services | Installed runtime services |
| Runtime Environment | Assigned runtime |
| Last Communication | Last successful connection with IDMC |
| Upgrade Status | Current software version status |

---

# Secure Agent Statuses

The status indicates the operational condition of a Secure Agent.

Common statuses include:

### Running

- Agent is online.
- Ready to execute jobs.
- All required services are active.

---

### Starting

- Agent services are initializing.
- Temporary status after startup.

---

### Stopping

- Agent is shutting down.
- Running jobs may complete before termination.

---

### Stopped

- Agent services are not running.
- Jobs cannot execute.

---

### Offline

- Agent cannot communicate with IDMC.
- Possible network or system issue.

---

### Upgrading

- New version is being installed.
- Administrative actions may be temporarily unavailable.

---

# Status Lifecycle

```
Installed

↓

Starting

↓

Running

↓

Stopping

↓

Stopped

↓

Restart

↓

Running
```

---

# Secure Agent Services

A Secure Agent consists of multiple services working together.

Common services include:

- Data Integration Service
- Application Integration Service
- Process Server
- Metadata Service
- Connector Services
- Logging Service

Each service performs a specialized function.

---

# Service Responsibilities

| Service | Purpose |
|----------|---------|
| Data Integration | Executes mappings and synchronization tasks |
| Application Integration | Supports API and application workflows |
| Process Server | Executes process-based integrations |
| Metadata Service | Manages metadata communication |
| Connector Services | Connect to external systems |
| Logging Service | Stores execution logs |

---

# Service Health Monitoring

Administrators should regularly verify:

- Service status
- CPU utilization
- Memory usage
- Network connectivity
- Error logs
- Failed jobs

Monitoring these metrics helps detect issues before they affect production workloads.

---

# Upgrade Settings

Secure Agent supports software upgrades to provide:

- New features
- Security updates
- Bug fixes
- Performance improvements

Upgrade settings determine how these updates are applied.

---

# Upgrade Options

### Automatic Upgrade

- New versions are installed automatically.
- Recommended for development environments.

### Manual Upgrade

- Administrator controls upgrade timing.
- Preferred for production environments.

---

# Upgrade Best Practices

- Review release notes before upgrading.
- Perform upgrades during maintenance windows.
- Backup important configurations.
- Verify services after the upgrade.
- Test critical integration jobs.

---

# Enterprise Example

A financial institution operates Secure Agents in production.

To avoid business disruption:

- Automatic upgrades are disabled.
- Upgrades are tested in a staging environment.
- Production agents are upgraded only after successful validation.

This approach minimizes operational risk.

---

# Demonstration

Demonstrate the following:

1. Open Administrator Console.
2. Navigate to Runtime Environments.
3. Select a Secure Agent.
4. View agent properties.
5. Observe current status.
6. Review installed services.
7. Check upgrade settings.

---

# Troubleshooting Examples

| Problem | Possible Cause | Suggested Action |
|----------|----------------|------------------|
| Agent Offline | Network issue | Verify internet and firewall |
| Service Failed | Service crash | Restart Secure Agent service |
| Upgrade Failed | Interrupted download | Retry upgrade after checking connectivity |
| Jobs Not Running | Data Integration Service stopped | Restart the service |
| Frequent Disconnects | Unstable network | Verify network configuration |

---

# Teaching Tips

Ask students:

> "Why should production Secure Agents generally use manual upgrades instead of automatic upgrades?"

Encourage discussion around:

- Business continuity
- Change management
- Downtime planning
- Risk mitigation

---

# Classroom Discussion

Discuss the advantages and disadvantages of:

- Automatic upgrades
- Manual upgrades

Which approach is more appropriate for:

- Development environments?
- Testing environments?
- Production environments?

---

# Lab Activity

1. Open the Runtime Environment page.
2. View Secure Agent details.
3. Identify the status of each Secure Agent.
4. Review installed services.
5. Check upgrade settings.
6. Record observations.

---

# Interview Questions

1. What information is available in Secure Agent Details?
2. Explain different Secure Agent statuses.
3. What is the purpose of Data Integration Service?
4. Why are Secure Agent services monitored?
5. When should manual upgrades be preferred?

---

# Examination Questions

### 2 Marks

1. Define Secure Agent Status.
2. What is the purpose of Upgrade Settings?

---

### 5 Marks

1. Explain Secure Agent Services.
2. Differentiate Automatic and Manual Upgrades.

---

### 10 Marks

Explain the Secure Agent administration process, including agent details, statuses, services, upgrade settings, and troubleshooting.

---

# Key Points

✔ Secure Agent Details provide runtime information.

✔ Status indicates operational health.

✔ Multiple services work together to execute jobs.

✔ Upgrades improve functionality and security.

✔ Production upgrades should follow proper change management.

---

# Summary

In this session, students learned:

- Viewing Secure Agent Details
- Secure Agent Statuses
- Secure Agent Services
- Upgrade Settings
- Service Monitoring
- Enterprise Best Practices
- Troubleshooting

These concepts enable administrators to manage Secure Agents effectively and maintain reliable enterprise integration environments.

---

# End of Session 2