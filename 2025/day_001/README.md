# Day 1 benchmarks

[link to problem](https://adventofcode.com/2025/day/1)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 1)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-lanjian | 744.3 ± 142.6 | 68.2 | 1085.6 | 1.00 |
| whyando | input-mattcl | 745.3 ± 139.5 | 175.6 | 1238.0 | 1.00 ± 0.27 |
| whyando | input-whyando | 764.0 ± 152.0 | 117.6 | 1372.8 | 1.03 ± 0.28 |
| kcen | input-mattcl | 831.5 ± 169.7 | 0.0 | 1359.1 | 1.12 ± 0.31 |
| kcen | input-lanjian | 872.0 ± 167.0 | 222.4 | 1607.9 | 1.17 ± 0.32 |
| kcen | input-whyando | 876.5 ± 113.1 | 542.6 | 1465.3 | 1.18 ± 0.27 |
| mattcl | input-mattcl | 1163.5 ± 177.4 | 658.1 | 1869.1 | 1.56 ± 0.38 |
| mattcl | input-whyando | 1187.8 ± 221.4 | 598.4 | 1856.4 | 1.60 ± 0.43 |
| mattcl | input-lanjian | 1221.9 ± 242.2 | 629.3 | 2508.4 | 1.64 ± 0.45 |
| lanjian | input-mattcl | 1279.0 ± 198.1 | 790.8 | 2042.9 | 1.72 ± 0.42 |
| lanjian | input-lanjian | 1307.9 ± 233.7 | 442.7 | 2083.3 | 1.76 ± 0.46 |
| lanjian | input-whyando | 1340.3 ± 206.8 | 608.9 | 2104.4 | 1.80 ± 0.44 |
| mattcl-py | input-mattcl | 18082.6 ± 464.8 | 16812.0 | 20631.1 | 24.30 ± 4.70 |
| mattcl-py | input-whyando | 18193.0 ± 649.1 | 16828.6 | 21430.4 | 24.44 ± 4.76 |
| mattcl-py | input-lanjian | 18217.8 ± 651.9 | 17154.8 | 21353.9 | 24.48 ± 4.77 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|