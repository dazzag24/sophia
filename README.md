
<p align="center">
	<a href="http://sphia.org"><img src="http://sophia.systems/sophia.png" /></a><br>
</p>
<br>
[Sophia](http://sophia.systems) is advanced transactional [MVCC](http://en.wikipedia.org/wiki/Multiversion_concurrency_control)
key-value/row storage library.

Optimized for Write and Range-Query cases. It can efficiently work with ordered data, such as a time-series,<br>
event-storage, log-storage, server metrics, etc.

**Features**

* Full [ACID](http://en.wikipedia.org/wiki/ACID) compliancy
* [Multi-Version Concurrency Control (MVCC)](http://en.wikipedia.org/wiki/Multiversion_concurrency_control) engine
* Optimistic, non-blocking concurrency with N-writers and M-readers
* Pure Append-Only
* Unique data [storage architecture](http://sophia.systems/v2.1/arch/v12.html)
* Multi-threaded (linear compaction scalability)
* Multi-databases support (sharing a single write-ahead log)
* Secondary indexes
* Multi-Statement and Single-Statement Transactions (cross-database)
* Serialized Snapshot Isolation (SSI)
* Persistent RAM Storage mode
* Anti-Cache Storage mode
* LRU Storage
* AMQ Filter (approximate member query filter) based on Quotient Filter
* Upsert (fast write-only 'update or insert' operation)
* Consistent Cursors
* Prefix search
* Duplicate compression
* Automatic garbage-collection
* Automatic key-expire
* Point-in-Time views
* Online/Versional database creation and asynchronous shutdown/drop
* Asynchronous Online/Hot Backup
* Compression (no fixed-size blocks, no-holes, supported: lz4, zstd)
* Compression for hot and cold data (distinct compression types)
* Optimizations for faster recovery with large datasets (snapshot)
* Easy to use (minimalistic API)
* Easy to write bindings (FFI-friendly)
* Easy to built-in (amalgamated source)
* Implemented as small *C-written* library with zero dependencies
* Carefully tested
* Open Source Software, [*BSD* Licensed](documentation/tutorial/license.md)

**Support**

Sophia [Documentation](http://sophia.systems/v2.1/index.html) and [Bindings](http://sophia.systems/drivers.html)
for the most common languages are available on the [website](http://sophia.systems).

Please use Official Sophia [Google Group](http://groups.google.com/group/sophia-database) or
[StackOverflow](http://stackoverflow.com/tags/sophia) to ask any general questions.<br>
More information is available [Here](http://sophia.systems/support.html).
<br><br>

<a href="https://travis-ci.org/pmwkaa/sophia"><img src="https://travis-ci.org/pmwkaa/sophia.svg?branch=master" /></a>
<a href="https://scan.coverity.com/projects/5109"><img src="https://scan.coverity.com/projects/5109/badge.svg" /></a>
<a href="https://coveralls.io/r/pmwkaa/sophia?branch=master"><img src="https://coveralls.io/repos/pmwkaa/sophia/badge.svg?branch=master" /></a>
