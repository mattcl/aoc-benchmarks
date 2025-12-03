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
| whyando | input-whyando | 516.8 ± 156.4 | 0.0 | 981.0 | 1.00 |
| whyando | input-lanjian | 525.2 ± 163.1 | 0.0 | 1014.0 | 1.02 ± 0.44 |
| whyando | input-mattcl | 551.9 ± 157.8 | 0.0 | 1158.0 | 1.07 ± 0.44 |
| kcen | input-mattcl | 786.3 ± 157.2 | 8.4 | 1156.9 | 1.52 ± 0.55 |
| kcen | input-whyando | 794.9 ± 121.9 | 401.6 | 1174.3 | 1.54 ± 0.52 |
| kcen | input-lanjian | 802.8 ± 122.8 | 206.7 | 1219.2 | 1.55 ± 0.53 |
| mattcl | input-lanjian | 923.6 ± 163.6 | 34.6 | 1451.9 | 1.79 ± 0.63 |
| mattcl | input-whyando | 938.6 ± 137.7 | 332.0 | 1494.0 | 1.82 ± 0.61 |
| mattcl | input-mattcl | 947.2 ± 152.2 | 416.6 | 1501.1 | 1.83 ± 0.63 |
| lanjian | input-mattcl | 1089.6 ± 199.5 | 525.5 | 1798.6 | 2.11 ± 0.75 |
| lanjian | input-lanjian | 1102.1 ± 229.3 | 196.0 | 2897.2 | 2.13 ± 0.78 |
| lanjian | input-whyando | 1152.9 ± 215.0 | 627.8 | 1890.9 | 2.23 ± 0.79 |
| mattcl-py | input-whyando | 20099.2 ± 522.4 | 19257.0 | 23744.5 | 38.89 ± 11.81 |
| mattcl-py | input-lanjian | 20391.6 ± 567.8 | 19487.5 | 23912.8 | 39.46 ± 11.99 |
| mattcl-py | input-mattcl | 20537.5 ± 724.4 | 19367.6 | 23812.0 | 39.74 ± 12.11 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|