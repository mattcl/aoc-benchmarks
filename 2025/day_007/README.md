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
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-lanjian | 399.0 ± 156.0 | 0.0 | 1022.5 | 1.00 |
| whyando | input-whyando | 401.3 ± 175.9 | 0.0 | 1038.7 | 1.01 ± 0.59 |
| whyando | input-mattcl | 417.4 ± 150.8 | 0.0 | 943.5 | 1.05 ± 0.56 |
| mattcl | input-whyando | 423.2 ± 190.4 | 0.0 | 1070.4 | 1.06 ± 0.63 |
| mattcl | input-lanjian | 426.0 ± 161.4 | 0.0 | 982.7 | 1.07 ± 0.58 |
| mattcl | input-mattcl | 444.6 ± 157.8 | 0.0 | 998.5 | 1.11 ± 0.59 |
| lanjian | input-whyando | 701.4 ± 118.1 | 308.1 | 931.3 | 1.76 ± 0.75 |
| lanjian | input-lanjian | 711.5 ± 184.5 | 57.3 | 1376.6 | 1.78 ± 0.84 |
| lanjian | input-mattcl | 726.4 ± 142.2 | 260.2 | 1143.8 | 1.82 ± 0.80 |
| kcen | input-lanjian | 900.1 ± 151.2 | 12.8 | 1292.6 | 2.26 ± 0.96 |
| kcen | input-mattcl | 904.2 ± 148.3 | 271.0 | 1478.4 | 2.27 ± 0.96 |
| kcen | input-whyando | 917.9 ± 129.4 | 446.7 | 1343.4 | 2.30 ± 0.96 |
| mattcl-py | input-lanjian | 17401.4 ± 545.4 | 16412.5 | 21009.8 | 43.61 ± 17.11 |
| mattcl-py | input-mattcl | 17440.9 ± 672.0 | 16207.0 | 20333.2 | 43.71 ± 17.17 |
| mattcl-py | input-whyando | 17534.2 ± 685.4 | 16383.1 | 20473.1 | 43.94 ± 17.27 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|