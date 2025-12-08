# Day 7 benchmarks

[link to problem](https://adventofcode.com/2025/day/7)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 7)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-whyando | 332.2 ± 180.3 | 0.0 | 1043.6 | 1.00 |
| whyando | input-mattcl | 333.0 ± 161.6 | 0.0 | 912.3 | 1.00 ± 0.73 |
| whyando | input-lanjian | 348.2 ± 150.8 | 0.0 | 858.2 | 1.05 ± 0.73 |
| mattcl | input-mattcl | 369.3 ± 166.8 | 0.0 | 893.9 | 1.11 ± 0.79 |
| mattcl | input-lanjian | 383.6 ± 160.2 | 0.0 | 985.1 | 1.15 ± 0.79 |
| mattcl | input-whyando | 400.5 ± 174.1 | 0.0 | 1188.2 | 1.21 ± 0.84 |
| kcen | input-whyando | 603.9 ± 295.4 | 0.0 | 1285.7 | 1.82 ± 1.33 |
| kcen | input-mattcl | 808.3 ± 197.2 | 0.0 | 1352.7 | 2.43 ± 1.45 |
| kcen | input-lanjian | 828.5 ± 188.7 | 0.0 | 1406.5 | 2.49 ± 1.47 |
| mattcl-py | input-lanjian | 17330.6 ± 612.0 | 16143.0 | 22315.9 | 52.17 ± 28.38 |
| mattcl-py | input-mattcl | 17411.0 ± 355.6 | 16577.1 | 18611.0 | 52.41 ± 28.47 |
| mattcl-py | input-whyando | 17419.7 ± 661.1 | 16026.7 | 20435.0 | 52.44 ± 28.53 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|