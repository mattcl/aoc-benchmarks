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
| whyando | input-whyando | 496.0 ± 171.1 | 0.0 | 971.9 | 1.00 |
| whyando | input-mattcl | 510.0 ± 178.1 | 0.0 | 1335.2 | 1.03 ± 0.50 |
| whyando | input-lanjian | 528.2 ± 175.4 | 0.0 | 1369.2 | 1.06 ± 0.51 |
| mattcl | input-lanjian | 542.8 ± 165.9 | 0.0 | 1109.6 | 1.09 ± 0.50 |
| mattcl | input-whyando | 544.5 ± 174.0 | 0.0 | 1049.0 | 1.10 ± 0.52 |
| mattcl | input-mattcl | 573.5 ± 156.5 | 0.0 | 1077.1 | 1.16 ± 0.51 |
| kcen | input-mattcl | 854.7 ± 138.9 | 309.0 | 1454.2 | 1.72 ± 0.66 |
| kcen | input-lanjian | 857.8 ± 143.9 | 190.6 | 1333.1 | 1.73 ± 0.66 |
| kcen | input-whyando | 872.0 ± 120.1 | 349.5 | 1314.3 | 1.76 ± 0.65 |
| lanjian | input-mattcl | 1113.2 ± 219.7 | 456.7 | 2516.8 | 2.24 ± 0.89 |
| lanjian | input-lanjian | 1179.2 ± 258.6 | 239.9 | 2030.1 | 2.38 ± 0.97 |
| lanjian | input-whyando | 1199.4 ± 203.8 | 560.7 | 2077.6 | 2.42 ± 0.93 |
| mattcl-py | input-mattcl | 18204.6 ± 549.7 | 17104.3 | 20606.6 | 36.70 ± 12.71 |
| mattcl-py | input-whyando | 18246.2 ± 600.6 | 16870.4 | 21236.9 | 36.79 ± 12.74 |
| mattcl-py | input-lanjian | 18312.4 ± 624.2 | 17214.3 | 21430.1 | 36.92 ± 12.79 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|