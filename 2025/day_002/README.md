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
| whyando | input-whyando | 565.9 ± 142.1 | 67.2 | 924.3 | 1.00 |
| whyando | input-mattcl | 594.1 ± 137.4 | 0.0 | 1049.8 | 1.05 ± 0.36 |
| whyando | input-lanjian | 597.5 ± 151.7 | 0.0 | 1193.7 | 1.06 ± 0.38 |
| kcen | input-lanjian | 808.0 ± 148.3 | 0.0 | 1259.8 | 1.43 ± 0.44 |
| kcen | input-whyando | 813.2 ± 132.4 | 388.5 | 1347.6 | 1.44 ± 0.43 |
| kcen | input-mattcl | 837.6 ± 134.5 | 313.0 | 1281.9 | 1.48 ± 0.44 |
| mattcl | input-whyando | 988.8 ± 171.9 | 0.0 | 1592.7 | 1.75 ± 0.53 |
| mattcl | input-mattcl | 997.9 ± 147.6 | 223.0 | 1591.2 | 1.76 ± 0.51 |
| mattcl | input-lanjian | 1030.8 ± 174.6 | 387.9 | 1721.9 | 1.82 ± 0.55 |
| lanjian | input-whyando | 1107.2 ± 189.7 | 585.5 | 1825.9 | 1.96 ± 0.59 |
| lanjian | input-mattcl | 1168.1 ± 239.7 | 481.3 | 2199.4 | 2.06 ± 0.67 |
| lanjian | input-lanjian | 1215.9 ± 224.4 | 576.6 | 1956.4 | 2.15 ± 0.67 |
| mattcl-py | input-whyando | 20411.8 ± 549.2 | 19360.4 | 23043.0 | 36.07 ± 9.11 |
| mattcl-py | input-lanjian | 20552.0 ± 530.7 | 19236.2 | 22932.4 | 36.32 ± 9.17 |
| mattcl-py | input-mattcl | 20602.0 ± 369.3 | 19696.3 | 22588.1 | 36.41 ± 9.17 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|