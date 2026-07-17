# Apache JMeter

> Simulating realistic workloads to evaluate application performance, reliability, and scalability.

---

# Overview

Apache JMeter is an open-source performance testing tool used to simulate user activity and measure how applications behave under different workloads.

I use JMeter to assess system responsiveness, identify bottlenecks, and support performance optimisation before software is released.

---

# Performance Testing Types

Using JMeter, I perform different types of performance testing depending on project objectives.

## Load Testing

Evaluates how an application performs under expected user traffic.

Typical objectives include:

- Measuring response time
- Validating throughput
- Monitoring resource utilisation
- Detecting bottlenecks

---

## Stress Testing

Pushes an application beyond its expected operating capacity to determine its breaking point and evaluate recovery behaviour.

---

## Spike Testing

Simulates sudden increases and decreases in user traffic to observe how the application responds to unexpected workload changes.

---

## Endurance Testing

Runs the application under sustained load over an extended period to identify memory leaks, resource exhaustion, or performance degradation.

---

# Typical JMeter Components

My performance test plans commonly include:

- Thread Groups
- HTTP Request Samplers
- CSV Data Set Config
- Assertions
- Timers
- Listeners
- Variables
- Controllers

---

# Typical Workflow

A typical performance testing workflow includes:

1. Define performance objectives.
2. Design realistic user scenarios.
3. Configure test data.
4. Execute performance tests.
5. Monitor application behaviour.
6. Analyse reports.
7. Share findings with stakeholders.

---

# Reporting

Typical reports include:

- Average Response Time
- Median Response Time
- 90th / 95th Percentile
- Throughput
- Error Percentage
- Active Users
- Requests per Second

---

# Business Value

Performance testing helps teams:

- Improve scalability
- Detect bottlenecks early
- Increase release confidence
- Enhance user experience
- Reduce production performance issues

---

> **"Reliable software should perform well not only under normal conditions, but also under pressure."**