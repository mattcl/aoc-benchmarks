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
| whyando | input-whyando | 713.4 ± 158.6 | 0.0 | 1054.8 | 1.00 |
| whyando | input-mattcl | 714.4 ± 170.7 | 181.5 | 1405.1 | 1.00 ± 0.33 |
| whyando | input-lanjian | 719.5 ± 170.6 | 0.0 | 1157.8 | 1.01 ± 0.33 |
| kcen | input-mattcl | 831.4 ± 189.3 | 13.2 | 1387.0 | 1.17 ± 0.37 |
| kcen | input-whyando | 860.2 ± 128.3 | 353.4 | 1345.1 | 1.21 ± 0.32 |
| kcen | input-lanjian | 864.5 ± 148.8 | 338.8 | 1395.5 | 1.21 ± 0.34 |
| mattcl | input-mattcl | 977.6 ± 213.2 | 37.5 | 1719.5 | 1.37 ± 0.43 |
| mattcl | input-lanjian | 1031.2 ± 168.4 | 453.0 | 1740.5 | 1.45 ± 0.40 |
| mattcl | input-whyando | 1077.8 ± 186.6 | 356.1 | 1697.4 | 1.51 ± 0.43 |
| lanjian | input-mattcl | 1310.4 ± 232.6 | 620.6 | 2096.5 | 1.84 ± 0.52 |
| lanjian | input-whyando | 1314.7 ± 228.0 | 545.8 | 2218.0 | 1.84 ± 0.52 |
| lanjian | input-lanjian | 1317.0 ± 223.6 | 604.1 | 2072.9 | 1.85 ± 0.52 |
| mattcl-py | input-whyando | 18256.8 ± 457.9 | 17207.1 | 20755.7 | 25.59 ± 5.72 |
| mattcl-py | input-mattcl | 18271.2 ± 609.7 | 17292.5 | 21663.3 | 25.61 ± 5.76 |
| mattcl-py | input-lanjian | 18341.8 ± 521.6 | 17363.7 | 21243.8 | 25.71 ± 5.76 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|