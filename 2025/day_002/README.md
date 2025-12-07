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
| whyando | input-whyando | 385.5 ± 168.7 | 0.0 | 905.5 | 1.00 |
| whyando | input-lanjian | 398.8 ± 177.1 | 0.0 | 1041.7 | 1.03 ± 0.64 |
| whyando | input-mattcl | 417.0 ± 182.3 | 0.0 | 1011.3 | 1.08 ± 0.67 |
| mattcl | input-lanjian | 642.7 ± 163.9 | 0.0 | 1139.2 | 1.67 ± 0.84 |
| mattcl | input-mattcl | 648.7 ± 150.0 | 11.0 | 939.5 | 1.68 ± 0.83 |
| mattcl | input-whyando | 652.1 ± 156.3 | 0.0 | 1067.6 | 1.69 ± 0.84 |
| kcen | input-whyando | 802.0 ± 150.3 | 0.0 | 1270.0 | 2.08 ± 0.99 |
| lanjian | input-mattcl | 833.2 ± 136.4 | 269.4 | 1240.6 | 2.16 ± 1.01 |
| lanjian | input-lanjian | 858.6 ± 163.1 | 0.0 | 1336.9 | 2.23 ± 1.06 |
| lanjian | input-whyando | 867.8 ± 164.9 | 0.0 | 1568.3 | 2.25 ± 1.07 |
| kcen | input-lanjian | 892.3 ± 174.8 | 300.8 | 1485.6 | 2.31 ± 1.11 |
| kcen | input-mattcl | 913.7 ± 198.0 | 251.1 | 1561.3 | 2.37 ± 1.16 |
| mattcl-py | input-whyando | 20394.1 ± 569.2 | 19378.7 | 23499.8 | 52.90 ± 23.19 |
| mattcl-py | input-mattcl | 20697.5 ± 612.0 | 19226.3 | 24283.0 | 53.69 ± 23.54 |
| mattcl-py | input-lanjian | 20728.6 ± 591.8 | 19689.6 | 23582.4 | 53.77 ± 23.57 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|