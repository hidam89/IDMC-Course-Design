# UNIT 4

# Student Notes

## REST API Administration and Troubleshooting

---

# Course Outcome (CO4)

Apply Informatica Intelligent Data Management Cloud (IDMC) REST APIs for administrative automation, retrieve and manage organizational resources, analyze log files, troubleshoot integration issues, and utilize monitoring resources to maintain enterprise cloud integration environments.

---

# Introduction

Modern enterprise cloud applications continuously exchange information with other applications. Instead of manually performing administrative tasks, organizations use **REST APIs** to automate administration, monitoring, and reporting.

This unit introduces REST APIs in Informatica Intelligent Data Management Cloud (IDMC), explains how administrators retrieve platform information using APIs, and demonstrates how troubleshooting is performed using log files and platform monitoring resources.

After completing this unit, students will understand both **API-based administration** and **enterprise troubleshooting techniques**.

---

# Chapter 1

# REST API Fundamentals

---

# Learning Objectives

After completing this chapter, you should be able to:

- Define REST API.
- Explain REST architecture.
- Describe REST principles.
- Explain HTTP methods.
- Identify the advantages of Informatica REST APIs.

---

# What is an API?

An **Application Programming Interface (API)** is a communication interface that allows one software application to exchange information with another.

Example:

```
Mobile App

↓

REST API

↓

IDMC Platform

↓

Response
```

---

# What is REST?

REST stands for **Representational State Transfer**.

It is an architectural style used to build web services.

REST APIs use:

- HTTP
- HTTPS
- JSON
- XML

REST APIs are:

- Lightweight
- Scalable
- Platform Independent
- Stateless

---

# REST Architecture

```
Client

↓

HTTP Request

↓

REST API

↓

IDMC Resources

↓

JSON Response
```

---

# REST Principles

REST follows several principles:

### Client–Server

The client sends requests.

The server processes requests.

---

### Stateless

Each request is independent.

No previous request information is stored by the server.

---

### Resource-Based

Everything is treated as a resource.

Examples:

- Users
- Runtime Environments
- Organizations
- Schedules

---

### Uniform Interface

REST uses standard HTTP methods.

---

# HTTP Methods

| Method | Purpose |
|---------|---------|
| GET | Retrieve |
| POST | Create |
| PUT | Replace |
| PATCH | Update |
| DELETE | Remove |

---

# HTTP Status Codes

| Code | Meaning |
|------|---------|
| 200 | Success |
| 201 | Created |
| 400 | Bad Request |
| 401 | Unauthorized |
| 404 | Not Found |
| 500 | Server Error |

---

# Advantages of Informatica REST APIs

- Automation
- Easy integration
- Faster administration
- Improved monitoring
- Reduced manual effort
- Enterprise scalability

---

# Enterprise Example

Instead of manually checking Runtime Environment status every morning, an organization uses a Python script that calls the Runtime API every 15 minutes and sends alerts if a runtime becomes unavailable.

---

# Important Points

✔ REST uses HTTP.

✔ REST is stateless.

✔ JSON is the preferred response format.

✔ REST APIs automate administration.

---

# Examination Questions

### 2 Marks

1. Define REST API.
2. What is REST?
3. Name any two HTTP methods.

---

### 5 Marks

Explain REST architecture and its advantages.

---

### 10 Marks

Explain REST APIs, REST principles, HTTP methods, and the advantages of Informatica REST APIs with suitable examples.

---

# Quick Revision

| Remember |
|-----------|
| REST = Representational State Transfer |
| Stateless communication |
| Uses HTTP/HTTPS |
| JSON response |
| Platform APIs automate administration |

---

# End of Chapter 1