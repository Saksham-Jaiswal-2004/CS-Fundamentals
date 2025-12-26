Database Management Systems (DBMS)

Overview

This section covers how data is modeled, stored, queried, optimized, and recovered. Content balances theory with practical SQL and system-level behavior so you can design schemas, write performant queries, and understand database internals.

Table of Contents

- Overview
- Topics Covered
- Folder Structure (Planned)
- Learning Outcomes
- How to Use

Topics Covered

- Database fundamentals and terminology
- ER modeling and schema design (entities, relationships, keys)
- Relational model and constraints
- SQL (DDL, DML, joins, subqueries, views)
- Normalization (1NF–BCNF) and denormalization trade-offs
- Indexing (B+ trees, hash, composite, covering)
- Transactions and ACID properties
- Concurrency control (locks, MVCC, isolation levels)
- Deadlocks and avoidance
- Recovery and logging (WAL, checkpoints)

Folder Structure (Planned)

- [Introduction](Introduction.md)
- [ER Model](ER-Model.md)
- [Relational Model](Relational-Model.md)
- [SQL](SQL.md)
- [Normalization](Normalization.md)
- [Indexing](Indexing.md)
- [Transactions](Transactions.md)
- [Concurrency Control](Concurrency-Control.md)
- [Recovery](Recovery.md)

Learning Outcomes

- Design normalized schemas with appropriate constraints and indexes
- Write correct, performant SQL and reason about execution plans
- Understand concurrency, isolation, and failure recovery mechanisms

How to Use

- Start with data modeling; evolve designs with normalization best practices
- Profile queries and experiment with indexes on realistic data sets
- Vary isolation levels to observe anomalies and trade-offs