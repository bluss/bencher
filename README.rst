

A port of the libtest (unstable Rust) benchmark runner to Rust stable releases.
Supports running benchmarks and filtering based on the name. Benchmark
execution works exactly the same way and no more (caveat: black_box is still
missing!).

Please read the `API documentation here`__ (it includes a usage example).

__ https://bluss.github.io/bencher/

**NOTE: Don't forget to compile in release mode**.

Recent Changes
--------------

- 0.1.0

Authors
-------

Principal authors of the benchmark and statistics code in the Rust project are:

+ Brian Anderson
+ Graydon Hoare

Very very many have contributed to lib.rs and stats.rs however, so author
credit is due to:

+ The Rust Project Developers

License
-------

Dual-licensed just like the Rust project.

Licensed under the Apache License, Version 2.0
http://www.apache.org/licenses/LICENSE-2.0 or the MIT license
http://opensource.org/licenses/MIT, at your
option. This file may not be copied, modified, or distributed
except according to those terms.
