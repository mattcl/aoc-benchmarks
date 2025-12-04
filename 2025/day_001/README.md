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
| whyando | input-lanjian | 708.5 ± 143.6 | 0.0 | 1074.6 | 1.00 |
| whyando | input-mattcl | 737.7 ± 148.2 | 0.0 | 1368.3 | 1.04 ± 0.30 |
| whyando | input-whyando | 744.7 ± 148.3 | 260.4 | 1189.2 | 1.05 ± 0.30 |
| kcen | input-mattcl | 834.1 ± 178.2 | 265.5 | 1487.0 | 1.18 ± 0.35 |
| kcen | input-lanjian | 837.6 ± 128.1 | 302.6 | 1362.5 | 1.18 ± 0.30 |
| kcen | input-whyando | 856.6 ± 141.4 | 313.8 | 1429.1 | 1.21 ± 0.32 |
| mattcl | input-mattcl | 994.2 ± 160.1 | 432.4 | 1675.8 | 1.40 ± 0.36 |
| mattcl | input-lanjian | 1052.1 ± 194.9 | 346.4 | 1873.6 | 1.49 ± 0.41 |
| mattcl | input-whyando | 1064.1 ± 227.6 | 409.5 | 2673.7 | 1.50 ± 0.44 |
| lanjian | input-lanjian | 1351.2 ± 253.7 | 672.0 | 2517.6 | 1.91 ± 0.53 |
| lanjian | input-whyando | 1365.4 ± 186.1 | 551.7 | 1881.5 | 1.93 ± 0.47 |
| lanjian | input-mattcl | 1369.7 ± 189.6 | 598.8 | 1978.6 | 1.93 ± 0.47 |
| mattcl-py | input-mattcl | 18166.4 ± 500.4 | 17215.7 | 20717.1 | 25.64 ± 5.25 |
| mattcl-py | input-whyando | 18226.1 ± 570.6 | 17254.3 | 21252.9 | 25.73 ± 5.28 |
| mattcl-py | input-lanjian | 18249.4 ± 784.5 | 17263.2 | 21706.7 | 25.76 ± 5.34 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|