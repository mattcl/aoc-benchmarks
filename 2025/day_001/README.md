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
| whyando | input-whyando | 499.8 ± 183.7 | 0.0 | 1078.2 | 1.00 |
| whyando | input-lanjian | 515.8 ± 193.3 | 0.0 | 1084.6 | 1.03 ± 0.54 |
| whyando | input-mattcl | 538.0 ± 138.4 | 0.0 | 823.1 | 1.08 ± 0.48 |
| mattcl | input-mattcl | 540.2 ± 170.7 | 0.0 | 1083.8 | 1.08 ± 0.52 |
| mattcl | input-lanjian | 552.1 ± 198.1 | 0.0 | 1218.0 | 1.10 ± 0.57 |
| mattcl | input-whyando | 560.4 ± 177.4 | 0.0 | 1084.1 | 1.12 ± 0.54 |
| kcen | input-whyando | 856.0 ± 157.8 | 259.3 | 1263.3 | 1.71 ± 0.70 |
| kcen | input-mattcl | 861.7 ± 140.5 | 384.8 | 1399.7 | 1.72 ± 0.69 |
| kcen | input-lanjian | 864.8 ± 128.8 | 285.8 | 1334.8 | 1.73 ± 0.69 |
| lanjian | input-mattcl | 864.9 ± 156.6 | 250.6 | 1498.5 | 1.73 ± 0.71 |
| lanjian | input-whyando | 880.5 ± 152.6 | 289.2 | 1647.0 | 1.76 ± 0.72 |
| lanjian | input-lanjian | 889.7 ± 148.2 | 298.2 | 1417.9 | 1.78 ± 0.72 |
| mattcl-py | input-lanjian | 18302.2 ± 561.8 | 17253.1 | 21890.6 | 36.62 ± 13.51 |
| mattcl-py | input-whyando | 18321.5 ± 538.4 | 17215.8 | 21780.1 | 36.65 ± 13.52 |
| mattcl-py | input-mattcl | 18358.7 ± 710.6 | 17450.8 | 21640.0 | 36.73 ± 13.57 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|