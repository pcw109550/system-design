# How to start with distributed systems

> [System Design Primer ⭐️: How to start with distributed systems?](https://www.youtube.com/watch?v=SqcXvc3ZmRU&ab_channel=GauravSen)

## How do you handle orders? 

1. Vertical Scaling
    -  Optimize processes and increase throughput with the same resources

2. Preprocessing using cron jobs
    - Preparing beforehand at non-peak hours

3. Backup servers
    - Keep backups and avoid single point of failure

4. Horizontal Scaling
    - Hire more resources

5. Microservices
    - Divide responsibilities
    - Specialize each components

6. Distributed System
    - Able to route orders depending on requests
    - Partitioning

7. Load balancing
    - Routing depending on components and requests

8. Decoupling
    - Separation of responsibilities by separating concerns to be more efficient

9. Logging and metrics calculation
    - Analytics
    - Auditing
    - Reporting
    - Machine Learning

10. Extensibility
    - Easily scale out by decoupling everything


## High Level Design

How multiple systems interact. Focused on upper ten concepts.

1. Order overload
    - Recruitment
2. Complexity
    - Separation of Concerns
3. Mishaps
    - Fault tolerance


## Low Level Design

Lot more to do with coding: making functions/classes/signatures