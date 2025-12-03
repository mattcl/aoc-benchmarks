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
| whyando | input-whyando | 566.5 ± 190.3 | 0.0 | 1163.5 | 1.00 |
| whyando | input-lanjian | 572.6 ± 141.4 | 25.7 | 1090.1 | 1.01 ± 0.42 |
| whyando | input-mattcl | 592.4 ± 138.5 | 24.4 | 1093.0 | 1.05 ± 0.43 |
| kcen | input-lanjian | 809.4 ± 144.8 | 76.4 | 1307.3 | 1.43 ± 0.54 |
| kcen | input-mattcl | 821.8 ± 129.0 | 321.8 | 1315.8 | 1.45 ± 0.54 |
| kcen | input-whyando | 857.3 ± 138.6 | 336.9 | 1370.0 | 1.51 ± 0.56 |
| mattcl | input-lanjian | 1017.5 ± 188.9 | 76.9 | 1642.8 | 1.80 ± 0.69 |
| mattcl | input-mattcl | 1025.1 ± 176.8 | 489.8 | 1630.3 | 1.81 ± 0.68 |
| lanjian | input-lanjian | 1038.7 ± 154.6 | 461.9 | 1695.0 | 1.83 ± 0.67 |
| lanjian | input-whyando | 1066.9 ± 209.2 | 79.6 | 1752.5 | 1.88 ± 0.73 |
| mattcl | input-whyando | 1070.2 ± 231.6 | 37.3 | 2200.5 | 1.89 ± 0.75 |
| lanjian | input-mattcl | 1088.4 ± 178.2 | 474.3 | 1851.9 | 1.92 ± 0.72 |
| mattcl-py | input-whyando | 20373.7 ± 658.3 | 19232.9 | 23311.0 | 35.96 ± 12.13 |
| mattcl-py | input-lanjian | 20421.3 ± 621.9 | 19102.7 | 23128.4 | 36.05 ± 12.16 |
| mattcl-py | input-mattcl | 20544.8 ± 756.1 | 19207.9 | 23894.1 | 36.26 ± 12.25 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|