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
| kcen | input-lanjian | 778.8 ± 354.3 | 107.4 | 1311.8 | 1.00 |
| whyando | input-lanjian | 855.0 ± 183.4 | 137.7 | 1450.6 | 1.10 ± 0.55 |
| whyando | input-whyando | 871.9 ± 184.9 | 94.1 | 1358.2 | 1.12 ± 0.56 |
| whyando | input-mattcl | 896.4 ± 167.4 | 82.8 | 1612.8 | 1.15 ± 0.57 |
| kcen | input-whyando | 1142.5 ± 183.0 | 482.9 | 1657.8 | 1.47 ± 0.71 |
| kcen | input-mattcl | 1181.6 ± 189.4 | 674.8 | 1723.1 | 1.52 ± 0.73 |
| mattcl | input-mattcl | 1240.9 ± 167.9 | 691.3 | 1948.8 | 1.59 ± 0.76 |
| mattcl | input-lanjian | 1277.5 ± 164.1 | 486.8 | 1995.4 | 1.64 ± 0.78 |
| mattcl | input-whyando | 1284.0 ± 172.6 | 846.4 | 1950.5 | 1.65 ± 0.78 |
| lanjian | input-lanjian | 1512.4 ± 296.8 | 411.3 | 2277.2 | 1.94 ± 0.96 |
| lanjian | input-mattcl | 1577.6 ± 238.2 | 562.9 | 2437.6 | 2.03 ± 0.97 |
| lanjian | input-whyando | 1605.9 ± 176.5 | 881.2 | 2181.2 | 2.06 ± 0.96 |
| mattcl-py | input-mattcl | 18497.4 ± 612.5 | 17503.8 | 21381.6 | 23.75 ± 10.83 |
| mattcl-py | input-lanjian | 18531.5 ± 648.7 | 17179.0 | 21767.1 | 23.79 ± 10.86 |
| mattcl-py | input-whyando | 18545.0 ± 561.8 | 17471.5 | 21906.3 | 23.81 ± 10.86 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|