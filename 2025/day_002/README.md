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
| whyando | input-mattcl | 360.0 ± 167.1 | 0.0 | 865.3 | 1.00 |
| whyando | input-lanjian | 366.9 ± 187.3 | 0.0 | 1011.3 | 1.02 ± 0.70 |
| whyando | input-whyando | 390.9 ± 157.7 | 0.0 | 1033.9 | 1.09 ± 0.67 |
| mattcl | input-whyando | 612.2 ± 176.8 | 0.0 | 1281.1 | 1.70 ± 0.93 |
| mattcl | input-mattcl | 631.0 ± 151.3 | 0.0 | 1310.6 | 1.75 ± 0.92 |
| mattcl | input-lanjian | 632.9 ± 133.5 | 0.0 | 1039.5 | 1.76 ± 0.90 |
| kcen | input-mattcl | 769.8 ± 157.6 | 186.3 | 1339.1 | 2.14 ± 1.08 |
| lanjian | input-whyando | 820.6 ± 203.8 | 0.0 | 2794.1 | 2.28 ± 1.20 |
| kcen | input-whyando | 828.2 ± 145.1 | 422.3 | 1561.6 | 2.30 ± 1.14 |
| lanjian | input-lanjian | 835.2 ± 141.1 | 380.9 | 1374.1 | 2.32 ± 1.15 |
| lanjian | input-mattcl | 839.4 ± 142.2 | 0.0 | 1310.0 | 2.33 ± 1.15 |
| kcen | input-lanjian | 866.4 ± 180.2 | 288.4 | 1415.0 | 2.41 ± 1.22 |
| mattcl-py | input-whyando | 20514.7 ± 465.0 | 19477.2 | 23287.7 | 56.99 ± 26.48 |
| mattcl-py | input-lanjian | 20723.7 ± 628.5 | 19606.1 | 23666.9 | 57.57 ± 26.78 |
| mattcl-py | input-mattcl | 20808.9 ± 598.8 | 19785.1 | 23274.1 | 57.81 ± 26.88 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|