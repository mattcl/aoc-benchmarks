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
| whyando | input-mattcl | 553.6 ± 178.6 | 0.0 | 1096.7 | 1.00 |
| whyando | input-lanjian | 570.6 ± 210.9 | 0.0 | 2868.1 | 1.03 ± 0.51 |
| whyando | input-whyando | 600.5 ± 165.2 | 35.8 | 1096.9 | 1.08 ± 0.46 |
| kcen | input-lanjian | 785.0 ± 123.8 | 248.9 | 1321.3 | 1.42 ± 0.51 |
| kcen | input-mattcl | 786.4 ± 146.2 | 0.0 | 1226.3 | 1.42 ± 0.53 |
| kcen | input-whyando | 840.1 ± 178.6 | 0.9 | 1432.1 | 1.52 ± 0.59 |
| mattcl | input-lanjian | 954.3 ± 165.9 | 381.4 | 1582.0 | 1.72 ± 0.63 |
| mattcl | input-mattcl | 986.7 ± 155.8 | 413.4 | 1798.6 | 1.78 ± 0.64 |
| mattcl | input-whyando | 1014.8 ± 168.2 | 401.2 | 1602.1 | 1.83 ± 0.66 |
| lanjian | input-mattcl | 1077.4 ± 164.0 | 502.2 | 1778.4 | 1.95 ± 0.69 |
| lanjian | input-lanjian | 1087.7 ± 213.3 | 296.7 | 1809.8 | 1.96 ± 0.74 |
| lanjian | input-whyando | 1092.1 ± 166.4 | 406.4 | 1745.6 | 1.97 ± 0.70 |
| mattcl-py | input-whyando | 20118.2 ± 449.9 | 18997.9 | 21603.1 | 36.34 ± 11.75 |
| mattcl-py | input-lanjian | 20554.8 ± 695.0 | 19686.8 | 23383.6 | 37.13 ± 12.05 |
| mattcl-py | input-mattcl | 20651.6 ± 718.5 | 19666.3 | 23725.7 | 37.31 ± 12.11 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|