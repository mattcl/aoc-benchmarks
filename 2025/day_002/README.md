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
| whyando | input-whyando | 539.3 ± 183.3 | 0.0 | 1022.5 | 1.00 |
| whyando | input-mattcl | 558.4 ± 182.4 | 0.0 | 1022.3 | 1.04 ± 0.49 |
| whyando | input-lanjian | 562.1 ± 183.5 | 0.0 | 1161.0 | 1.04 ± 0.49 |
| kcen | input-mattcl | 811.1 ± 156.5 | 0.0 | 1315.0 | 1.50 ± 0.59 |
| kcen | input-lanjian | 812.1 ± 148.5 | 209.0 | 1249.1 | 1.51 ± 0.58 |
| kcen | input-whyando | 832.0 ± 174.1 | 210.1 | 1661.6 | 1.54 ± 0.62 |
| mattcl | input-mattcl | 951.1 ± 225.0 | 34.9 | 1575.9 | 1.76 ± 0.73 |
| mattcl | input-lanjian | 971.3 ± 135.5 | 488.5 | 1540.3 | 1.80 ± 0.66 |
| mattcl | input-whyando | 1033.7 ± 155.4 | 493.4 | 1678.4 | 1.92 ± 0.71 |
| lanjian | input-mattcl | 1063.1 ± 229.4 | 240.9 | 1811.3 | 1.97 ± 0.79 |
| lanjian | input-lanjian | 1125.4 ± 203.3 | 501.9 | 1955.4 | 2.09 ± 0.80 |
| lanjian | input-whyando | 1204.3 ± 227.2 | 676.4 | 2006.6 | 2.23 ± 0.87 |
| mattcl-py | input-whyando | 20325.3 ± 604.1 | 19395.6 | 23685.1 | 37.69 ± 12.86 |
| mattcl-py | input-lanjian | 20437.1 ± 679.0 | 18973.5 | 23104.1 | 37.90 ± 12.94 |
| mattcl-py | input-mattcl | 20598.9 ± 588.8 | 19636.5 | 23583.6 | 38.20 ± 13.03 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|