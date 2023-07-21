# GoDis
Implementation if redis-like database in Go that achieves 1 000 000+ GET and SET requests per second on single core. GoDis uses architecture similar to Redis: persistent append only file + snapshots.

# Features
-  Works with Redis Client or nc tool
-  Supports GET and SET
-  Supports TTL for SET
-  DEL command support

