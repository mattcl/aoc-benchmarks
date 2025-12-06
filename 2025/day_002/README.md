# Day 2 benchmarks

[link to problem](https://adventofcode.com/2025/day/2)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 2)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-lanjian | 532.1 ± 168.3 | 0.0 | 1079.8 | 1.00 |
| whyando | input-mattcl | 537.7 ± 168.0 | 0.0 | 1077.4 | 1.01 ± 0.45 |
| whyando | input-whyando | 565.0 ± 124.4 | 54.8 | 922.2 | 1.06 ± 0.41 |
| kcen | input-whyando | 804.2 ± 133.9 | 346.4 | 1220.4 | 1.51 ± 0.54 |
| kcen | input-lanjian | 810.4 ± 126.2 | 410.5 | 1382.8 | 1.52 ± 0.54 |
| kcen | input-mattcl | 822.1 ± 143.7 | 236.0 | 1275.1 | 1.54 ± 0.56 |
| mattcl | input-whyando | 833.1 ± 299.8 | 0.0 | 1405.6 | 1.57 ± 0.75 |
| mattcl | input-mattcl | 967.2 ± 196.4 | 160.3 | 1638.0 | 1.82 ± 0.68 |
| mattcl | input-lanjian | 1016.9 ± 148.2 | 496.9 | 1673.2 | 1.91 ± 0.67 |
| lanjian | input-mattcl | 1093.4 ± 196.6 | 339.8 | 1865.7 | 2.05 ± 0.75 |
| lanjian | input-whyando | 1168.0 ± 225.8 | 443.1 | 1847.1 | 2.19 ± 0.81 |
| lanjian | input-lanjian | 1175.9 ± 222.0 | 527.4 | 1849.5 | 2.21 ± 0.81 |
| mattcl-py | input-whyando | 20493.6 ± 572.9 | 19492.4 | 23187.6 | 38.51 ± 12.23 |
| mattcl-py | input-lanjian | 20691.9 ± 608.0 | 19599.9 | 23515.5 | 38.89 ± 12.35 |
| mattcl-py | input-mattcl | 20777.7 ± 626.3 | 19800.4 | 23714.3 | 39.05 ± 12.41 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|