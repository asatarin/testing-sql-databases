# Testing SQL Databases

## TO READ 
* [Massive Stochastic Testing of SQL](https://www.vldb.org/conf/1998/p618.pdf)
  * https://twitter.com/MarkCallaghanDB/status/1601313113982533633
* [Testing Database Engines via Query Plan Guidance](http://jinshengba.me/assets/pdf/qpg_icse23.pdf)
* [DynSQL: Stateful Fuzzing for Database Management Systems with Complex and Valid SQL Query Generation](https://www.usenix.org/system/files/sec23summer_60-jiang_zu_ming-prepub.pdf)
* [Testing SQL Server's Query Optimizer: Challenges, Techniques and Experiences](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C48&q=Testing+SQL+Server%E2%80%99s+Query+Optimizer%3A+Challenges%2C+Techniques+and+Experiences&btnG=)
* [Squirrel](https://github.com/s3team/Squirrel) — a coverage-guided DBMS fuzzer.
* [Oracle database replay](https://dl.acm.org/doi/10.1145/1376616.1376732) — Oracle replay from 2008
* [Scope playback: self-validation in the cloud](https://dl.acm.org/doi/10.1145/2304510.2304514) — Scope playback from Microsoft for SQL-like execution on top of MapReduce


## Query Execution
* [Testing query execution engines with mutations](https://dl.acm.org/doi/pdf/10.1145/3395032.3395322) 
* [Verifying Transactional Consistency of MongoDB](https://arxiv.org/abs/2111.14946)
* [SQLancer](https://github.com/sqlancer/sqlancer)


## Query Optimization
* [Deploying a Steered Query Optimizer in Production at Microsoft](https://dl.acm.org/doi/abs/10.1145/3514221.3526052)
* [The Cascades Framework for Query Optimization at Microsoft (Nico Bruno + Cesar Galindo-Legaria)](https://youtu.be/pQe1LQJiXN0)


## Benchmarking
* [Creating a Virtuous Cycle in Performance Testing at MongoDB](https://dl.acm.org/doi/10.1145/3427921.3450234)
* [The Use of Change Point Detection to Identify Software Performance Regressions in a Continuous Integration System](https://dl.acm.org/doi/abs/10.1145/3358960.3375791)
* [Fair Benchmarking Considered Difficult: Common Pitfalls In Database Performance Testing](https://mytherin.github.io/papers/2018-dbtest.pdf)

## Conferences
* [Workshop on Testing Database Systems](https://dbtest-workshop.github.io/)


## Approaches by company

### Databricks 
* [SparkFuzz: searching correctness regressions in modern query engines](https://dl.acm.org/doi/abs/10.1145/3395032.3395327)
* [Correctness and Performance of Apache Spark SQL with Bogdan Ghit and Nicolas Poggi (Databricks)](https://youtu.be/fddBOZxdUKI)


### Snowflake
* [Snowtrail: Testing with Production Queries on a Cloud Database](https://dl.acm.org/doi/10.1145/3209950.3209958)


### DuckDB Labs (DuckDB)
* [DuckDB Testing - Present and Future](https://youtu.be/BgC79Zt2fPs) by [Mark Raasveldt](https://twitter.com/mraasveldt) — comprehensive overview of testing of DuckDB for correctness, reliability and performance


## Greenplum (Orca)
* [Automatic capture of minimal, portable, and executable bug repros using AMPERe](https://dl.acm.org/doi/10.1145/2304510.2304513) (DBTest 2012)
* [Testing the accuracy of query optimizers](https://dl.acm.org/doi/10.1145/2304510.2304525) (DBTest 2012) aka TAQO
* [Orca: a modular query optimizer architecture for big data](https://dl.acm.org/doi/10.1145/2588555.2595637) (SIGMOD 2014)


## Cockroach Labs (CockroachDB)
* [Introducing Pebble: A RocksDB-inspired key-value store written in Go](https://www.cockroachlabs.com/blog/pebble-rocksdb-kv-store/) 
— Includes thorough discussion on what it takes to properly test a storage engine


## Apache Calcite
* https://github.com/hydromatic/sql-logic-test/


## SQLite
* https://www.sqlite.org/sqllogictest/doc/trunk/about.wiki — Sqllogictest for SQLite


### Other systems
See [Single node systems](https://asatarin.github.io/testing-distributed-systems/#single-node-systems)

