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
| whyando | input-mattcl | 405.5 ± 153.9 | 0.0 | 841.5 | 1.00 |
| whyando | input-lanjian | 407.5 ± 151.1 | 0.0 | 993.7 | 1.00 ± 0.53 |
| whyando | input-whyando | 412.4 ± 171.1 | 0.0 | 1681.6 | 1.02 ± 0.57 |
| mattcl | input-lanjian | 612.8 ± 173.4 | 0.0 | 1237.6 | 1.51 ± 0.72 |
| mattcl | input-whyando | 628.5 ± 150.5 | 49.5 | 1071.3 | 1.55 ± 0.70 |
| mattcl | input-mattcl | 660.4 ± 149.5 | 70.7 | 1095.1 | 1.63 ± 0.72 |
| kcen | input-lanjian | 796.4 ± 179.4 | 0.0 | 1436.4 | 1.96 ± 0.87 |
| kcen | input-mattcl | 796.5 ± 132.2 | 320.2 | 1586.7 | 1.96 ± 0.81 |
| kcen | input-whyando | 797.0 ± 154.1 | 286.9 | 1478.2 | 1.97 ± 0.84 |
| lanjian | input-mattcl | 1162.6 ± 214.0 | 655.1 | 2522.7 | 2.87 ± 1.21 |
| lanjian | input-lanjian | 1185.4 ± 213.3 | 497.5 | 1963.3 | 2.92 ± 1.23 |
| lanjian | input-whyando | 1189.3 ± 194.2 | 509.8 | 1856.3 | 2.93 ± 1.21 |
| mattcl-py | input-whyando | 20587.1 ± 753.3 | 19510.1 | 23749.6 | 50.77 ± 19.36 |
| mattcl-py | input-mattcl | 20712.4 ± 613.2 | 19638.8 | 23848.5 | 51.08 ± 19.45 |
| mattcl-py | input-lanjian | 20749.7 ± 652.6 | 19621.8 | 23810.3 | 51.17 ± 19.49 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|