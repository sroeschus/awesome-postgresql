# Awesome PostgreSQL
List of links with a focus on free and open source software for PostgreSQL.
# GUI
* [Jailer database tool](https://github.com/Wisser/Jailer) - Database subsetting and data browsing tool
* [migra](https://github.com/djrobstep/migra) - Schema diff
* [pgAdmin](https://www.pgadmin.org/) -  Open Source administration and development platform
* [pgModeler](https://pgmodeler.io/) - Database modeler
* [Postico](https://eggerapps.at/postico/) - A modern PostgreSQL client for the mac
* [SQL Developer](https://www.oracle.com/database/technologies/appdev/sql-developer.html) - Oracle SQL Developer (supports PostgreSQL)

# Commands / Functions
* [heroku-pg-extras](https://github.com/heroku/heroku-pg-extras) - A heroku plugin for awesome pg* commands
* [pglockanalyze](https://github.com/joyent/pglockanalyze) - Analyze locking behavior
* [pg-histogram](https://github.com/wolever/pg-histogram) - Functions for generating histograms
* [pg-utils](https://github.com/dataegret/pg-utils) - Useful utilities
* [pg_global_temp_tables](https://github.com/yallie/pg_global_temp_tables) - Global temporary tables
* [pg_toolkit](https://github.com/bdrouvot/pg_toolkit) - Some scripts to compare pages in memory and on disk
* [postgres-toolkit](https://github.com/uptimejp/postgres-toolkit) - Repository of SQL scripts

# Builtin-Extensions
* [pstattuple](https://www.postgresql.org/docs/11/pgstattuple.html) - Obtain tuple-level statistics

# Extensions
* [pgxn](https://pgxn.org/) - PostgreSQL extension network
* [Supercharge your installation with extensions](http://leopard.in.ua/presentations/pgconf_2017/)
* [aqo](https://github.com/postgrespro/aqo) - Adaptive query optimization
* [call_graph](https://github.com/johto/call_graph) - Automatically creating function call graphs
* [citus](https://github.com/citusdata/citus) - Scalable postgres for multi-tenant and real-time analytics workloads
* [connection_limits](https://github.com/tvondra/connection_limits) - Set quotas on connections
* [crunchy_check_access](https://github.com/CrunchyData/crunchy_check_access) - Functions and views for object access inspection
* [cstore_fdw](https://github.com/citusdata/cstore_fdw) - Columnar store for analytics
* [emaj](https://github.com/dalibo/emaj) - Track updates on table sets with rollback capabilities
* [first_last](https://gitlab.com/depesz/first_last) - Aggregates to return first or last values/rows
* [hstore_ops](https://github.com/postgrespro/hstore_ops) - Better operator class for hstore
* [hypopg](https://github.com/HypoPG/hypopg) - Hypothetical Indexes
* [imcs](https://github.com/knizhnik/imcs) - In-Memory Columnar Store
* [login_hook](https://github.com/splendiddata/login_hook) - Logon trigger
* [log_functions](https://github.com/gleu/log_functions) - Logs each function executed
* [memstat](https://github.com/postgrespro/memstat) - Report memory context information
* [mods_since_analyze](https://github.com/gleu/mods_since_analyze) - Estimation of number of changed tuples since last analyze
* [pgaudit](https://github.com/pgaudit/pgaudit) - Session and object audit logging
* [pgbitmap](https://github.com/marcmunro/pgbitmap) - Space-optimized, non-sparse, bitmap type
* [pgbucket](https://bitbucket.org/dineshopenscg/pgbucket/src/master) - Simple scheduler
* [pgcov](https://github.com/johto/pgcov) - PL/PgSQL test coverage analysis
* [pghashlib](https://github.com/markokr/pghashlib) - Stable hash functions
* [pglocial](https://github.com/2ndQuadrant/pglogical) - Logical replication
* [pgmasq](https://github.com/citusdata/pgmasq) - Transparently forward transactions from a hot standby to a primary
* [pgsql-gzip](https://github.com/pramsey/pgsql-gzip) - Gzip compress and decompress
* [pg-biguint](https://github.com/craigbranscom/pg-biguint) - Unsigned 64-bit integers
* [pg-movtbl](https://github.com/adjust/pg-mvtbl) - Easily move tables and tablespaces
* [pg-strom](https://github.com/heterodb/pg-strom) - Accelerate batch and analytics workloads with utilization of GPU and NVME-SSD
* [pgsentinel](https://github.com/pgsentinel/pgsentinel) - Active session history
* [pg_adviser](https://github.com/gurjeet/pg_adviser) - Index adiviser
* [pg_auth_mon](https://github.com/RafiaSabih/pg_auth_mon) - Monitor client authentication attempts
* [pg_auto_failover](https://github.com/citusdata/pg_auto_failover) - Service for automated failover and high-availability 
* [pg_backtrace](https://github.com/postgrespro/pg_backtrace) - Show backtrace for errors and signals
* [pg_badplan](https://github.com/trustly/pg_badplan) - Logging queries where the expected / actual rows ratio exceeds a defined value
* [pg_bitcount](https://github.com/thehyve/pg_bitcount) - Bitcount function
* [pg_cgroups](https://github.com/cybertec-postgresql/pg_cgroups) - Manger linux control groups
* [pg_cheat_funcs](https://github.com/petergeoghegan/pg_cheat_funcs) - Useful functions
* [pg_crash](https://github.com/cybertec-postgresql/pg_crash) - Crash database instance
* [pg_crasher](https://github.com/davidcrawford/pg_crasher) - Crash database backend
* [pg_cron](https://github.com/citusdata/pg_cron) - Run periodic jobs
* [pg_cryogen](https://github.com/adjust/pg_cryogen) - Compressed append-only pluggable storage
* [pg_dbms_stats](https://github.com/ossc-db/pg_dbms_stats) - Create execution plans using frozen statistics
* [pg_dirtyread](https://github.com/df7cb/pg_dirtyread) - Read dead but unvacuumed tuples
* [pg_dropbuffers](https://github.com/rjuju/pg_dropbuffers) - Drop buffers from shared_buffers without needing to restart the cluster
* [pg_dropcache](https://github.com/zilder/pg_dropcache) - Invalidate the shared_buffers cache
* [pg_dtm](https://github.com/postgrespro/pg_dtm) - Distributed transaction manager
* [pg_eyes](https://github.com/alexandersamoylov/pg_eyes) - Functions and views for monitoring database state
* [pg_fiu](https://github.com/jasonmp85/pg_fiu) - Fault injection in userspace
* [pg_get_page_tuple](https://github.com/sangli00/pg_get_page_tuple) - Get relation block tuple
* [pg_grab_statement](https://github.com/postgrespro/pg_grab_statement) - Record successfully committed transactions
* [pg_hashids](https://github.com/iCyberon/pg_hashids) - Short unique id generator using hashids
* [pg_healer](https://github.com/turnstep/pg_healer) - Repair data corruptions automatically
* [pg_hibernator](https://github.com/gurjeet/pg_hibernator) - Save and Restore Postgres Cache
* [pg_hint_plan](https://github.com/ossc-db/pg_hint_plan) - Manually force some decisions in execution plans
* [pg_idx_advisor](https://github.com/cohenjo/pg_idx_advisor) - Analyze queries and give indexing advice
* [pg_inet_addr](https://github.com/eulerto/pg_inet_addr) - List network interfaces
* [pg_intpair](https://github.com/citusdata/pg_intpair) - int64pair data type
* [pg_logging](https://github.com/postgrespro/pg_logging) - Read log file
* [pg_log_disconnections_during_tx](https://github.com/MasaoFujii/pg_log_disconnections_during_tx) - Log disconnection during transaction
* [pg_log_userqueries](https://github.com/gleu/pg_log_userqueries) - Log queries done by specific user types
* [pg_lz4](https://github.com/zilder/pg_lz4) - LZ4 compression
* [pg_memorycontext](https://github.com/mutex73/pg_memorycontext) - Report memory context information
* [pg_mem_counters](https://github.com/topharley/pg_mem_counters) - Keep total and rpm named counters in shared memory
* [pg_octopus](https://github.com/citusdata/pg_octopus) - Health checker
* [pg_oltp_bench](https://github.com/postgrespro/pg_oltp_bench) - OLTP benchmark
* [pg_outrider](https://github.com/meistervonperf/pg_outrider) - Background worker to automatically extend relations
* [pg_pageprep](https://github.com/postgrespro/pg_pageprep) - Help prepare heap pages for migration to 64bit XID page format
* [pg_pathman](https://github.com/postgrespro/pg_pathman) - Partitioning tool for your database
* [pg_paxos](https://github.com/citusdata/pg_paxos) - Paxos and Paxos-based table replication for a cluster of PostgreSQL nodes
* [pg_plan_advsr](https://github.com/ossc-db/pg_plan_advsr) - Automated execution plan tuning
* [pg_profile](https://github.com/zubkov-andrei/pg_profile) - History of performance reports
* [pg_qualstats](https://github.com/powa-team/pg_qualstats) - Collect statistics about predicates to find missing indices
* [pq_query_internals](https://github.com/petergeoghegan/pg_query_internals) - Query sql query internals with SQL
* [pq_query_log](https://github.com/adjust/pg_querylog) - Show queries running on backends
* [pq_query_state](https://github.com/postgrespro/pg_query_state) - Query progress monitoring
* [pg_recall](https://github.com/mreithub/pg_recall) - Keep track of changes to certain tables
* [pg_remote_exec](https://github.com/cybertec-postgresql/pg_remote_exec) - Execute shell commands over database connection
* [pg_repack](https://github.com/reorg/pg_repack) - Reorganize tables with minimal locks
* [pg_restrict](https://github.com/eulerto/pg_restrict) - Restrict execution of SQL commands
* [pg_rlimit](https://github.com/harukat/pg_rlimit) - Interfaces for setrlimit and getrlimit
* [pg_sampletolog](https://github.com/anayrat/pg_sampletolog) - Sample statements or transactions to logs
* [pg_shard](https://github.com/citusdata/pg_shard) - Sharding (deprecated)
* [pg_shardman](https://github.com/postgrespro/pg_shardman) - Sharding built on partitioning, postgres_fdw and logical replication 
* [pg_similarity](https://github.com/eulerto/pg_similarity) - Support for similarity queries
* [pg_sleep](https://github.com/samber/pg_sleep) - Add pg_sleep and pg_usleep function
* [pg_sortstats](https://github.com/powa-team/pg_sortstats) - Collecting statistics about sorts
* [pg_squeeze](https://github.com/cybertec-postgresql/pg_squeeze) - Automatic bloat clean up
* [pg_stats](https://github.com/s-hironobu/pg_stats) - Customized statistics views
* [pg_stat_kcache](https://github.com/powa-team/pg_stat_kcache) - Gather statistics about physical disk access and CPU consumption
* [pq_stat_plans](https://github.com/2ndQuadrant/pg_stat_plans) - pg_stat_statements variant that differentiates between query plans
* [pq_stat_sql_plans](https://github.com/legrandlegrand/pg_stat_sql_plans) - Add plan_id column to pg_stat_statements
* [pg_store_plans](https://github.com/ossc-db/pg_store_plans) - Store execution plans
* [pg_terminator](https://gitlab.com/depesz/pg_terminator) - Tool for automatically canceling or terminating offending connections
* [pg_track_settings](https://github.com/rjuju/pg_track_settings) - Keep track of configuration changes
* [pg_track_slow_queries](https://github.com/julmon/pg_track_slow_queries) - Slow query tracking
* [pg_trgm_pro](https://github.com/postgrespro/pg_trgm_pro) - Text similarity measurement and index searching based on trigrams
* [pg_ulid](https://github.com/iCyberon/pg_ulid) - Universally Unique Lexicographically Sortable Identifier (ULID)
* [pg_wait_sampling](https://github.com/postgrespro/pg_wait_sampling) - Sampling based statistics of wait events
* [pg_xid](https://github.com/iCyberon/pg_xid) - Globally unique id generator
* [planfix](https://github.com/srutz/planfix) - Force specific indices
* [planscape_postgres_module](https://github.com/mejedi/planscape-postgresql-module) - Insight into the planning process
* [postgresql-hll](https://github.com/citusdata/postgresql-hll) - HyperLogLog data structures as a native data type
* [postgresql-popcount](https://github.com/eschmar/postgresql-popcount) - Population count function for data type bit(n)
* [postgresql-similarity](https://github.com/urbic/postgresql-similarity) - Functions that calculate the similarity between two strings
* [postgresql-topn](https://github.com/citusdata/postgresql-topn) - Returns the top values in a database according to some criteria
* [query_cache](https://github.com/thinkprojectgroup/query_cache) - Query cache to store the result set of queries
* [rum](https://github.com/postgrespro/rum) - RUM access method - inverted index with additional information in posting lists
* [short_ids](https://gitlab.com/depesz/short_ids) - Generate safely short, textual ids
* [sql_firewall](https://github.com/uptimejp/sql_firewall) - SQL firewall
* [sr_plan](https://github.com/postgrespro/sr_plan) - Save and restore query plans
* [stat_record](https://github.com/asotolongo/stat_record) - Record database statistics
* [timescaledb](https://github.com/timescale/timescaledb) - Time-series database
* [tuple_fdw](https://github.com/zilder/tuple_fdw) - POC for a compressed binary file storage foreign data wrapper
* [versioning](https://gitlab.com/depesz/Versioning) - Versioning of database changes
* [vops](https://github.com/postgrespro/vops) - Columnar store
* [walreader](https://github.com/moritetu/walreader) - Read WAL records with sql functions
* [wildspeed](https://github.com/postgrespro/wildspeed) - Fast wildcard search for like operator

# Libraries
* [asyncpg](https://github.com/MagicStack/asyncpg/) - A fast PostgreSQL Database Client Library for Python/asyncio
* [plantuner](https://github.com/postgrespro/plantuner) - Enable planner hints
* [pg_parallizator](https://github.com/postgrespro/pg_parallizator) - Building indexes in parallel.

# Monitoring / Performance
* [benchmarksql](https://github.com/petergeoghegan/benchmarksql) - TPCC
* [gensort](https://github.com/petergeoghegan/gensort) - Gensort tool for benchmarking sort performance 
* [iops](https://github.com/benschweizer/iops) - Benchmark disk I/O
* [mamosu](https://github.com/postgrespro/mamonsu) - Monitoring agent
* [pgbench-tools](https://github.com/gregs1104/pgbench-tools) - Benchmarking toolset
* [pgcenter](https://github.com/lesovsky/pgcenter) - Command-line admin tool for observing and troubleshooting postgres
* [pgcheetah](https://github.com/anayrat/pgcheetah) - Tool to replay workload randomly
* [PgHero](https://github.com/ankane/pghero) - A performance dashboard for Postgres
* [pgmetrics](https://github.com/rapidloop/pgmetrics) - Collect and display information and stats
* [pgsqlstat](https://github.com/joyent/pgsqlstat) - Report top-level postgres stats
* [pg_ash_scripts](https://github.com/pgsentinel/pg_ash_scripts) - Scripts for active session history
* [pg_insights](https://github.com/lob/pg_insights) - SQL for monitoring Postgres database health
* [pgstats](https://github.com/gleu/pgstats) - Collects PostgreSQL statistics, and either saves them in CSV files or print them on the stdout
* [pg_view](https://github.com/zalando/pg_view) - Detailed, real-time view of your database and system metrics
* [pg_ycsb](https://github.com/postgrespro/pg_ycsb) - YCSB-like benchmark for pgbench
* [postgresql-metrics](https://github.com/spotify/postgresql-metrics) - Tool that extracts and provides metrics
* [postgresql-perf-tools](https://github.com/virtuozzo/postgresql-perf-tools) - Performance Monitoring Tools
* [Queries to monitor postgres](https://github.com/nilenso/postgresql-monitoring)

# Tools
* [apposha](https://apposha.io) - The Extension for Scalable File IO
* [bdr](https://github.com/2ndQuadrant/bdr) - Bi-Directional Multi-Master Replication (BDR)
* [condenser](https://github.com/TonicAI/condenser) - Database subsetting tool
* [Configurator](http://pgconfigurator.cybertec.at/) - Config file configurator
* [Depesz explain tool](https://explain.depesz.com/) - Online explain plan tool
* [dexter](https://github.com/ankane/dexter) - Automatic indexer
* [gocmdpev](https://github.com/simon-engledew/gocmdpev) - Command-line GO Postgres query visualizer
* [odyssey](https://github.com/yandex/odyssey) - Scalable connection pooler
* [paf](http://clusterlabs.github.io/PAF/) - PostgreSQL automatic failover
* [patroni](https://github.com/zalando/patroni) - A template for High Availability with ZooKeeper, etcd, or Consul
* [pev](https://github.com/AlexTatiyants/pev) - Explain plan visualizer
* [pev2](https://dalibo.github.io/pev2/#/) - Explain plan visualizer
* [pgBadger](http://pgbadger.darold.net) - Log analyzer
* [pgbouncer](http://www.pgbouncer.org/) - Lightweight connection pooler
* [pgcli](https://github.com/dbcli/pgcli) - CLI with autocompletion and syntax highlighting
* [pgio](https://github.com/therealkevinc/pgio) - SLOB method tool
* [pgloader](https://pgloader.io/) - Data loader
* [pgreplay](https://github.com/laurenz/pgreplay) - Replay statements from a log file
* [pgreplay-go](https://github.com/gocardless/pgreplay-go/) - Replay SQL statements at approximately the same rate
* [pgrouter](https://github.com/jhunt/pgrouter) - A router for postgres HA
* [pgsync](https://github.com/ankane/pgsync) - Sync data between databases
* [pg_auto_failover](https://github.com/citusdata/pg_auto_failover) - Service for automated failover and high-availability
* [pg_catcheck](https://github.com/EnterpriseDB/pg_catcheck) - Catalog checker
* [pg_filedump](https://github.com/df7cb/pg_filedump) - Low-level examination of tables and indexes
* [pg_flame](https://github.com/mgartner/pg_flame) - Flamegraph generator for explain analyze output
* [pg_hexedit](https://github.com/petergeoghegan/pg_hexedit) - Open data files in a hex editor
* [pg_page_verification](https://github.com/google/pg_page_verification) - Verify checksums on data pages
* [pg_prefaulter](https://github.com/joyent/pg_prefaulter) - Faults pages into shared_buffers or filesystem caches in advance of WAL apply
* [pg_probackup](https://github.com/postgrespro/pg_probackup) - Backup and recovery manager
* [pg_reloaded](https://github.com/zikani03/pg_reloaded) - Restore databases periodically
* [pg_reorg](https://github.com/ossc-db/pg_reorg) - Reorganize tables without keeping locks
* [pg_rman](https://github.com/ossc-db/pg_rman) - Backup and restore management tool
* [pg_tail](https://github.com/aaparmeggiani/pg_tail) - tail -f your tables
* [pg_timetable](https://github.com/cybertec-postgresql/pg_timetable) - Advanced scheduling
* [piretry](https://dalibo.github.io/pitrery/) - Set of bash scripts to manage Point In Time Recovery (PITR) backups
* [postgresqltuner](https://github.com/jfcoz/postgresqltuner) - Script to analyse your database configuration, and give tuning advice
* [postgres_all_versions](https://github.com/bucardo/postgres_all_versions) - Release notes parser
* [PostgeSQL Anonmyizer](https://gitlab.com/dalibo/postgresql_anonymizer) - Anonymization & Data Masking
* [postgreSQL-Query-Lock-Explainer](https://github.com/AdmTal/PostgreSQL-Query-Lock-Explainer) - Query lock explainer
* [pspg](https://github.com/okbob/pspg) - Unix pager designed to work with tables
* [repmgr](https://repmgr.org/) - Replication manager
* [stellar](https://github.com/fastmonkeys/stellar) - Fast database snapshot and restore tool for development
* [stolon](https://github.com/sorintlab/stolon) - Cloud native high availability
* [wal-e](https://github.com/wal-e/wal-e) - Continous archiving
* [wal-g](https://github.com/wal-g/wal-g) - Archival and restauration tool
* [yoke](https://github.com/nanopack/yoke) - High-availability cluster with auto-failover and automated cluster recovery

# Forks
* [C++ port of postgres](https://github.com/jarulraj/postgresql-cpp)
* [postgresql.builtin_pool](https://github.com/postgrespro/postgresql.builtin_pool) - PostgreSQL with built-in connection pooling
* [zHeap](https://github.com/EnterpriseDB/zheap)

# Development
* [vipsql](https://github.com/martingms/vipsql) - Vim frontend for interacting with psql
* [gdbpg](https://github.com/tvondra/gdbpg) - GDB command(s) making debugging somewhat easier
* [Postgres bugs](https://granicus.if.org/pgbugs/) - List of current and past bugs
* [Development wiki](https://wiki.postgresql.org/wiki/Developer_and_Contributor_Resources) - Development information
* [Writing extensions is fun](https://www.percona.com/blog/2019/04/05/writing-postgresql-extensions-is-fun-c-language/) - Step-by-step guide to developing extensions
* [PostgreSQL: Simple C extension development for a novice user (and performance advantages)](https://www.percona.com/blog/2019/07/31/postgresql-simple-c-extension-development-for-a-novice-user/)
* [pg_plugins](https://github.com/michaelpq/pg_plugins) - Templates for plugins
* [postgresql-extension-example](https://github.com/pkorobeinikov/postgresql-extension-example) - Extension examples
* [pgxn-utils](https://github.com/guedes/pgxn-utils) - Tools to create extensions
* [psql-hooks](https://github.com/AmatanHead/psql-hooks) - Unofficial documentation of hooks

# Patches
* [execplan](https://github.com/danolivo/execplan) - Raw query plan execution
* [Extended Prefetching using Asynchronous IO](https://www.postgresql.org/message-id/BAY175-W45086073075CA064EFE9A0A33A0%40phx.gbl)
* [stats_recorder](https://github.com/gleu/stats_recorder) - Background worker code that gets a periodic copy of activity statistics
* [Zedstore - compressed in-core columnar storage](https://www.postgresql.org/message-id/flat/CALfoeiuF-m5jg51mJUPm5GN8u396o5sA2AF5N97vTRAEDYac7w%40mail.gmail.com)

# Documentation / Blogs
[Postgres documentation](https://www.postgresql.org/docs/12/index.html)
## Architecture
- [Backend Flowchart](https://www.postgresql.org/developer/backend/)
- [Life of a SQL query](https://numeracy.co/blog/life-of-a-sql-query)
## Analytics
- GPU
  - [GPU Accelerated SQL queries with PostgreSQL & PG-Strom](https://blog.openshift.com/gpu-accelerated-sql-queries-with-postgresql-pg-strom-in-openshift-3-10/)
  - [Bringing GPU's to bear on bog standard relational databases](https://www.nextplatform.com/2018/02/26/bringing-gpus-bear-bog-standard-relational-databases/)
- Columnar store
  - [In-memory Column Store](https://www.youtube.com/watch?v=ahMo3kd9_hM) - Fujitsu Columnar and in-memory solution
## Authentication
- [PostgreSQL administrator account with nologin (recover your postgres role)](https://fluca1978.github.io/2019/06/27/PostgreSQLSingleMode.html)
- [How to upgrade your PostgreSQL passwords to SCRAM](https://info.crunchydata.com/blog/how-to-upgrade-postgresql-passwords-to-scram)
- [pgBouncer and auth pass-thru](https://hunleyd.github.io/posts/pgBouncer-and-auth-pass-thru/)
## Connection pool
- [The challenges of setting max_connections and why you should use a connection pooler](https://richyen.com/postgres/2019/06/25/pools_arent_just_for_cars.html)
- [Pgpool wiki](https://pgpool.net/mediawiki/index.php/Main_Page)
- [A guide to pgpool for PostgreSQL: Part one](https://severalnines.com/database-blog/guide-pgpool-postgresql-part-one)
- [A guide to pgpool for PostgreSQL: Part two](https://severalnines.com/database-blog/guide-pgpool-postgresql-part-two)
## Datatypes
- [PostgreSQL interval, date, timestamp and time data types](https://www.2ndquadrant.com/en/blog/know-what-time-it-is/)
* Date / Timestamp
  * [Does anyone really know what time it is?](https://thebuild.com/blog/2018/08/07/does-anyone-really-know-what-time-it-is/)
  * [PostgreSQL Data Types: Date, Timestamp, and Time Zones](https://tapoueh.org/blog/2018/04/postgresql-data-types-date-timestamp-and-time-zones/)
## ETL
- [Fastest way to load data into PostgreSQL using python](https://hakibenita.com/fast-load-data-python-postgresql)
## Table
- [Heap only table (HOT)](https://github.com/postgres/postgres/blob/master/src/backend/access/heap/README.HOT)
- [PostgreSQL and heap-only-tuples updates - part 1](https://blog.anayrat.info/en/2018/11/12/postgresql-and-heap-only-tuples-updates-part-1/)
- [PostgreSQL and heap-only-tuples updates - part 2](https://blog.anayrat.info/en/2018/11/19/postgresql-and-heap-only-tuples-updates-part-2/)
- [PostgreSQL and heap-only-tuples updates - part 3](https://blog.anayrat.info/en/2018/11/26/postgresql-and-heap-only-tuples-updates-part-3/)
## Index
- Bloom Index
  - [Bloom Indexes in PostgreSQL](https://www.percona.com/blog/2019/06/14/bloom-indexes-in-postgresql/)
  - [Indexes in PostgreSQL — 10 (Bloom)](https://habr.com/en/company/postgrespro/blog/452968/)
- BRIN Index
  - [BRIN Index for PostgreSQL: Don’t forget the benefits](https://www.percona.com/blog/2019/07/16/brin-index-for-postgresql-dont-forget-the-benefits/)
- GIN index
  - [Indexes in PostgreSQL — 7 (GIN)](https://habr.com/en/company/postgrespro/blog/448746/)
  - [PostgreSQL's indexes - GIN](http://www.louisemeta.com/blog/indexes-gin/)
- Covering Indexes
  - [PostgreSQL 11 highlight - Covering Indexes](https://paquier.xyz/postgresql-2/postgres-11-covering-indexes/)
- Combined Indexes
  - [Combined indexes vs. separate indexes in PostgreSQL](https://www.cybertec-postgresql.com/en/combined-indexes-vs-separate-indexes-in-postgresql/)
- [Hypothetical Indexes in PostgreSQL](https://www.percona.com/blog/2019/06/21/hypothetical-indexes-in-postgresql/)
- [Automatic index recommendations in PostgreSQL using pg_qualstats and hypopg](https://www.percona.com/blog/2019/07/22/automatic-index-recommendations-in-postgresql-using-pg_qualstats-and-hypopg/)
- [How to index your database](https://www.xaprb.com/slides/index-postgresql-database-postgresconf-2018/#1)
- [Indexing with PostgreSQL: When less is more](https://medium.com/plangrid-technology/indexing-with-postgres-when-less-is-more-7337d6f09048)
## Sequence
- [Checking the sequences status on a single pass](https://fluca1978.github.io/2019/06/11/SequenceCheck.html)
- [The modern alternative to SERIAL columns](https://postgresweekly.com/issues/311)
- [Generate primary keys (almost) automatically](https://fluca1978.github.io/2019/07/09/GeneratePrimaryKeys.html)
## Transaction
- [SERIALIZABLE in PostgreSQL 11... and beyond](https://write-skew.blogspot.com/2018/05/serializable-in-postgresql-11-and-beyond.html)
- [How to implement autonomous transactions in PostgreSQL](https://www.cybertec-postgresql.com/en/implementing-autonomous-transactions-in-postgres/)
- [idle_in_transaction_session_timeout: Terminating idle transactions in PostgreSQL](https://www.cybertec-postgresql.com/en/idle_in_transaction_session_timeout-terminating-idle-transactions-in-postgresql/)
## HA
- [Top PG Clustering High Availability (HA) Solutions for PostgreSQL](https://severalnines.com/database-blog/top-pg-clustering-high-availability-ha-solutions-postgresql)
- [Introducing pg_auto_failover: Open source extension for automated failover and high-availability in PostgreSQL](https://cloudblogs.microsoft.com/opensource/2019/05/06/introducing-pg_auto_failover-postgresql-open-source-extension-automated-failover-high-availability/)
- [Introduction to PostgreSQL automatic failover](https://pgstef.github.io/2018/02/07/introduction_to_postgresql_automatic_failover.html)
- [Standby in production: scaling application in the second largest classified site in the world](https://medium.com/avitotech/standby-in-production-scaling-application-in-second-largest-classified-site-in-the-world-97a79a1929de)
## Query Planer
- [Debugging the postgres query planer](https://gocardless.com/blog/debugging-the-postgres-query-planner/)
- [An Overview of various auxiliary plan nodes in PostgreSQL](https://severalnines.com/database-blog/overview-various-auxiliary-plan-nodes-postgresql?utm_campaign=Cloud_DR_Campaign_OCT19&utm_content=pg_plan_nodes&utm_medium=Social_Media&utm_source=Twitter)
- [An Overview of Just-in-Time Compilation (JIT) for PostgreSQL](https://severalnines.com/database-blog/overview-just-time-compilation-jit-postgresql)
- [Postgres execution plans — Field glossary](https://medium.com/pgmustard/postgres-execution-plans-field-glossary-bc588340b0db)
## Parallel Processing
- [Parallelism in PostgreSQL](https://www.percona.com/blog/2019/07/30/parallelism-in-postgresql/)
- [PostgreSQL 10 Parallel Queries and Performance](https://blog.rustprooflabs.com/2018/02/pg10_parallel_queries)
- [Parallel queries in PostgreSQL](https://www.percona.com/blog/2019/02/21/parallel-queries-in-postgresql/)
## Partitioning
- [PostgreSQL 11 Partitioning Improvements](https://pgdash.io/blog/partition-postgres-11.html)
- [Partitioning Improvements in PostgreSQL 11](https://www.2ndquadrant.com/en/blog/slides-partitioning-pg-11/)
- [Partition Elimination in PostgreSQL 11](https://www.2ndquadrant.com/en/blog/partition-elimination-postgresql-11/)
## Sharding
- [An Overview of Sharding in PostgreSQL and How it Relates to MongoDB’s](https://www.percona.com/blog/2019/05/24/an-overview-of-sharding-in-postgresql-and-how-it-relates-to-mongodbs/)
## Performance
- [Performance Monitoring & Auditing PostgreSQL - Top Resources](https://severalnines.com/database-blog/performance-monitoring-auditing-postgresql-top-resources)
- [Metrics to Monitor in Your PostgreSQL Database](https://www.influxdata.com/blog/metrics-to-monitor-in-your-postgresql-database/?utm_campaign=postgres&utm_medium=newsletter&utm_source=cooperpress)
- [Key metrics for PostgreSQL monitoring](https://www.datadoghq.com/blog/postgresql-monitoring/)
- [Collecting metrics with PostgreSQL monitoring tools](https://www.datadoghq.com/blog/postgresql-monitoring-tools/)
- [Monitoring CPU and memory usage](https://aaronparecki.com/2015/02/19/8/monitoring-cpu-memory-usage-from-postgres)
- [Monitoring cheatsheet](https://russ.garrett.co.uk/2015/10/02/postgres-monitoring-cheatsheet/)
- [PostgreSQL technical performance presentations](http://momjian.us/main/presentations/performance.html)
- [Vertically Scaling PostgreSQL](https://pgdash.io/blog/scaling-postgres.html)
- Tools
  - [Profiling with perf](https://wiki.postgresql.org/wiki/Profiling_with_perf)
  - [pgCenter’s wait events profiler](https://blog.dataegret.com/2019/03/pgcenters-wait-event-profiler.html)
  - [Announcing pgio](https://kevinclosson.net/2019/09/21/announcing-pgio-the-slob-method-for-postgresql-is-released-under-apache-2-0-and-available-at-github/)
  - [So pgio does not accurately report physical I/O in test results? Buffering buffers, and baffles](https://kevinclosson.net/2019/09/27/so-pgio-does-not-accurately-report-physical-i-o-in-test-results-buffering-buffers-and-baffles/)
  - [Announcing pgmetrics](https://www.opsdash.com/blog/announcing-pgmetrics.html)
  - [pgio / pg_hint_plan / pg_sentinel demo](https://www.youtube.com/watch?v=tMNviAclMKo&feature=youtu.be)
- Locks
  - [Lock monitoring](https://wiki.postgresql.org/wiki/Lock_Monitoring)
  - [PostgreSQL rocks, except when it blocks: Understanding locks](https://www.citusdata.com/blog/2018/02/15/when-postgresql-blocks/)
  - [When PostgreSQL blocks: 7 tips for dealing with locks](https://www.citusdata.com/blog/2018/02/22/seven-tips-for-dealing-with-postgres-locks/)
  - [How to track long-waiting locks in your database](https://postgresweekly.com/issues/303)
  - [Migrations and long transactions in PostgreSQL](https://www.fin.com/posts/migrations-and-long-transactions-in-postgres/)
- Queries
  - [3 ways to detect slow queries in PostgreSQL](https://www.cybertec-postgresql.com/en/3-ways-to-detect-slow-queries-in-postgresql/)
  - [Automatically logging slow queries](https://postgresweekly.com/issues/301)
  - [Detecting performance problems easily in PostgreSQL](https://www.cybertec-postgresql.com/en/detecting-performance-problems-easily-in-postgresql/)
  - [Avoiding “OR” for better query peformance](https://www.cybertec-postgresql.com/en/avoid-or-for-better-performance/)
  - [The most useful Postgres extension: pg_stat_statements](https://www.citusdata.com/blog/2019/02/08/the-most-useful-postgres-extension-pg-stat-statements/)
- Stored Procedures
  - [Improving performance with stored procedures — a pgbench example](https://medium.com/@FranckPachot/improving-performance-with-stored-procedures-a-pgbench-example-249a1f6b9f6c)
- Statistics
  - [The PostgreSQL 10 feature you didn't know about: create statistics](https://www.citusdata.com/blog/2018/03/06/postgres-planner-and-its-usage-of-statistics/)
## Recovery
- [pg_wal is too big, what is going on](https://blog.dataegret.com/2018/04/pgwal-is-too-big-whats-going-on.html)
## Replication
- [Three Steps to pg_rewind Happiness](https://thebuild.com/blog/2018/08/09/three-steps-to-pg_rewind-happiness/)
- [Converting from asynchronous to synchronous replication in PostgreSQL](https://severalnines.com/database-blog/converting-asynchronous-synchronous-replication-postgresql?utm_campaign=Vendor_Lockin_Campaign_NOV19&utm_content=pg_async_sync&utm_medium=Social_Media&utm_source=Twitter)
- [An overview of logical replication](https://severalnines.com/database-blog/overview-logical-replication-postgresql)
- [PostgreSQL Replication with easy failback](https://www.scalingpostgres.com/tutorials/postgresql-replication-easy-failback/)
- [PostgreSQL Replication failback with pg_rewind](https://www.scalingpostgres.com/tutorials/postgresql-replication-failback-pg-rewind/)
- [PostgreSQL Replication Monitoring](https://www.scalingpostgres.com/tutorials/postgresql-replication-monitoring/)
## SQL
* CTE
  * [Fun with SQL: Common Table Expressions for more readable queries](https://www.citusdata.com/blog/2018/08/09/fun-with-sql-common-table-expressions/)
* first_value / last_value
  * [Advanced SQL: Why first_value and last_value are no bugs](https://www.cybertec-postgresql.com/en/advanced-sql-why-first_value-and-last_value-are-no-bugs/)
* generate_series
  * [Simple Monthly Reports in PostgreSQL Using generate_series](https://rob.conery.io/2018/08/01/simple-monthly-reports-in-postgresql-using-generate_series/)
* select
  * [Count(*) made fast](https://www.cybertec-postgresql.com/en/postgresql-count-made-fast/)
  * [Selecting a 'sample' of a table's rows](https://postgresweekly.com/issues/300)
## PGSQL
- [Tech preview: PostgreSQL 11 – create procedure](https://www.cybertec-postgresql.com/en/tech-preview-postgresql-11-create-procedure/)
## Security
- [PostgreSQL Deep Dive: PostgreSQL Defaults and Impact on Security - Part 1](https://info.crunchydata.com/blog/postgresql-defaults-and-impact-on-security-part-1)
- [PostgreSQL Deep Dive: PostgreSQL Defaults and Impact on Security - Part 2](https://info.crunchydata.com/blog/postgresql-defaults-and-impact-on-security-part-2)
- [Install PostgreSQL 9.6 with transparent data encyption](https://www.cybertec-postgresql.com/en/install-postgresql-9-6-with-transparent-data-encryption/)
- [How the CIS Benchmark for PostgreSQL 11 Works](https://info.crunchydata.com/blog/cis-11-benchmark)
## Upgrade
- [Near-Zero Downtime Automated Upgrades of PostgreSQL Clusters in Cloud (Part I)](https://www.2ndquadrant.com/en/blog/near-zero-downtime-automated-upgrades-postgresql-clusters-cloud/)
- [Near-Zero Downtime Automated Upgrades of PostgreSQL Clusters in Cloud (Part II)](https://www.2ndquadrant.com/en/blog/near-zero-downtime-automated-upgrades-postgresql-clusters-cloud-part-ii/)
- [PostgreSQL 10 upgrade](https://bricklen.github.io/2018-03-27-Postgres-10-upgrade/)
## Migration
- [Oracle to Postgres Conversion](https://wiki.postgresql.org/wiki/Oracle_to_Postgres_Conversion)
## MVCC
- [MVCC and Vaccum](http://rhaas.blogspot.com/2017/12/mvcc-and-vacuum.html)
- [Different approaches for MVCC used in well known databases](http://amitkapila16.blogspot.com/2015/03/different-approaches-for-mvcc-used-in.html)
- [PostgreSQL concurrency with MVCC](https://devcenter.heroku.com/articles/postgresql-concurrency)
## Vacuum
- [Tuning Autovacuum in PostgreSQL and Autovacuum Internals](https://www.percona.com/blog/2018/08/10/tuning-autovacuum-in-postgresql-and-autovacuum-internals/)
- [Managing Freezing in PostgreSQL	](https://www.2ndquadrant.com/en/blog/managing-freezing/)
- [Monitoring PostgreSQL VACUUM processes](https://www.datadoghq.com/blog/postgresql-vacuum-monitoring/)
- [PostgreSQL Bloatbusters](https://blog.dataegret.com/2018/03/postgresql-bloatbusters.html)
- [VACUUM FULL doesn't mean "VACUUM, but better"](http://rhaas.blogspot.com/2014/03/vacuum-full-doesnt-mean-vacuum-but.html)
- [The State of VACUUM](http://rhaas.blogspot.com/2018/01/the-state-of-vacuum.html)
- [DO or UNDO - there is no VACUUM](http://rhaas.blogspot.com/2018/01/do-or-undo-there-is-no-vacuum.html)
## I/O
- [PostgreSQL's fsync() surprise](https://lwn.net/Articles/752063/)
## Pluggable storage
- [Pluggable storage discussion](https://www.postgresql.org/message-id/flat/20160812231527.GA690404%40alvherre.pgsql#20160812231527.GA690404@alvherre.pgsql)
## Foreign Data Wrapper
- [A Tour of Foreign Data Wrappers](http://www.craigkerstiens.com/2016/09/11/a-tour-of-fdws/)
## OS
- Linux
  - [How to adjust Linux Out-Of-Memory killer settings for PostgreSQL](https://www.percona.com/blog/2019/08/02/out-of-memory-killer-or-savior/)
  - [Manage linux control groups in PostgreSQL with pg_cgroups](https://www.cybertec-postgresql.com/en/pg_cgroups-linux-control-groups-in-postgresql/)
## Limits
- [PostgreSQL maximum table sizes](https://www.2ndquadrant.com/en/blog/postgresql-maximum-table-size/)
## Cloud
- [Cloud vendor deep-dive: PostgreSQL on AWS Aurora](https://severalnines.com/database-blog/cloud-vendor-deep-dive-postgresql-aws-aurora)
