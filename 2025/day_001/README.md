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
| whyando | input-lanjian | 485.6 ± 183.7 | 0.0 | 873.1 | 1.00 |
| whyando | input-mattcl | 505.3 ± 168.6 | 0.0 | 1160.4 | 1.04 ± 0.52 |
| whyando | input-whyando | 522.8 ± 143.0 | 0.0 | 1078.8 | 1.08 ± 0.50 |
| mattcl | input-mattcl | 537.1 ± 156.5 | 0.0 | 779.1 | 1.11 ± 0.53 |
| mattcl | input-lanjian | 552.3 ± 168.9 | 0.0 | 1026.5 | 1.14 ± 0.55 |
| mattcl | input-whyando | 552.4 ± 149.3 | 0.0 | 1077.8 | 1.14 ± 0.53 |
| kcen | input-whyando | 857.6 ± 164.4 | 5.9 | 1400.6 | 1.77 ± 0.75 |
| kcen | input-mattcl | 865.2 ± 156.3 | 267.2 | 1575.9 | 1.78 ± 0.75 |
| kcen | input-lanjian | 906.2 ± 149.5 | 266.1 | 1450.1 | 1.87 ± 0.77 |
| lanjian | input-mattcl | 1123.5 ± 173.7 | 473.0 | 1697.8 | 2.31 ± 0.95 |
| lanjian | input-lanjian | 1147.8 ± 231.4 | 487.2 | 1945.7 | 2.36 ± 1.01 |
| lanjian | input-whyando | 1180.9 ± 236.6 | 502.3 | 2564.4 | 2.43 ± 1.04 |
| mattcl-py | input-mattcl | 18422.7 ± 785.5 | 16954.6 | 21555.0 | 37.94 ± 14.44 |
| mattcl-py | input-lanjian | 18478.6 ± 770.3 | 17086.9 | 21569.5 | 38.05 ± 14.48 |
| mattcl-py | input-whyando | 18481.1 ± 723.5 | 17276.2 | 21411.3 | 38.06 ± 14.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|