# physical-memory-traces
Physical Memory Traces from Sniper

# Git clone and commit
You may need to install git lfs in order to download/upload large traces

# Benchmarks: CPU SPEC 2017
All the benchmarks are comipled with full optimization. For each workload, the first 200 million instructions are fast forwarded and the next 4 billion instructions are simulated in detailed mode.

# System Configuration
We wrote a custom Sniper-sim config file to simulate IBM Power S8 series HPC system.

Processor: 3.32 GHz, 8 cores per socket

Level 1 I/D-cache per core: 128-byte cache block size, 8-way associativity, 32 KB

Level 2 cache per core: 128-byte cache block size, 8-way associativity, 512 KB

Level 3 cache per core: 128-byte cache block size, 16-way associativity, 8 MB

DRAM cache per socket: 128-byte cache block size, 16-way associativity, 64 MB

# Memory Traces:
503.bwaves_r.trace -- 8 copies of 503.bwaves_r running across 8 cores

507.cactusBSSN_r.trace -- 8 copies of 507.cactusBSSN_r running across 8 cores

510.parset_r.trace -- 8 copies of 510.parset_r running across 8 cores

554.roms_r.trace -- 8 copies of 554.roms_r running across 8 cores

557.xz_r.trace -- 8 copies of 557.xz_r running across 8 cores

