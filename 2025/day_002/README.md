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
| whyando | input-lanjian | 371.9 ± 186.7 | 0.0 | 975.7 | 1.00 |
| whyando | input-whyando | 385.5 ± 187.8 | 0.0 | 922.4 | 1.04 ± 0.73 |
| whyando | input-mattcl | 398.0 ± 159.0 | 0.0 | 875.6 | 1.07 ± 0.69 |
| mattcl | input-whyando | 605.2 ± 191.0 | 0.0 | 1056.3 | 1.63 ± 0.96 |
| mattcl | input-lanjian | 622.3 ± 184.8 | 0.0 | 1081.0 | 1.67 ± 0.98 |
| mattcl | input-mattcl | 626.3 ± 163.7 | 106.2 | 1180.9 | 1.68 ± 0.95 |
| kcen | input-whyando | 784.5 ± 184.7 | 0.0 | 1431.0 | 2.11 ± 1.17 |
| lanjian | input-mattcl | 795.2 ± 192.6 | 0.0 | 1353.9 | 2.14 ± 1.19 |
| kcen | input-lanjian | 808.7 ± 137.5 | 0.0 | 1315.4 | 2.17 ± 1.15 |
| kcen | input-mattcl | 814.6 ± 195.7 | 0.0 | 1410.0 | 2.19 ± 1.22 |
| lanjian | input-lanjian | 847.4 ± 155.6 | 0.0 | 1587.1 | 2.28 ± 1.22 |
| lanjian | input-whyando | 847.5 ± 125.9 | 265.7 | 1384.1 | 2.28 ± 1.19 |
| mattcl-py | input-whyando | 20549.1 ± 753.0 | 19293.3 | 23949.6 | 55.26 ± 27.81 |
| mattcl-py | input-mattcl | 20571.0 ± 526.6 | 19515.3 | 22970.4 | 55.32 ± 27.80 |
| mattcl-py | input-lanjian | 20695.3 ± 602.2 | 19622.8 | 23119.3 | 55.65 ± 27.98 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|