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
| whyando | input-mattcl | 407.3 ± 168.8 | 0.0 | 741.9 | 1.00 |
| whyando | input-whyando | 414.6 ± 194.7 | 0.0 | 1028.2 | 1.02 ± 0.64 |
| whyando | input-lanjian | 424.2 ± 166.8 | 0.0 | 1027.1 | 1.04 ± 0.59 |
| mattcl | input-mattcl | 668.1 ± 163.6 | 0.0 | 1100.4 | 1.64 ± 0.79 |
| lanjian | input-lanjian | 684.2 ± 150.2 | 0.0 | 1230.2 | 1.68 ± 0.79 |
| mattcl | input-lanjian | 689.7 ± 201.2 | 19.6 | 1265.4 | 1.69 ± 0.86 |
| mattcl | input-whyando | 698.8 ± 172.7 | 0.0 | 1281.6 | 1.72 ± 0.83 |
| lanjian | input-mattcl | 713.1 ± 142.8 | 67.2 | 1158.6 | 1.75 ± 0.81 |
| lanjian | input-whyando | 714.9 ± 143.4 | 268.7 | 1237.8 | 1.76 ± 0.81 |
| kcen | input-mattcl | 831.6 ± 146.2 | 0.0 | 1263.8 | 2.04 ± 0.92 |
| kcen | input-whyando | 855.9 ± 154.1 | 0.0 | 1287.4 | 2.10 ± 0.95 |
| kcen | input-lanjian | 948.2 ± 197.2 | 374.6 | 1533.2 | 2.33 ± 1.08 |
| mattcl-py | input-whyando | 20457.4 ± 597.1 | 19427.3 | 24208.5 | 50.22 ± 20.86 |
| mattcl-py | input-mattcl | 20700.3 ± 576.0 | 19889.7 | 23094.9 | 50.82 ± 21.11 |
| mattcl-py | input-lanjian | 20752.3 ± 623.3 | 19138.2 | 23925.8 | 50.95 ± 21.17 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|