# ⏱️ 06. Benchmark-Driven Optimization Loop

Never guess where bottlenecks are. Optimization without profiling is malpractice.

```mermaid
flowchart TD
    B1["1. Baseline Benchmark<br/>(Measure ops/sec, latency p99, RAM)"] -->
    B2["2. Profile CPU / Memory / Allocations<br/>(cProfile, flamegraphs, memory_profiler)"] -->
    B3["3. Targeted Surgical Optimization<br/>(Vectorization, zero-copy, caching)"] -->
    B4["4. Verification Benchmark<br/>(Statistically prove improvement >25%)"]
```

Accept optimizations ONLY when empirical benchmark logs prove measurable gain.
