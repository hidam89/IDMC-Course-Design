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