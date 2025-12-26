System Design

Overview

System design is about building scalable, reliable, and maintainable software systems. This section emphasizes engineering trade-offs, performance characteristics, and practical decision-making for real-world architectures and interviews.

Table of Contents

- Overview
- Topics Covered
- Folder Structure (Planned)
- Learning Outcomes
- How to Use

Topics Covered

- System design fundamentals and design process
- Scalability (vertical vs horizontal, partitioning, replication)
- Latency vs throughput and tail latency
- Load balancing strategies (L4/L7, sticky sessions, health checks)
- Caching (client, CDN, reverse proxy, application, database)
- Databases (SQL vs NoSQL, sharding, replication, consistency)
- CAP theorem and PACELC intuition
- Consistency models (strong, eventual, causal, read-your-writes)
- Messaging and queues (at-most/at-least/exactly-once semantics)
- Case studies and back-of-the-envelope calculations

Folder Structure (Planned)

- [Introduction](Introduction.md)
- [Scalability](Scalability.md)
- [Load Balancing](Load-Balancing.md)
- [Caching](Caching.md)
- [Databases](Databases.md)
- [CAP Theorem](CAP-Theorem.md)
- [Consistency Models](Consistency.md)
- [Message Queues](Message-Queues.md)
- [Case Studies](Case-Studies.md)

Learning Outcomes

- Design architectures that scale and remain reliable under load
- Make informed trade-offs among latency, throughput, and consistency
- Communicate designs clearly for interviews and reviews

How to Use

- Start with fundamentals, then study one topic at a time
- Practice deriving requirements, constraints, and back-of-the-envelope estimates
- Sketch high-level designs; identify bottlenecks and apply appropriate patterns