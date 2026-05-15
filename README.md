# @collections/hashbrown — SwissTable Hash Map for Zeta

Auto-converted from [hashbrown](https://crates.io/crates/hashbrown) v0.17.1 via [Dark Factory](https://github.com/murphsicles/dark-factory).

## Features
- **HashMap / HashSet** — drop-in replacements using Google's SwissTable (AA) hash table algorithm
- **Raw entry API** — low-level control over table operations
- **Table API** — generic hash table for custom key/value types
- **Entry API** — `entry()`, `or_insert()`, `and_modify()`, `or_default()`
- **AHash** — high-speed DoS-resistant hashing via `@std/ahash`

## Performance
SwissTable is typically 2-3x faster than Rust's standard `HashMap` for most workloads, with lower memory overhead and better cache locality.

## Stats: ~9,738 lines, 0 unsupported items

## License: MIT