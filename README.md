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
* [pgsql-tweaks](https://github.com/sjstoelting/pgsql-tweaks) - Useful PostgreSQL functions
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
* [ap_pgutils](https://github.com/Apsalar/ap_pgutils) - Functions for hostname, argon2 password hashing and TOTP based 2 factor authentication
* [aqo](https://github.com/postgrespro/aqo) - Adaptive query optimization
* [atree](https://github.com/XiaYingyin/atree) - Atree index implementation
* [bg_mon](https://github.com/CyberDem0n/bg_mon) - Background worker for monitoring PostgreSQL
* [bitmap-postgresql](https://github.com/jiayuasu/bitmap-postgresql) - An on-disk bitmap index
* [call_graph](https://github.com/johto/call_graph) - Automatically creating function call graphs
* [citus](https://github.com/citusdata/citus) - Scalable postgres for multi-tenant and real-time analytics workloads
* [cms_topn](https://github.com/ozturkosu/cms_topn) - Use count-min sketch top-n algorithm
* [config_log](https://github.com/ibarwick/config_log) - Custom background worker (BGW) for monitoring configuration log changes
* [connection_limits](https://github.com/tvondra/connection_limits) - Set quotas on connections
* [count_bits](https://github.com/sldab/count-bits) - Functions for counting bits
* [count_distinct](https://github.com/tvondra/count_distinct) - Alternative to COUNT(DISTINCT ...) aggregate in PostgreSQL
* [crunchy_check_access](https://github.com/CrunchyData/crunchy_check_access) - Functions and views for object access inspection
* [cstore_fdw](https://github.com/citusdata/cstore_fdw) - Columnar store for analytics
* [diskquota](https://github.com/greenplum-db/diskquota) - Disk usage enforcement for database objects in PostgreSQL
* [distinct_estimators](https://github.com/tvondra/distinct_estimators) - Distinct counters and aggregate functions for distinct estimation in PostgreSQL
* [elephant-worker](https://github.com/trax777/elephant-worker) - Background workers in PostgreSQL
* [emaj](https://github.com/dalibo/emaj) - Track updates on table sets with rollback capabilities
* [first_last](https://gitlab.com/depesz/first_last) - Aggregates to return first or last values/rows
* [fnvhash](https://github.com/amutu/fnvhash) - FNV hash function for PostgreSQL
* [generic_scheduler](https://github.com/okbob/generic-scheduler) - Generic SQL statements scheduler without additional dependencies
* [hashtypes](https://github.com/pandrewhk/hashtypes) - SHA1, MD5 and other data types for PostgreSQL
* [hstore_ops](https://github.com/postgrespro/hstore_ops) - Better operator class for hstore
* [hypopg](https://github.com/HypoPG/hypopg) - Hypothetical Indexes
* [imcs](https://github.com/knizhnik/imcs) - In-Memory Columnar Store
* [incubator-datasketches-postgresql](https://github.com/apache/incubator-datasketches-postgresql) - Approximate algorithms based on DataSketches
* [kmeans-postgresql](https://github.com/umitanuki/kmeans-postgresql) - K-means function as a user-defined window function in PostgreSQL
* [libuuid](https://github.com/petere/pglibuuid) - Wrapper for libuuid
* [login_hook](https://github.com/splendiddata/login_hook) - Logon trigger
* [log_functions](https://github.com/gleu/log_functions) - Logs each function executed
* [memstat](https://github.com/postgrespro/memstat) - Report memory context information
* [mods_since_analyze](https://github.com/gleu/mods_since_analyze) - Estimation of number of changed tuples since last analyze
* [oracle_fdw](https://github.com/laurenz/oracle_fdw) - PostgreSQL Foreign Data Wrapper for Oracle
* [pagevis](https://github.com/hollobon/pagevis) - PostgreSQL data page visualisation
* [pgaudit](https://github.com/pgaudit/pgaudit) - Session and object audit logging
* [pgbitmap](https://github.com/marcmunro/pgbitmap) - Space-optimized, non-sparse, bitmap type
* [pgbloom](https://github.com/saaros/pgbloom) - Bloom filters for PostgreSQL
* [pgbucket](https://bitbucket.org/dineshopenscg/pgbucket/src/master) - Simple scheduler
* [pgcov](https://github.com/johto/pgcov) - PL/PgSQL test coverage analysis
* [pgextwhitelist](https://github.com/dimitri/pgextwlist) - PostgreSQL Extension Whitelisting
* [pghashlib](https://github.com/markokr/pghashlib) - Stable hash functions
* [phgist](https://github.com/segasai/pg_hist) - Fast uni-variate and multivariate histograms in PostgreSQL
* [pgloggingfilter](https://github.com/ohmu/pgloggingfilter) - Filter module for postgresql logging
* [pglogical](https://github.com/2ndQuadrant/pglogical) - Logical replication
* [pgmasq](https://github.com/citusdata/pgmasq) - Transparently forward transactions from a hot standby to a primary
* [pgmedian](https://github.com/sveljko/pgmedian) - Median aggregate for PostgreSQL
* [pgmemcache](https://github.com/ohmu/pgmemcache) - set of PostgreSQL user-defined functions that provide an interface to memcached
* [pgora-osql](https://github.com/pgoracle/pgora-osql) - Procedural Language with Oracle PLSQL Compatibility
* [pgsampler](https://github.com/no0p/pgsampler) - Background worker for collecting status and performance metrics
* [pgsql-gzip](https://github.com/pramsey/pgsql-gzip) - Gzip compress and decompress
* [pgsentinel](https://github.com/pgsentinel/pgsentinel) - Active session history
* [pgtrashcan](https://github.com/petere/pgtrashcan) - PostgreSQL trash can
* [pgzstd](https://github.com/grahamedgecombe/pgzstd) - Zstandard compression/decompression with preset dictionary support
* [pg-bignum](https://github.com/beargiles/pg-bignum) - PostgreSQL extension for unlimited precision integers
* [pg-biguint](https://github.com/craigbranscom/pg-biguint) - Unsigned 64-bit integers
* [pg-hash64](https://github.com/theory/pg-hash64) - Generate 64-bit hash integers from PostgreSQL strings
* [pg-movtbl](https://github.com/adjust/pg-mvtbl) - Easily move tables and tablespaces
* [pg-progress](https://github.com/wulczer/pg-progress) - Query progress estimation for PostgreSQL
* [pg-spgist_hamming](https://github.com/fake-name/pg-spgist_hamming) - Fast hamming-distance range searches via native GiST Indexing facility in PostgreSQL
* [pg-strom](https://github.com/heterodb/pg-strom) - Accelerate batch and analytics workloads with utilization of GPU and NVME-SSD
* [pg-ulid](https://github.com/edoceo/pg-ulid) - ULID functions for PostgreSQL
* [pg-uuid-int32](https://github.com/ancoron/pg-uuid-int32) - UUID data type stored as 32-bit integers
* [pg_adviser](https://github.com/gurjeet/pg_adviser) - Index adiviser
* [pg_auth_mon](https://github.com/RafiaSabih/pg_auth_mon) - Monitor client authentication attempts
* [pg_auto_failover](https://github.com/citusdata/pg_auto_failover) - Service for automated failover and high-availability 
* [pg_backtrace](https://github.com/postgrespro/pg_backtrace) - Show backtrace for errors and signals
* [pg_badplan](https://github.com/trustly/pg_badplan) - Logging queries where the expected / actual rows ratio exceeds a defined value
* [pg_bitcount](https://github.com/thehyve/pg_bitcount) - Bitcount function
* [pg_cgroups](https://github.com/cybertec-postgresql/pg_cgroups) - Manger linux control groups
* [pg_cheat_funcs](https://github.com/petergeoghegan/pg_cheat_funcs) - Useful functions
* [pg_check](https://github.com/tvondra/pg_check) - Basic consistency checking functionality for tables and b-tree indexes
* [pg_crash](https://github.com/cybertec-postgresql/pg_crash) - Crash database instance
* [pg_crasher](https://github.com/davidcrawford/pg_crasher) - Crash database backend
* [pg_cron](https://github.com/citusdata/pg_cron) - Run periodic jobs
* [pg_cryogen](https://github.com/adjust/pg_cryogen) - Compressed append-only pluggable storage
* [pg_cuckoo](https://github.com/kryonix/pg_cuckoo) - Use PostgreSQL's planner hook to open a side entrance through which we can pass plan trees for immediate execution
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
* [pg_keeper](https://github.com/MasahikoSawada/pg_keeper) - Simplified clustering module for PostgreSQL
* [pg_linegazer](https://github.com/funbringer/pg_linegazer) - Transparent code coverage for PL/pgSQL
* [pg_logfilter](https://github.com/ckh0618/pg_logfilter) - Filtering postgresql output log if it matches given patterns
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
* [pg_partman](https://github.com/pgpartman/pg_partman) - Partition management extension for PostgreSQL
* [pg_pathman](https://github.com/postgrespro/pg_pathman) - Partitioning tool for your database
* [pg_paxos](https://github.com/citusdata/pg_paxos) - Paxos and Paxos-based table replication for a cluster of PostgreSQL nodes
* [pg_permission](https://github.com/cybertec-postgresql/pg_permission) - Set of views to see ALL permissions in a PostgreSQL database
* [pg_plan_advsr](https://github.com/ossc-db/pg_plan_advsr) - Automated execution plan tuning
* [pg_popcount](https://github.com/yo1dog/pg_popcount) - popcount for PostgreSQL
* [pg_prioritize](https://github.com/schmiddy/pg_prioritize) - Get and set the priority of PostgreSQL backends
* [pg_profile](https://github.com/zubkov-andrei/pg_profile) - History of performance reports
* [pg_protobuf](https://github.com/afiskon/pg_protobuf) - Protobuf support for PostgreSQL
* [pg_qualstats](https://github.com/powa-team/pg_qualstats) - Collect statistics about predicates to find missing indices
* [pg_querylog](https://github.com/adjust/pg_querylog) - Show queries running on backends
* [pg_query_internals](https://github.com/petergeoghegan/pg_query_internals) - Query sql query internals with SQL
* [pg_query_state](https://github.com/postgrespro/pg_query_state) - Query progress monitoring
* [pg_recall](https://github.com/mreithub/pg_recall) - Keep track of changes to certain tables
* [pg_remote_exec](https://github.com/cybertec-postgresql/pg_remote_exec) - Execute shell commands over database connection
* [pg_repack](https://github.com/reorg/pg_repack) - Reorganize tables with minimal locks
* [pg_restrict](https://github.com/eulerto/pg_restrict) - Restrict execution of SQL commands
* [pg_retire](https://github.com/moritetu/pg_retire) - Simplified query canceler for PostgreSQL
* [pg_rlimit](https://github.com/harukat/pg_rlimit) - Interfaces for setrlimit and getrlimit
* [pg_roaringbitmap](https://github.com/ChenHuajun/pg_roaringbitmap) - Roaring bitmap data type
* [pg_sampletolog](https://github.com/anayrat/pg_sampletolog) - Sample statements or transactions to logs
* [pg_schedule](https://github.com/albertov/pg_schedule) - Cron-formatted schedule type for PostgreSQL
* [pg_setpriority](https://github.com/sshutdownow/pg_setpriority) - Set the priority of PostgreSQL process
* [pg_shard](https://github.com/citusdata/pg_shard) - Sharding (deprecated)
* [pg_shardman](https://github.com/postgrespro/pg_shardman) - Sharding built on partitioning, postgres_fdw and logical replication 
* [pg_similarity](https://github.com/eulerto/pg_similarity) - Support for similarity queries
* [pg_simula](https://github.com/MasahikoSawada/pg_simula) - A database system failure simulation tool for PostgreSQL
* [pg_sleep](https://github.com/samber/pg_sleep) - Add pg_sleep and pg_usleep function
* [pg_snakeoil](https://github.com/credativ/pg_snakeoil) - The PostgreSQL Antivirus #pgSnakeOil
* [pg_sortstats](https://github.com/powa-team/pg_sortstats) - Collecting statistics about sorts
* [pg_squeeze](https://github.com/cybertec-postgresql/pg_squeeze) - Automatic bloat clean up
* [pg_sslstatus](https://github.com/mhagander/pg_sslstatus) - View of how SSL is used in the installation
* [pg_stats](https://github.com/s-hironobu/pg_stats) - Customized statistics views
* [pg_stat_kcache](https://github.com/powa-team/pg_stat_kcache) - Gather statistics about physical disk access and CPU consumption
* [pg_stat_monitor](https://github.com/Percona-Lab/pg_stat_monitor) - Statistics collector for PostgreSQL
* [pq_stat_plans](https://github.com/2ndQuadrant/pg_stat_plans) - pg_stat_statements variant that differentiates between query plans
* [pg_stat_sql_plans](https://github.com/legrandlegrand/pg_stat_sql_plans) - Add plan_id column to pg_stat_statements
* [pg_store_plans](https://github.com/ossc-db/pg_store_plans) - Store execution plans
* [pg_strom](https://github.com/kaigai/pg_strom) - FDW module of PostgreSQL using GPU for Asynchronous Super-Parallel Query Execution
* [pg_sulog](https://github.com/nuko-yokohama/pg_sulog) - Superuser logging/blocking
* [pg_terminator](https://gitlab.com/depesz/pg_terminator) - Tool for automatically canceling or terminating offending connections
* [pg_themis](https://github.com/cossacklabs/pg_themis?utm_source=postgresweekly&utm_medium=email) - Encrypting / Decrypting data using the Themis library
* [pg_track_settings](https://github.com/rjuju/pg_track_settings) - Keep track of configuration changes
* [pg_track_slow_queries](https://github.com/julmon/pg_track_slow_queries) - Slow query tracking
* [pg_trgm_pro](https://github.com/postgrespro/pg_trgm_pro) - Text similarity measurement and index searching based on trigrams
* [pg_ulid](https://github.com/iCyberon/pg_ulid) - Universally Unique Lexicographically Sortable Identifier (ULID)
* [pg_wait_sampling](https://github.com/postgrespro/pg_wait_sampling) - Sampling based statistics of wait events
* [pg_xid](https://github.com/iCyberon/pg_xid) - Globally unique id generator
* [pipelinedb](https://github.com/pipelinedb/pipelinedb) - High-performance time-series aggregation for PostgreSQL
* [planfix](https://github.com/srutz/planfix) - Force specific indices
* [planscape_postgres_module](https://github.com/mejedi/planscape-postgresql-module) - Insight into the planning process
* [plpgsql_check](https://github.com/okbob/plpgsql_check) - Linter tool for language PL/pgSQL
* [postgresql-fast-guids](https://github.com/dyninc/postgresql-fast-guid) - Fast GUIDs for PostgreSQL
* [postgresql-hll](https://github.com/citusdata/postgresql-hll) - HyperLogLog data structures as a native data type
* [postgresql-median](https://github.com/clime/postgresql-median) - Median aggregate function
* [postgresql-popcount](https://github.com/eschmar/postgresql-popcount) - Population count function for data type bit(n)
* [postgresql-similarity](https://github.com/urbic/postgresql-similarity) - Functions that calculate the similarity between two strings
* [postgresql-topn](https://github.com/citusdata/postgresql-topn) - Returns the top values in a database according to some criteria
* [postgresql_track_renames](https://github.com/hollobon/postgresql_track_renames) - Tracking object renames in PostgreSQL 9.3+
* [postgres-decoderbufs](https://github.com/debezium/postgres-decoderbufs) - Logical decoder output plugin to deliver data as Protocol Buffers
* [postgres-shacrypt](https://github.com/dverite/postgres-shacrypt) - Generate SHA256-CRYPT and SHA512-CRYPT password hashes
* [postgres_vectorization_test](https://github.com/citusdata/postgres_vectorization_test) - Vectorized executor to speed up PostgreSQL
* [pqc-master](https://github.com/dpaks/pqc-master) - PostgreSQL Query Cache
* [preprepare](https://github.com/dimitri/preprepare) - PostgreSQL prepare statements made pooling friendly
* [quantile](https://github.com/tvondra/quantile) - provides three simple aggregate functions to compute quantiles
* [query_cache](https://github.com/thinkprojectgroup/query_cache) - Query cache to store the result set of queries
* [query_histogram](https://github.com/tvondra/query_histogram) - Simple query execution time histogram for PostgreSQL
* [repack_bgw](https://github.com/reorg/repack_bgw) - Repack background worker for PostgreSQL
* [repl_mon](https://github.com/dev1ant/repl_mon) - Custom background worker for easy replication monitoring
* [rum](https://github.com/postgrespro/rum) - RUM access method - inverted index with additional information in posting lists
* [saio](https://github.com/wulczer/saio) - Join optimisation with Simulated Annealing
* [session_exec](https://github.com/okbob/session_exec) - Introduce login function
* [set_user](https://github.com/pgaudit/set_user) - Allowing privilege escalation with enhanced logging and control
* [short_ids](https://gitlab.com/depesz/short_ids) - Generate safely short, textual ids
* [smlr](https://github.com/jirutka/smlar) - Effective similarity search
* [sql_firewall](https://github.com/uptimejp/sql_firewall) - SQL firewall
* [sr_plan](https://github.com/postgrespro/sr_plan) - Save and restore query plans
* [stat_record](https://github.com/asotolongo/stat_record) - Record database statistics
* [timescaledb](https://github.com/timescale/timescaledb) - Time-series database
* [tinyint-postgresql](https://github.com/umitanuki/tinyint-postgresql) - A tiny int implementation as a data type of PostgreSQL
* [toastinfo](https://github.com/credativ/toastinfo) - Show storage structure of varlena datatypes in PostgreSQL
* [trimmed_aggregates](https://github.com/tvondra/trimmed_aggregates) - Trimmed aggregates for PostgreSQL (average, variance, stddev)
* [tuple_fdw](https://github.com/zilder/tuple_fdw) - POC for a compressed binary file storage foreign data wrapper
* [url_encode](https://github.com/okbob/url_encode) - url_encode, url_decode functions for PostgreSQL
* [versioning](https://gitlab.com/depesz/Versioning) - Versioning of database changes
* [vgram](https://github.com/akorotkov/vgram) - Prototype of V-gram indexing for PostgreSQL
* [vops](https://github.com/postgrespro/vops) - Columnar store
* [walreader](https://github.com/moritetu/walreader) - Read WAL records with sql functions
* [weighted_mean](https://github.com/Kozea/weighted_mean) - A simple weighted mean aggregate function for PostgreSQL
* [wildspeed](https://github.com/postgrespro/wildspeed) - Fast wildcard search for like operator
* [xlogminer](https://github.com/HighgoSoftware/XLogMiner) - Open-Source SQL miner on PostgreSQL WAL log

# Libraries
* [asyncpg](https://github.com/MagicStack/asyncpg/) - A fast PostgreSQL Database Client Library for Python/asyncio
* [libpg_query](https://github.com/lfittl/libpg_query) - C library for accessing the PostgreSQL parser outside of the server environment
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
* [pgstats](https://github.com/gleu/pgstats) - Collects PostgreSQL statistics, and either saves them in CSV files or print them on the stdout
* [pg-tpch](https://github.com/AXLEproject/pg-tpch) - PostgreSQL-compatible TPC-H benchmark, with wrapper scripts for populating data and evaluating performance
* [pg-tpch](https://github.com/sshtmc/pg-tpch) - PostgreSQL-compatible benchmark TPC-H, with some wrapper scripts
* [pg_ash_scripts](https://github.com/pgsentinel/pg_ash_scripts) - Scripts for active session history
* [pg_insights](https://github.com/lob/pg_insights) - SQL for monitoring Postgres database health
* [pg_view](https://github.com/zalando/pg_view) - Detailed, real-time view of your database and system metrics
* [pg_ycsb](https://github.com/postgrespro/pg_ycsb) - YCSB-like benchmark for pgbench
* [postgresql-metrics](https://github.com/spotify/postgresql-metrics) - Tool that extracts and provides metrics
* [postgresql-perf-tools](https://github.com/virtuozzo/postgresql-perf-tools) - Performance Monitoring Tools
* [Queries to monitor postgres](https://github.com/nilenso/postgresql-monitoring)
* [sysbench](https://github.com/akopytov/sysbench) - Scriptable database and system performance benchmark
* [tpch_benchmark](https://github.com/ictlyh/tpch_benchmark) - TPC-H benckmark on Cloudera Impala, PostgreSQL and Citus

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
* [pgagroal](https://github.com/agroal/pgagroal) - High-performance connection pool for PostgreSQL
* [pgBadger](http://pgbadger.darold.net) - Log analyzer
* [pgbouncer](http://www.pgbouncer.org/) - Lightweight connection pooler
* [pgcheck](https://github.com/leapking/pgcheck) - Check data file of PostgreSQL database
* [pgcli](https://github.com/dbcli/pgcli) - CLI with autocompletion and syntax highlighting
* [pgenv](https://github.com/vyegorov/pgenv) - Manage PostgreSQL environment
* [pgio](https://github.com/therealkevinc/pgio) - SLOB method tool
* [pgloader](https://pgloader.io/) - Data loader
* [pgquarrel](https://github.com/eulerto/pgquarrel) - Compares PostgreSQL database schemas (DDL))
* [pgreplay](https://github.com/laurenz/pgreplay) - Replay statements from a log file
* [pgreplay-go](https://github.com/gocardless/pgreplay-go/) - Replay SQL statements at approximately the same rate
* [pgrouter](https://github.com/jhunt/pgrouter) - A router for postgres HA
* [pgsync](https://github.com/ankane/pgsync) - Sync data between databases
* [PgSynchronizer](https://github.com/xba1k/PgSynchronizer) - Tool to synchronize data between PostgreSQL databases
* [pgtransform](https://github.com/facetoe/pgtransform?utm_source=postgresweekly&utm_medium=email) - Tools for comparing and modifying Postgresql databases at scale
* [pg_auto_failover](https://github.com/citusdata/pg_auto_failover) - Service for automated failover and high-availability
* [pg_bulkload](https://github.com/ossc-db/pg_bulkload) - High speed data loading utility for PostgreSQL
* [pg_catcheck](https://github.com/EnterpriseDB/pg_catcheck) - Catalog checker
* [pg_dumpacl](https://github.com/dalibo/pg_dumpacl) - Dumping database creation options
* [pg_filedump](https://github.com/df7cb/pg_filedump) - Low-level examination of tables and indexes
* [pg_flame](https://github.com/mgartner/pg_flame) - Flamegraph generator for explain analyze output
* [pg_hexedit](https://github.com/petergeoghegan/pg_hexedit) - Open data files in a hex editor
* [pg_page_verification](https://github.com/google/pg_page_verification) - Verify checksums on data pages
* [pg_prefaulter](https://github.com/joyent/pg_prefaulter) - Faults pages into shared_buffers or filesystem caches in advance of WAL apply
* [pg_probackup](https://github.com/postgrespro/pg_probackup) - Backup and recovery manager
* [pg_reloaded](https://github.com/zikani03/pg_reloaded) - Restore databases periodically
* [pg_reorg](https://github.com/ossc-db/pg_reorg) - Reorganize tables without keeping locks
* [pg_rman](https://github.com/ossc-db/pg_rman) - Backup and restore management tool
* [pg_stealback](https://github.com/stalkerg/pg_stealback) - Backup and recovery manager for PostgreSQL
* [pg_tail](https://github.com/aaparmeggiani/pg_tail) - tail -f your tables
* [pg_timetable](https://github.com/cybertec-postgresql/pg_timetable) - Advanced scheduling
* [pg_tmp](http://eradman.com/ephemeralpg/) - Run tests on an isolated, temporary PostgreSQL database)
* [piretry](https://dalibo.github.io/pitrery/) - Set of bash scripts to manage Point In Time Recovery (PITR) backups
* [postgresqltuner](https://github.com/jfcoz/postgresqltuner) - Script to analyse your database configuration, and give tuning advice
* [postgres_all_versions](https://github.com/bucardo/postgres_all_versions) - Release notes parser
* [PostgeSQL Anonmyizer](https://gitlab.com/dalibo/postgresql_anonymizer) - Anonymization & Data Masking
* [postgreSQL-Query-Lock-Explainer](https://github.com/AdmTal/PostgreSQL-Query-Lock-Explainer) - Query lock explainer
* [pspg](https://github.com/okbob/pspg) - Unix pager designed to work with tables
* [repmgr](https://repmgr.org/) - Replication manager
* [slony](https://github.com/ssinger/slony1-engine) - Slony replication system for Postgresql
* [stellar](https://github.com/fastmonkeys/stellar) - Fast database snapshot and restore tool for development
* [stolon](https://github.com/sorintlab/stolon) - Cloud native high availability
* [wal-e](https://github.com/wal-e/wal-e) - Continous archiving
* [wal-g](https://github.com/wal-g/wal-g) - Archival and restauration tool
* [yoke](https://github.com/nanopack/yoke) - High-availability cluster with auto-failover and automated cluster recovery
* [xlogdump](https://github.com/snaga/xlogdump) - A tool for extracting data from the PostgreSQL's write ahead logs

# Forks
* [Agensgraph](https://github.com/bitnine-oss/agensgraph) - AgensGraph, a transactional graph database based on PostgreSQL
* [C++ port of postgres](https://github.com/jarulraj/postgresql-cpp)
* [ecpg-readahead](https://github.com/zboszor/ecpg-readahead) - PostgreSQL ECPG client-side cursor caching
* [hippo-postgresql](https://github.com/DataSystemsLab/hippo-postgresql) - Hippo is a fast, yet scalable, sparse database indexing approach
* [postgrespro](https://github.com/postgrespro/postgrespro) - Postgres Professional fork of PostgreSQL
* [postgresql.builtin_pool](https://github.com/postgrespro/postgresql.builtin_pool) - PostgreSQL with built-in connection pooling
* [postgresql.threads](https://github.com/postgrespro/postgresql.pthreads) - Port of postgresql for pthreads
* [postgresql-directio](https://github.com/woonhak/postgresql-directio) - PosgreSQL 9.4.1 with O_DIRECT(DirectIO) support
* [postgresql-NVM-logging](https://github.com/meistervonperf/postgresql-NVM-logging) - NVM logging implementation on postgresql-9.6.0
* [postgres-xl](https://github.com/pharosnet/postgres-xl) - Scalable Open Source PostgreSQL-based Database Cluster
* [zHeap](https://github.com/EnterpriseDB/zheap)

# Development
* [vipsql](https://github.com/martingms/vipsql) - Vim frontend for interacting with psql
* [emacs-config](https://www.postgresql.org/message-id/1342042526.2712.21.camel@vanquo.pezone.net) - Emacs settings for PostgreSQL development
* [gdbpg](https://github.com/tvondra/gdbpg) - GDB command(s) making debugging somewhat easier
* [Postgres bugs](https://granicus.if.org/pgbugs/) - List of current and past bugs
* [Development wiki](https://wiki.postgresql.org/wiki/Developer_and_Contributor_Resources) - Development information
* [Writing Postgres Extensions - the Basics](http://big-elephants.com/2015-10/writing-postgres-extensions-part-i/?utm_source=postgresweekly&utm_medium=email)
* [Writing extensions is fun](https://www.percona.com/blog/2019/04/05/writing-postgresql-extensions-is-fun-c-language/) - Step-by-step guide to developing extensions
* [PostgreSQL: Simple C extension development for a novice user (and performance advantages)](https://www.percona.com/blog/2019/07/31/postgresql-simple-c-extension-development-for-a-novice-user/)
* [pg_plugins](https://github.com/michaelpq/pg_plugins) - Templates for plugins
* [postgresql-extension-example](https://github.com/pkorobeinikov/postgresql-extension-example) - Extension examples
* [Trace Query Processing Internals with Debugger](https://www.highgo.ca/2019/10/03/trace-query-processing-internals-with-debugger/) - Example debugging session to trace a query
* [pgxn-utils](https://github.com/guedes/pgxn-utils) - Tools to create extensions
* [PostgreSQL internals through pictures](http://momjian.us/main/writings/pgsql/internalpics.pdf)
* [A quick look at PostgreSQL source code](http://www.zerobugsandprogramfaster.net/essays/3.html?utm_source=postgresweekly&utm_medium=email)
* [psql-hooks](https://github.com/AmatanHead/psql-hooks) - Unofficial documentation of hooks
* [Hooks-in-PostgreSQL](https://github.com/gleu/Hooks-in-PostgreSQL) - Talk about PostgreSQL hooks
* [PostgreSQL: how to add new keyword to SQL grammar](https://shaplov.livejournal.com/903924.html?utm_source=postgresweekly&utm_medium=email)
* [Bug Squashing with SQLsmith](https://share.credativ.com/~ase/sqlsmith-talk.pdf?utm_source=postgresweekly&utm_medium=email)

# Patches
* [buffer_replacement_policies](https://github.com/chen3593/PostgreSQL) - Adding Alternative buffer replacement policies including LRU, MRU, FIFO
* [BufferReplacement-in-PostgreSQL](https://github.com/Neha34/BufferReplacement-in-PostgreSQL) - Different buffer replacement policies
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
- [A Billion Taxi Rides in PostgreSQL](https://tech.marksblogg.com/billion-nyc-taxi-rides-postgresql.html?utm_source=postgresweekly&utm_medium=email)
- GPU
  - [GPU Accelerated SQL queries with PostgreSQL & PG-Strom](https://blog.openshift.com/gpu-accelerated-sql-queries-with-postgresql-pg-strom-in-openshift-3-10/)
  - [Bringing GPU's to bear on bog standard relational databases](https://www.nextplatform.com/2018/02/26/bringing-gpus-bear-bog-standard-relational-databases/)
- Columnar store
  - [In-memory Column Store](https://www.youtube.com/watch?v=ahMo3kd9_hM) - Fujitsu Columnar and in-memory solution
- LLVM
  - [Pairing LLVM JIT with PostgreSQL can speed up database performance](https://www.phoronix.com/scan.php?page=news_item&px=LLVM-JIT-PostgreSQL&utm_source=postgresweekly&utm_medium=email)
 
## Authentication
- [PostgreSQL administrator account with nologin (recover your postgres role)](https://fluca1978.github.io/2019/06/27/PostgreSQLSingleMode.html)
- [How to upgrade your PostgreSQL passwords to SCRAM](https://info.crunchydata.com/blog/how-to-upgrade-postgresql-passwords-to-scram)
- [pgBouncer and auth pass-thru](https://hunleyd.github.io/posts/pgBouncer-and-auth-pass-thru/)

## Configuration
- [PostgreSQL configuration for humans](https://www.slideshare.net/profyclub_ru/postgresql-configuration-for-humans-alvaro-hernandez-ongres)

## Connection pool
- [The challenges of setting max_connections and why you should use a connection pooler](https://richyen.com/postgres/2019/06/25/pools_arent_just_for_cars.html)
- [Pgpool wiki](https://pgpool.net/mediawiki/index.php/Main_Page)
- [A guide to pgpool for PostgreSQL: Part one](https://severalnines.com/database-blog/guide-pgpool-postgresql-part-one)
- [A guide to pgpool for PostgreSQL: Part two](https://severalnines.com/database-blog/guide-pgpool-postgresql-part-two)

## Constraints
- [Protect your data with PostgreSQL constraints](http://nathanmlong.com/2016/01/protect-your-data-with-postgresql-constraints/?utm_source=postgresweekly&utm_medium=email)

## Customer
- [On Uber's Choice of Databases](https://use-the-index-luke.com/blog/2016-07-29/on-ubers-choice-of-databases?utm_source=postgresweekly&utm_medium=email)
- [Re: Why we lost Uber as a user](https://www.postgresql.org/message-id/5797D5A1.5030009%40agliodbs.com?utm_source=postgresweekly&utm_medium=email)
- [Thoughts on Uber’s list of PostgreSQL limitations](https://www.2ndquadrant.com/en/blog/thoughts-on-ubers-list-of-postgres-limitations/?utm_source=postgresweekly&utm_medium=email)
- [Why Uber Engineering Switched from Postgres to MySQL](https://eng.uber.com/mysql-migration/?utm_source=postgresweekly&utm_medium=email)
- [A PostgreSQL response to Uber](https://thebuild.com/presentations/uber-perconalive-2017.pdf?utm_source=postgresweekly&utm_medium=email)

## Datatypes
- [Tour de (PostgreSQL) data types](https://andreas.scherbaum.la/writings/Tour_de_Data_Types_-_FOSDEM_2017.pdf?utm_source=postgresweekly&utm_medium=email)
- [PostgreSQL interval, date, timestamp and time data types](https://www.2ndquadrant.com/en/blog/know-what-time-it-is/)
- Array
  - [PostgreSQL, the good parts: Arrays](http://blog.ryankelly.us/2016/08/21/postgres-the-good-parts-arrays.html?utm_source=postgresweekly&utm_medium=email)
  - [Array of LIKEs](https://www.cybertec-postgresql.com/en/two-simple-postgres-tips-to-kick-start-year-2017/)
  - [Removing duplicates in a PostgreSQL array](https://medium.com/marmolabs/removing-duplicates-in-a-postgresql-array-c972e4ed3bf0)
- Date / Timestamp
  - [Does anyone really know what time it is?](https://thebuild.com/blog/2018/08/07/does-anyone-really-know-what-time-it-is/)
  - [PostgreSQL Data Types: Date, Timestamp, and Time Zones](https://tapoueh.org/blog/2018/04/postgresql-data-types-date-timestamp-and-time-zones/)
  - [PostgreSQL Date Functions (and 7 ways to use them in business analysis)](https://mode.com/blog/postgres-sql-date-functions?utm_source=postgresweekly&utm_medium=email)
- Timezone
  - [Actually Understanding Timezones in PostgreSQL](http://blog.untrod.com/2016/08/actually-understanding-timezones-in-postgresql.html?utm_source=postgresweekly&utm_medium=email)
- [Using the ltree datatype in PostgreSQL](http://leapfrogonline.io/articles/2015-05-21-postgres-ltree/?utm_source=postgresweekly&utm_medium=email)
  
## ETL
- [Fastest way to load data into PostgreSQL using python](https://hakibenita.com/fast-load-data-python-postgresql)
- [Using COPY in Postgres for importing large CSVs](https://trineo.com/blog/2018/08/using-copy-in-postgres-for-importing-large-csvs)

## Table
- [Heap only table (HOT)](https://github.com/postgres/postgres/blob/master/src/backend/access/heap/README.HOT)
- [PostgreSQL and heap-only-tuples updates - part 1](https://blog.anayrat.info/en/2018/11/12/postgresql-and-heap-only-tuples-updates-part-1/)
- [PostgreSQL and heap-only-tuples updates - part 2](https://blog.anayrat.info/en/2018/11/19/postgresql-and-heap-only-tuples-updates-part-2/)
- [PostgreSQL and heap-only-tuples updates - part 3](https://blog.anayrat.info/en/2018/11/26/postgresql-and-heap-only-tuples-updates-part-3/)
- [Postgresql block internals](https://fritshoogland.wordpress.com/2017/07/01/postgresql-block-internals/)

## Index
- General
  - [Indexes in PostgreSQL — 1](https://habr.com/en/company/postgrespro/blog/441962/)
  - [Index internals](https://www.pgcon.org/2016/schedule/attachments/434_Index-internals-PGCon2016.pdf)
  - [Postgres index types](https://thoughtbot.com/blog/postgres-index-types?utm_source=postgresweekly&utm_medium=email)
- Bloom Index
  - [Bloom Indexes in PostgreSQL](https://www.percona.com/blog/2019/06/14/bloom-indexes-in-postgresql/)
  - [Waiting for 9.6 – bloom index contrib module](https://www.depesz.com/2016/04/11/waiting-for-9-6-bloom-index-contrib-module/?utm_source=postgresweekly&utm_medium=email)
  - [Indexes in PostgreSQL — 10 (Bloom)](https://habr.com/en/company/postgrespro/blog/452968/)
- BRIN Index
  - [BRIN Index for PostgreSQL: Don’t forget the benefits](https://www.percona.com/blog/2019/07/16/brin-index-for-postgresql-dont-forget-the-benefits/)
- GIN index
  - [Indexes in PostgreSQL — 7 (GIN)](https://habr.com/en/company/postgrespro/blog/448746/)
  - [PostgreSQL's indexes - GIN](http://www.louisemeta.com/blog/indexes-gin/)
- Hash index
  - [Hash Indexes on PostgreSQL](http://blog.andrebarbosa.co/hash-indexes-on-postgres/?utm_source=postgresweekly&utm_medium=email)
- "Like"
  - [PgSQL Indexes and "LIKE"](http://blog.cleverelephant.ca/2016/08/pgsql-text-pattern-ops.html?utm_source=postgresweekly&utm_medium=email)
- Covering Index
  - [PostgreSQL 11 highlight - Covering Indexes](https://paquier.xyz/postgresql-2/postgres-11-covering-indexes/)
- Combined Index
  - [Combined indexes vs. separate indexes in PostgreSQL](https://www.cybertec-postgresql.com/en/combined-indexes-vs-separate-indexes-in-postgresql/)
  - [The Multi-Column Index of the mysteries](https://thebuild.com/blog/2016/12/30/the-multi-column-index-of-the-mysteries/)
- Partial index
  - [Unique partial indexes with PostgreSQL](https://medium.com/little-programming-joys/unique-partial-indexes-with-postgresql-86e137905c12)
- [Hypothetical Indexes in PostgreSQL](https://www.percona.com/blog/2019/06/21/hypothetical-indexes-in-postgresql/)
- [Automatic index recommendations in PostgreSQL using pg_qualstats and hypopg](https://www.percona.com/blog/2019/07/22/automatic-index-recommendations-in-postgresql-using-pg_qualstats-and-hypopg/)
- [How to index your database](https://www.xaprb.com/slides/index-postgresql-database-postgresconf-2018/#1)
- [Indexing with PostgreSQL: When less is more](https://medium.com/plangrid-technology/indexing-with-postgres-when-less-is-more-7337d6f09048)

## Sequence
- [Checking the sequences status on a single pass](https://fluca1978.github.io/2019/06/11/SequenceCheck.html)
- [The modern alternative to SERIAL columns](https://postgresweekly.com/issues/311)
- [Generate primary keys (almost) automatically](https://fluca1978.github.io/2019/07/09/GeneratePrimaryKeys.html)
- [An Overview of the Serial Pseudo-Datatype for PostgreSQL](https://severalnines.com/database-blog/overview-serial-pseudo-datatype-postgresql)
- [UUID vs BIGSERIAL for primary keys](https://thebuild.com/blog/2015/10/08/uuid-vs-bigserial-for-primary-keys/?utm_source=postgresweekly&utm_medium=email)
- [FAQ: Using Sequences in PostgreSQL](http://www.neilconway.org/docs/sequences/?utm_source=postgresweekly&utm_medium=email)

## Concurrency
- [Batch Updates and Concurrency](https://tapoueh.org/blog/2018/07/batch-updates-and-concurrency/)

## Transaction
- [SERIALIZABLE in PostgreSQL 11... and beyond](https://write-skew.blogspot.com/2018/05/serializable-in-postgresql-11-and-beyond.html)
- [How to implement autonomous transactions in PostgreSQL](https://www.cybertec-postgresql.com/en/implementing-autonomous-transactions-in-postgres/)
- [idle_in_transaction_session_timeout: Terminating idle transactions in PostgreSQL](https://www.cybertec-postgresql.com/en/idle_in_transaction_session_timeout-terminating-idle-transactions-in-postgresql/)
- [PostgreSQL and per-connection write consistency settings](https://www.compose.com/articles/postgresql-and-per-connection-write-consistency-settings/?utm_source=cooper&utm_medium=banner&utm_campaign=postgresweekly)
- [PostgreSQL Transactions aren’t fully isolated](https://malisper.me/postgres-transactions-arent-fully-isolated/?utm_source=postgresweekly&utm_medium=email)
- [Practical Guide to SQL Transaction Isolation](https://begriffs.com/posts/2017-08-01-practical-guide-sql-isolation.html?utm_source=postgresweekly&utm_medium=email)

## HA
- [Top PG Clustering High Availability (HA) Solutions for PostgreSQL](https://severalnines.com/database-blog/top-pg-clustering-high-availability-ha-solutions-postgresql)
- [Introducing pg_auto_failover: Open source extension for automated failover and high-availability in PostgreSQL](https://cloudblogs.microsoft.com/opensource/2019/05/06/introducing-pg_auto_failover-postgresql-open-source-extension-automated-failover-high-availability/)
- [Introduction to PostgreSQL automatic failover](https://pgstef.github.io/2018/02/07/introduction_to_postgresql_automatic_failover.html)
- [Standby in production: scaling application in the second largest classified site in the world](https://medium.com/avitotech/standby-in-production-scaling-application-in-second-largest-classified-site-in-the-world-97a79a1929de)
- [An introduction to stolon: cloud native PostgreSQL high availability](https://sgotti.dev/post/stolon-introduction/?utm_source=postgresweekly&utm_medium=email)

## Query Planer
- [Debugging the postgres query planer](https://gocardless.com/blog/debugging-the-postgres-query-planner/)
- [An Overview of various auxiliary plan nodes in PostgreSQL](https://severalnines.com/database-blog/overview-various-auxiliary-plan-nodes-postgresql?utm_campaign=Cloud_DR_Campaign_OCT19&utm_content=pg_plan_nodes&utm_medium=Social_Media&utm_source=Twitter)
- [An Overview of Just-in-Time Compilation (JIT) for PostgreSQL](https://severalnines.com/database-blog/overview-just-time-compilation-jit-postgresql)
- [Postgres execution plans — Field glossary](https://medium.com/pgmustard/postgres-execution-plans-field-glossary-bc588340b0db)
- [Bruce Momjian on the Postgres Query Planner](http://www.se-radio.net/2018/06/se-radio-episode-328-bruce-momjian-on-the-postgres-query-planner/)
- [Planning queries involving foreign PostgreSQL tables](http://ashutoshpg.blogspot.com/2018/06/planning-queries-involving-foreign.html)
- [PostgreSQL Extended Statistics](https://fluca1978.github.io/2018/06/28/PostgreSQLExtendedStatistics.html)
- [All you need to know about sorting in PostgreSQL](https://madusudanan.com/blog/all-you-need-to-know-about-sorting-in-postgres/?utm_source=postgresweekly&utm_medium=email)
- [Disabling JOIN re-ordering by Postgres planner](https://www.cybertec-postgresql.com/en/two-simple-postgres-tips-to-kick-start-year-2017/)
- [Speeding up PostgreSQL Index Scans with Index-Only Scans](https://malisper.me/speeding-up-postgres-index-scans-with-index-only-scans/?utm_source=postgresweekly&utm_medium=email)

## Parallel Processing
- [Parallelism in PostgreSQL](https://www.percona.com/blog/2019/07/30/parallelism-in-postgresql/)
- [PostgreSQL 10 Parallel Queries and Performance](https://blog.rustprooflabs.com/2018/02/pg10_parallel_queries)
- [Parallel queries in PostgreSQL](https://www.percona.com/blog/2019/02/21/parallel-queries-in-postgresql/)
- [PostgreSQL 9.6 with parallel query vs. TPC-H](http://rhaas.blogspot.com/2016/04/postgresql-96-with-parallel-query-vs.html?utm_source=postgresweekly&utm_medium=email)
- [PostgreSQL 9.6: Parallel Sequential Scan](https://www.2ndquadrant.com/en/blog/postgresql96-parallel-sequential-scan/?utm_source=postgresweekly&utm_medium=email)
- [PostgreSQL 9.6: Parallel queries](https://blog.rebased.pl/2017/04/24/postgresql-9-6-parallel-queries.html?utm_source=postgresweekly&utm_medium=email)
- [Parallel Query v2](http://rhaas.blogspot.com/2017/03/parallel-query-v2.html?utm_source=postgresweekly&utm_medium=email)

## Distributed Processing
- [High performance distributed DML in Citus](https://www.citusdata.com/blog/2018/07/25/high-performance-distributed-dml/)
- [Queues in PostgeSQL](https://www.pgcon.org/2016/schedule/attachments/414_queues-pgcon-2016.pdf?utm_source=postgresweekly&utm_medium=email)
- [Master-less distributed queue with PG Paxos](https://www.citusdata.com/blog/2016/04/13/masterless-distributed-queue/)
- [Experimenting with scaling and full parallelism in PostgreSQL](https://www.cybertec-postgresql.com/en/experimenting-scaling-full-parallelism-postgresql/)

## Partitioning
- [PostgreSQL 10 Built-in Partitioning](https://www.keithf4.com/postgresql-10-built-in-partitioning/?utm_source=postgresweekly&utm_medium=email)
- [PostgreSQL 11 Partitioning Improvements](https://pgdash.io/blog/partition-postgres-11.html)
- [Partitioning Improvements in PostgreSQL 11](https://www.2ndquadrant.com/en/blog/slides-partitioning-pg-11/)
- [Partition Elimination in PostgreSQL 11](https://www.2ndquadrant.com/en/blog/partition-elimination-postgresql-11/)
- [Declarative data partitioning in PostgreSQL10](https://docs.google.com/presentation/d/136DZZJeVYklEmjl3QoX_-C6NPyMlqmUDuljpO8G8bys/mobilepresent?slide=id.g3a3a36a1fe_0_574)
- [Getting time zones right when setting up PostgreSQL monthly partitioning](https://blog.ondevice.io/2016/11/postgres-partitioning/)

## Sharding
- [An Overview of Sharding in PostgreSQL and How it Relates to MongoDB’s](https://www.percona.com/blog/2019/05/24/an-overview-of-sharding-in-postgresql-and-how-it-relates-to-mongodbs/)
- [Built-in Sharding for PostgreSQL](http://rhaas.blogspot.com/2018/05/built-in-sharding-for-postgresql.html)

## Performance
- [Performance Monitoring & Auditing PostgreSQL - Top Resources](https://severalnines.com/database-blog/performance-monitoring-auditing-postgresql-top-resources)
- [What PostgreSQL tells you about its performance](http://okigiveup.net/what-postgresql-tells-you-about-its-performance/?utm_source=postgresweekly&utm_medium=email)
- [Metrics to Monitor in Your PostgreSQL Database](https://www.influxdata.com/blog/metrics-to-monitor-in-your-postgresql-database/?utm_campaign=postgres&utm_medium=newsletter&utm_source=cooperpress)
- [Key metrics for PostgreSQL monitoring](https://www.datadoghq.com/blog/postgresql-monitoring/)
- [Collecting metrics with PostgreSQL monitoring tools](https://www.datadoghq.com/blog/postgresql-monitoring-tools/)
- [Monitoring CPU and memory usage](https://aaronparecki.com/2015/02/19/8/monitoring-cpu-memory-usage-from-postgres)
- [Monitoring cheatsheet](https://russ.garrett.co.uk/2015/10/02/postgres-monitoring-cheatsheet/)
- [PostgreSQL technical performance presentations](http://momjian.us/main/presentations/performance.html)
- [PostgreSQL Scalability: Towards millions TPS](http://akorotkov.github.io/blog/2016/05/09/scalability-towards-millions-tps/?utm_source=postgresweekly&utm_medium=email)
- [Vertically Scaling PostgreSQL](https://pgdash.io/blog/scaling-postgres.html)
- Benchmark
  - [Tuning PostgreSQL with pgbench](https://blog.codeship.com/tuning-postgresql-with-pgbench/?utm_source=postgresweekly&utm_medium=email)
- Tools
  - [Profiling with perf](https://wiki.postgresql.org/wiki/Profiling_with_perf)
  - [pgCenter’s wait events profiler](https://blog.dataegret.com/2019/03/pgcenters-wait-event-profiler.html)
  - [Announcing pgio](https://kevinclosson.net/2019/09/21/announcing-pgio-the-slob-method-for-postgresql-is-released-under-apache-2-0-and-available-at-github/)
  - [So pgio does not accurately report physical I/O in test results? Buffering buffers, and baffles](https://kevinclosson.net/2019/09/27/so-pgio-does-not-accurately-report-physical-i-o-in-test-results-buffering-buffers-and-baffles/)
  - [Announcing pgmetrics](https://www.opsdash.com/blog/announcing-pgmetrics.html)
  - [pgio / pg_hint_plan / pg_sentinel demo](https://www.youtube.com/watch?v=tMNviAclMKo&feature=youtu.be)
  - [pg_sampletolog: An extension to log a sample of statements](https://blog.anayrat.info/en/2019/01/28/pg_sampletolog-an-extension-to-log-a-sample-of-statements/)
- Memory
  - [Architecture and Tuning of Memory in PostgreSQL Databases](https://severalnines.com/database-blog/architecture-and-tuning-memory-postgresql-databases)
  - [Understanding caching in PostgreSQL - An in-depth guide](https://madusudanan.com/blog/understanding-postgres-caching-in-depth/?utm_source=postgresweekly&utm_medium=email)
  - [Caching in PostgreSQL](https://raghavt.blogspot.com/2012/04/caching-in-postgresql.html)
  - [Locking PostgreSQL shared memory to physical RAM](https://theplateisbad.blogspot.com/2016/11/locking-postgresql-shared-memory-to.html?utm_source=postgresweekly&utm_medium=email)
- Locks
  - [Lock monitoring](https://wiki.postgresql.org/wiki/Lock_Monitoring)
  - [PostgreSQL rocks, except when it blocks: Understanding locks](https://www.citusdata.com/blog/2018/02/15/when-postgresql-blocks/)
  - [When PostgreSQL blocks: 7 tips for dealing with locks](https://www.citusdata.com/blog/2018/02/22/seven-tips-for-dealing-with-postgres-locks/)
  - [How to track long-waiting locks in your database](https://postgresweekly.com/issues/303)
  - [Migrations and long transactions in PostgreSQL](https://www.fin.com/posts/migrations-and-long-transactions-in-postgres/)
  - [Understanding deadlocks in MySQL & PostgreSQL](https://severalnines.com/database-blog/understanding-deadlocks-mysql-postgresql)
  - [Don’t LOCK tables. Just don’t](https://thebuild.com/blog/2018/08/28/dont-lock-tables-just-dont/)
  - [How do PostgreSQL advisory locks work](https://vladmihalcea.com/how-do-postgresql-advisory-locks-work/?utm_source=postgresweekly&utm_medium=email/)
- Queries
  - [3 ways to detect slow queries in PostgreSQL](https://www.cybertec-postgresql.com/en/3-ways-to-detect-slow-queries-in-postgresql/)
  - [Automatically logging slow queries](https://postgresweekly.com/issues/301)
  - [Detecting performance problems easily in PostgreSQL](https://www.cybertec-postgresql.com/en/detecting-performance-problems-easily-in-postgresql/)
  - [Avoiding “OR” for better query peformance](https://www.cybertec-postgresql.com/en/avoid-or-for-better-performance/)
  - [Performance issues with ORed conditions](http://blog.rhodiumtoad.org.uk/2017/01/22/performance-issues-with-ored-conditions/?utm_source=postgresweekly&utm_medium=email)
  - [The most useful Postgres extension: pg_stat_statements](https://www.citusdata.com/blog/2019/02/08/the-most-useful-postgres-extension-pg-stat-statements/)
  - [PostgreSQL Running Slow? Tips & Tricks to get to the source](https://severalnines.com/database-blog/postgresql-running-slow-tips-tricks-get-source)
  - [Explaining the unexplainable](https://www.depesz.com/2013/04/16/explaining-the-unexplainable/)
  - [Explaining explain](https://wiki.postgresql.org/images/4/45/Explaining_EXPLAIN.pdf)
  - [Reading a PostgreSQL explain analyze query plan](https://thoughtbot.com/blog/reading-an-explain-analyze-query-plan?utm_source=postgresweekly&utm_medium=email)
  - [Finding and killing long running queries on PostgreSQL](https://medium.com/little-programming-joys/finding-and-killing-long-running-queries-on-postgres-7c4f0449e86d)
  - [PostrgreSQL: Improving sort performance](https://www.cybertec-postgresql.com/en/postgresql-improving-sort-performance/)
- Stored Procedures
  - [Improving performance with stored procedures — a pgbench example](https://medium.com/@FranckPachot/improving-performance-with-stored-procedures-a-pgbench-example-249a1f6b9f6c)
- Waits
  - [Troubleshooting waits in PostgreSQL](http://amitkapila16.blogspot.com/2016/03/troubleshooting-waits-in-postgresql.html?utm_source=postgresweekly&utm_medium=email)
  - [Monitoring wait events in PostgreSQL 9.6](http://akorotkov.github.io/blog/2016/03/25/wait_monitoring_9_6/?utm_source=postgresweekly&utm_medium=email)
- Trigger
  - [Are trigger really that slow in PostgreSQL?](https://www.cybertec-postgresql.com/en/are-triggers-really-that-slow-in-postgres/)
- Statistics
  - [The PostgreSQL 10 feature you didn't know about: create statistics](https://www.citusdata.com/blog/2018/03/06/postgres-planner-and-its-usage-of-statistics/)
  - [Always Do This #4: Put stats_temp_directory on a memory file system](https://thebuild.com/blog/2016/02/02/always-do-this-4-put-stats_temp_directory-on-a-memory-file-system/?utm_source=postgresweekly&utm_medium=email)
  - [Deep dive into PostgreSQL stats: Introduction](https://blog.dataegret.com/2017/02/deep-dive-into-postgres-stats.html?utm_source=postgresweekly&utm_medium=email?utm_source%3Dpostgresweekly&utm_medium=email)
  - [Deep dive into PostgreSQL stats: pg_stat_activity and pg_locks](https://blog.dataegret.com/2017/10/deep-dive-into-postgres-stats.html)
  - [Deep dive into PostgreSQL stats: pg_stat_user_indexes](https://blog.dataegret.com/2017/05/deep-dive-into-postgres-stats.html)
  - [Deep dive into PostgreSQL stats: pg_stat_all_tables](https://blog.dataegret.com/2017/04/deep-dive-into-postgres-stats_20.html)
  - [Deep dive into postgreSQL stats: pg_stat_bgwriter reports](https://blog.dataegret.com/2017/03/deep-dive-into-postgres-stats_27.html)
  - [Deep dive into PostgreSQL stats: pg_stat_database](https://blog.dataegret.com/2017/02/deep-dive-into-postgres-stats_28.html)
  - [Introduction to pg_stat_activity](https://blog.dataegret.com/2015/11/introduction-to-pgstatactivity.html)
- Checksum
  - [Postgres checksum performance impact](https://www.endpoint.com/blog/2015/12/31/postgres-checksum-performance-impact?utm_source=postgresweekly&utm_medium=email)
- Dynamic tracing
  - [PostgreSQL and SystemTap](https://simply.name/postgresql-and-systemtap.html)
  - [SystemTap for PostgreSQL Toolkit](https://bdrouvot.wordpress.com/2017/11/01/systemtap-for-postgresql-toolkit/)
  - [Dynamic tracing with Postgres](https://paquier.xyz/postgresql-2/postgres-dynamic-tracing/)
  - [Diagnose High-Latency I/O Operations Using SystemTap](https://db-blog.web.cern.ch/blog/luca-canali/2015-07-diagnose-high-latency-io-operations-using-systemtap)
  - [How Long Does It Take to …](https://developers.redhat.com/blog/2013/05/20/how-long-does-it-take-to/)
  - [Adding User Space Probing to an Application (heapsort example)](https://sourceware.org/systemtap/wiki/AddingUserSpaceProbingToApps)
## Recovery
- [How To Back Up, Restore, and Migrate PostgreSQL Databases with Barman on CentOS 7](https://www.digitalocean.com/community/tutorials/how-to-back-up-restore-and-migrate-postgresql-databases-with-barman-on-centos-7?utm_source=postgresweekly&utm_medium=email)
- [pg_wal is too big, what is going on](https://blog.dataegret.com/2018/04/pgwal-is-too-big-whats-going-on.html)
- [Recovery use cases for Logical Replication in PostgreSQL 10](https://medium.com/avitotech/recovery-use-cases-for-logical-replication-in-postgresql-10-a1e6bab03072)
- [Speeding up PostgreSQL restores](https://tech.gadventures.com/speeding-up-postgres-restores-de575149d17a#.55p72yhf7)
- [Recovering PostgreSQL database from disk level corruption](http://www.pateldenish.com/2016/09/recovering-corrupted-postgres-database.html?utm_source=postgresweekly&utm_medium=email)
- [pg_healer: repairing PostgreSQL problems automatically](https://www.endpoint.com/blog/2016/09/19/pghealer-repairing-postgres-problems?utm_source=postgresweekly&utm_medium=email)
- [That Google Checksum Tool](https://thebuild.com/blog/2018/07/17/that-google-checksum-tool/)

## Replication
- [Three Steps to pg_rewind Happiness](https://thebuild.com/blog/2018/08/09/three-steps-to-pg_rewind-happiness/)
- [Converting from asynchronous to synchronous replication in PostgreSQL](https://severalnines.com/database-blog/converting-asynchronous-synchronous-replication-postgresql?utm_campaign=Vendor_Lockin_Campaign_NOV19&utm_content=pg_async_sync&utm_medium=Social_Media&utm_source=Twitter)
- [An overview of logical replication](https://severalnines.com/database-blog/overview-logical-replication-postgresql)
- [PostgreSQL Replication with easy failback](https://www.scalingpostgres.com/tutorials/postgresql-replication-easy-failback/)
- [PostgreSQL Replication failback with pg_rewind](https://www.scalingpostgres.com/tutorials/postgresql-replication-failback-pg-rewind/)
- [pg_rewind and checkpoints: caution!](https://thebuild.com/blog/2018/07/18/pg_rewind-and-checkpoints-caution/)
- [PostgreSQL Replication Monitoring](https://www.scalingpostgres.com/tutorials/postgresql-replication-monitoring/)
- [PostgreSQL replication](https://thebuild.com//presentations/replication-perconalive-2018.pdf)
- [PostgreSQL Streaming Replication - a deep dive](https://severalnines.com/database-blog/postgresql-streaming-replication-deep-dive)
- [High availability and scalable reads in PostgreSQL](https://blog.timescale.com/blog/scalable-postgresql-high-availability-read-scalability-streaming-replication-fb95023e2af/)
- [PostgreSQL Streaming Replication Cheatsheet](https://blog.dataegret.com/2016/01/postgresql-sreaming-replication.html?utm_source=postgresweekly&utm_medium=email?utm_source%3Dpostgresweekly&utm_medium=email)
- [What hot_standby_feedback in PostgreSQL really does](https://www.cybertec-postgresql.com/en/what-hot_standby_feedback-in-postgresql-really-does/)
- [Postgres 10 highlight - Quorum set of synchronous standbys](https://paquier.xyz/postgresql-2/postgres-10-quorum-sync/?utm_source=postgresweekly&utm_medium=email)

## SQL
* [How PostgreSQL’s SQL dialect stays ahead of its competitors](https://modern-sql.com/slides/PG-stays-ahead-20180718.pdf)
* Development
  * [PostgreSQL: A Set of Practices](https://kukuruku.co/post/postgresql-set-of-practices/)
* CTE
  * [Fun with SQL: Common Table Expressions for more readable queries](https://www.citusdata.com/blog/2018/08/09/fun-with-sql-common-table-expressions/)
  * [Fun with SQL: Recursive CTEs in PostgreSQL](https://www.citusdata.com/blog/2018/05/15/fun-with-sql-recursive-ctes/)
  * [Using CTEs and Unions to Compute Running Totals](https://www.periscopedata.com/blog/using-ctes-and-unions-to-compute-running-totals)
* distinct
  * [The many faces of DISTINCT in PostgreSQL](https://medium.com/statuscode/the-many-faces-of-distinct-in-postgresql-c52490de5954)
* filter
  * [The FILTER clause in Postgres 9.4](https://medium.com/little-programming-joys/the-filter-clause-in-postgres-9-4-3dd327d3c852)
* first_value / last_value
  * [Advanced SQL: Why first_value and last_value are no bugs](https://www.cybertec-postgresql.com/en/advanced-sql-why-first_value-and-last_value-are-no-bugs/)
* generate_series
  * [Simple Monthly Reports in PostgreSQL Using generate_series](https://rob.conery.io/2018/08/01/simple-monthly-reports-in-postgresql-using-generate_series/)
* select
  * [Count(*) made fast](https://www.cybertec-postgresql.com/en/postgresql-count-made-fast/)
  * [Selecting a 'sample' of a table's rows](https://postgresweekly.com/issues/300)
  * Window functions
    * [Fun with SQL: Window functions in PostgreSQL](https://www.citusdata.com/blog/2018/06/01/fun-with-sql-window-functions-in-postgresql/)
    * [Window functions in action](https://www.endpoint.com/blog/2013/06/05/window-functions-in-action?utm_source=postgresweekly&utm_medium=email)
    * [PostgreSQL Window Magic](http://momjian.us/main/writings/pgsql/window.pdf?utm_source=postgresweekly&utm_medium=email)
  * Join
    * [PostgreSQL’s lateral Join](https://medium.com/kkempin/postgresqls-lateral-join-bfd6bd0199df)
    * [Postgres Natural joins squash unneeded columns](https://til.hashrocket.com/posts/tyz0whhvc9-postgres-natural-joins-squash-unneeded-columns?utm_source=postgresweekly&utm_medium=email)
  * [Static and dynamic pivots](https://postgresql.verite.pro/blog/2018/06/19/crosstab-pivot.html)
  * [PostgreSQL 11’s Support for SQL Standard GROUPS and EXCLUDE Window Function Clauses](https://blog.jooq.org/2018/07/05/postgresql-11s-support-for-sql-standard-groups-and-exclude-window-function-clauses/)
  * [Custom aggregates in PostgreSQL](https://hashrocket.com/blog/posts/custom-aggregates-in-postgresql?utm_source=postgresweekly&utm_medium=email)
  * [Finding duplicate rows](http://jakeyesbeck.com/2016/02/21/four-postgresql-tips/?utm_source=postgresweekly&utm_medium=email)
  * [Metrics Maven: Calculating a moving average in PostgreSQL](https://www.compose.com/articles/metrics-maven-calculating-a-moving-average-in-postgresql/?utm_source=cooper&utm_medium=postgresql-newsletter&utm_campaign=postgres-moving-average)
  * [Simplifying recursive SQL queries](https://haughtcodeworks.com/blog/software-development/recursive-sql-queries-using-ctes/)
  * [Faster PostgreSQL counting](https://www.citusdata.com/blog/2016/10/12/count-performance/?utm_source=postgresweekly&utm_medium=email)
* Regular expressions
  * [Using regexps in PostgreSQL](https://lerner.co.il/2016/03/01/regexps-in-postgresql/?utm_source=postgresweekly&utm_medium=email)
* Update
  * [What is SKIP LOCKED for in PostgreSQL 9.5?](https://www.2ndquadrant.com/en/blog/what-is-select-skip-locked-for-in-postgresql-9-5/?utm_source=postgresweekly&utm_medium=email)
* Upsert
  * [UPSERT on Postgres 9.5](http://blog.andrebarbosa.co/upsert-on-postgres-9-5/?utm_source=postgresweekly&utm_medium=email)
  * [Upsert Records with PostgreSQL 9.5](https://hashrocket.com/blog/posts/upsert-records-with-postgresql-9-5?utm_source=postgresweekly&utm_medium=email)

## DDL
- [A Missing Link in Postgres 11: Fast Column Creation with Defaults](https://brandur.org/postgres-default)
- [Safe and unsafe operations for high volume PostgreSQL](https://leopard.in.ua/2016/09/20/safe-and-unsafe-operations-postgresql?utm_source=postgresweekly&utm_medium=email#.Xe3gCZNKh-j)

## PGSQL
- [Tech preview: PostgreSQL 11 – create procedure](https://www.cybertec-postgresql.com/en/tech-preview-postgresql-11-create-procedure/)
- [PG Phriday: Getting assertive](http://bonesmoses.org/2017/02/17/pg-phriday-getting-assertive/?utm_source=postgresweekly&utm_medium=email)

## PSQL
- [Tips for psql](https://mccalljt.io/blog/2016/07/psql-tips/?utm_source=postgresweekly&utm_medium=email)
- [psql Tips and Tricks](https://pgdash.io/blog/postgres-psql-tips-tricks.html)
- [Customizing my PostgreSQL Shell](https://www.citusdata.com/blog/2017/07/16/customizing-my-postgres-shell-using-psqlrc/?utm_source=postgresweekly&utm_medium=email)

## Testing
- [How PostgreSQL is tested](https://blog.pgconf.us/2017/02/how-postgresql-is-tested.html?utm_source=postgresweekly&utm_medium=email)

## Fulltext Search (FTS)
- [Full Text Search Made (Almost) Right in PostgreSQL 11](http://akorotkov.github.io/blog/2018/05/21/fulltext-search-made-almost-right/)

## Logging
- [Rules or triggers to log bulk updates?](https://www.cybertec-postgresql.com/en/rules-or-triggers-to-log-bulk-updates/)
- [Analyzing PostgreSQL logs using pgBadger](https://blog.garage-coding.com/2016/07/16/analyzing-postgres-logs-with-pgbadger.html?utm_source=postgresweekly&utm_medium=email)
- [Logging transactions that dropped tables](https://blog.hagander.net/logging-transactions-that-dropped-tables-236/?utm_source=postgresweekly&utm_medium=email)

## Security
- [PostgreSQL Deep Dive: PostgreSQL Defaults and Impact on Security - Part 1](https://info.crunchydata.com/blog/postgresql-defaults-and-impact-on-security-part-1)
- [PostgreSQL Deep Dive: PostgreSQL Defaults and Impact on Security - Part 2](https://info.crunchydata.com/blog/postgresql-defaults-and-impact-on-security-part-2)
- [pgAudit: Auditing database operations part 1](https://info.crunchydata.com/blog/pgaudit-auditing-database-operations-part-1)
- [pgAudit: Auditing database operations part 2](https://info.crunchydata.com/blog/pgaudit-auditing-database-operations-part-2?utm_source=postgresweekly&utm_medium=email)
- [Install PostgreSQL 9.6 with transparent data encyption](https://www.cybertec-postgresql.com/en/install-postgresql-9-6-with-transparent-data-encryption/)
- [Using the CIS PostgreSQL Benchmark to Enhance Your Security](https://info.crunchydata.com/blog/using-the-cis-postgresql-benchmark-to-enhance-your-security)
- [How the CIS Benchmark for PostgreSQL 11 Works](https://info.crunchydata.com/blog/cis-11-benchmark)
- [MitM-ing PostgreSQL](https://thusoy.com/2016/mitming-postgres?utm_source=postgresweekly&utm_medium=email)
- [Securing PostgreSQL](https://thebuild.com/presentations/pgconfeu-2016-securing-postgresql.pdf?utm_source=postgresweekly&utm_medium=email)
- [One-time passwords with Google Authenticator PAM (and friends)](https://theplateisbad.blogspot.com/2016/12/one-time-passwords-with-google.html?utm_source=postgresweekly&utm_medium=email)
- [A Penetration Tester’s Guide to PostgreSQL](https://medium.com/@cryptocracker99/a-penetration-testers-guide-to-postgresql-d78954921ee9)

## Upgrade
- [Near-Zero Downtime Automated Upgrades of PostgreSQL Clusters in Cloud (Part I)](https://www.2ndquadrant.com/en/blog/near-zero-downtime-automated-upgrades-postgresql-clusters-cloud/)
- [Near-Zero Downtime Automated Upgrades of PostgreSQL Clusters in Cloud (Part II)](https://www.2ndquadrant.com/en/blog/near-zero-downtime-automated-upgrades-postgresql-clusters-cloud-part-ii/)
- [PostgreSQL 10 upgrade](https://bricklen.github.io/2018-03-27-Postgres-10-upgrade/)
- [Upgrading PostgreSQL on AWS RDS with minimum or zero downtime](https://medium.com/preply-engineering/postgres-multimaster-34f2446d5e14)

## Migration
- [Oracle to Postgres Conversion](https://wiki.postgresql.org/wiki/Oracle_to_Postgres_Conversion)

## MVCC
- [MVCC and Vaccum](http://rhaas.blogspot.com/2017/12/mvcc-and-vacuum.html)
- [MVCC in PostgreSQL-1. Isolation](https://habr.com/en/company/postgrespro/blog/467437/)
- [Different approaches for MVCC used in well known databases](http://amitkapila16.blogspot.com/2015/03/different-approaches-for-mvcc-used-in.html)
- [PostgreSQL concurrency with MVCC](https://devcenter.heroku.com/articles/postgresql-concurrency)

## Vacuum
- [Tuning Autovacuum in PostgreSQL and Autovacuum Internals](https://www.percona.com/blog/2018/08/10/tuning-autovacuum-in-postgresql-and-autovacuum-internals/)
- [Autovacuum tuning basics](https://www.2ndquadrant.com/en/blog/autovacuum-tuning-basics/?utm_source=postgresweekly&utm_medium=email)
- [Autovacuum slides from PgCon 2018 Ottawa](https://blog.dataegret.com/2018/06/autovacuum-slides-from-pgcon-2018-ottawa.html)
- [Managing Freezing in PostgreSQL	](https://www.2ndquadrant.com/en/blog/managing-freezing/)
- [Monitoring PostgreSQL VACUUM processes](https://www.datadoghq.com/blog/postgresql-vacuum-monitoring/)
- [PostgreSQL Bloatbusters](https://blog.dataegret.com/2018/03/postgresql-bloatbusters.html)
- [PostgreSQL Vacuuming: An introduction for busy devs](http://okigiveup.net/postgresql-vacuuming-an-introduction-for-busy-devs/?utm_source=postgresweekly&utm_medium=email)
- [Postgres adores a Vacuum](https://begriffs.com/posts/2016-04-19-postgres-adores-vacuum.html?utm_source=postgresweekly&utm_medium=email)
- [VACUUM FULL doesn't mean "VACUUM, but better"](http://rhaas.blogspot.com/2014/03/vacuum-full-doesnt-mean-vacuum-but.html)
- [Unclogging the VACUUM](https://thebuild.com/presentations/pgconfeu-2016-vax.pdf?utm_source=postgresweekly&utm_medium=email)
- [Implement an early warning system for transaction ID wraparound in Amazon RDS for PostgreSQL](https://aws.amazon.com/blogs/database/implement-an-early-warning-system-for-transaction-id-wraparound-in-amazon-rds-for-postgresql/?adbsc=social_20161031_67402216&adbid=793131047848321024&adbpl=tw&adbpr=66780587&utm_source=postgresweekly&utm_medium=email)
- [When autovacuum does not vacuum](https://www.2ndquadrant.com/en/blog/when-autovacuum-does-not-vacuum/?utm_source=postgresweekly&utm_medium=email)
- [PostgreSQL Index bloat under a microscope](https://pgeoghegan.blogspot.com/2017/07/postgresql-index-bloat-microscope.html?utm_source=postgresweekly&utm_medium=email)
- [The State of VACUUM](http://rhaas.blogspot.com/2018/01/the-state-of-vacuum.html)
- [DO or UNDO - there is no VACUUM](http://rhaas.blogspot.com/2018/01/do-or-undo-there-is-no-vacuum.html)

## I/O
- [PostgreSQL's fsync() surprise](https://lwn.net/Articles/752063/)
- [Real world SSD wearout](https://blog.okmeter.io/real-world-ssd-wearout-a3396a35c663)
- [On the impact of full-page writes](https://www.2ndquadrant.com/en/blog/on-the-impact-of-full-page-writes/?utm_source=postgresweekly&utm_medium=email)

## Storage
- [Introduction to PostgreSQL physical storage](http://rachbelaid.com/introduction-to-postgres-physical-storage/?utm_source=postgresweekly&utm_medium=email)
- [PostgreSQL and tablespaces, it's not so scary](https://www.cybertec-postgresql.com/en/postgresql-tablespaces-its-not-so-scary/)
- [Pluggable storage discussion](https://www.postgresql.org/message-id/flat/20160812231527.GA690404%40alvherre.pgsql#20160812231527.GA690404@alvherre.pgsql)

## Foreign Data Wrapper
- [A Tour of Foreign Data Wrappers](http://www.craigkerstiens.com/2016/09/11/a-tour-of-fdws/)
- [Foreign Data Wrappers in PostgreSQL and a closer look at postgres_fdw](https://www.percona.com/blog/2018/08/21/foreign-data-wrappers-postgresql-postgres_fdw/)
- [Waiting for PostgreSQL 10 – PostgreSQL_fdw: Push down aggregates to remote servers](https://www.depesz.com/2016/10/25/waiting-for-postgresql-10-postgres_fdw-push-down-aggregates-to-remote-servers/?utm_source=postgresweekly&utm_medium=email)

## Version news
- [What's new in PostgreSQL 9.5](https://wiki.postgresql.org/wiki/What%27s_new_in_PostgreSQL_9.5?utm_source=postgresweekly&utm_medium=email)
- [Postgres 9.5: three little things](https://www.endpoint.com/blog/2016/01/28/postgres-95-three-little-things?utm_source=postgresweekly&utm_medium=email)
- [PostgreSQL 10 New features with examples](https://h50146.www5.hpe.com/products/software/oe/linux/mainstream/support/lcc/pdf/PostgreSQL_10_New_Features_en_20170522-1.pdf?utm_source=postgresweekly&utm_medium=email)
- [Major Features: PostgreSQL 12](http://momjian.us/main/writings/pgsql/features.pdf?utm_source=postgresweekly&utm_medium=email)

## OS
- Linux
  - [Tune linux kernel parameters for PostgreSQL optimization](https://www.percona.com/blog/2018/08/29/tune-linux-kernel-parameters-for-postgresql-optimization/)
  - [How to adjust Linux Out-Of-Memory killer settings for PostgreSQL](https://www.percona.com/blog/2019/08/02/out-of-memory-killer-or-savior/)
  - [Manage linux control groups in PostgreSQL with pg_cgroups](https://www.cybertec-postgresql.com/en/pg_cgroups-linux-control-groups-in-postgresql/)
  - [PostgreSQL vs. Linux kernel versions](https://www.2ndquadrant.com/en/blog/postgresql-vs-kernel-versions/?utm_source=postgresweekly&utm_medium=email)
  - [Diagnostic of an unexpected slowdown](https://rjuju.github.io/postgresql/2018/07/03/diagnostic-of-unexpected-slowdown.html)
  - [Improving Linux system performance with I/O scheduler tuning](https://blog.codeship.com/linux-io-scheduler-tuning/?utm_source=postgresweekly&utm_medium=email)

## Limits
- [PostgreSQL maximum table sizes](https://www.2ndquadrant.com/en/blog/postgresql-maximum-table-size/)

## Cloud
- [Cloud vendor deep-dive: PostgreSQL on AWS Aurora](https://severalnines.com/database-blog/cloud-vendor-deep-dive-postgresql-aws-aurora)
