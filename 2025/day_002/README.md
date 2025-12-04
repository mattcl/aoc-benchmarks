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
| whyando | input-lanjian | 515.3 ± 166.7 | 0.0 | 932.4 | 1.00 |
| whyando | input-mattcl | 540.3 ± 157.7 | 0.0 | 945.3 | 1.05 ± 0.46 |
| whyando | input-whyando | 545.7 ± 169.4 | 0.0 | 1148.2 | 1.06 ± 0.47 |
| kcen | input-lanjian | 770.4 ± 111.0 | 116.7 | 1141.9 | 1.50 ± 0.53 |
| kcen | input-mattcl | 818.7 ± 172.6 | 0.0 | 1547.5 | 1.59 ± 0.61 |
| kcen | input-whyando | 836.0 ± 165.1 | 263.1 | 1381.2 | 1.62 ± 0.61 |
| mattcl | input-whyando | 938.1 ± 152.3 | 351.0 | 1492.9 | 1.82 ± 0.66 |
| mattcl | input-lanjian | 939.9 ± 172.5 | 350.7 | 1528.0 | 1.82 ± 0.68 |
| mattcl | input-mattcl | 945.7 ± 137.9 | 385.9 | 1497.7 | 1.84 ± 0.65 |
| lanjian | input-mattcl | 1053.8 ± 186.5 | 451.8 | 1843.6 | 2.05 ± 0.75 |
| lanjian | input-whyando | 1053.9 ± 194.2 | 469.0 | 1976.9 | 2.05 ± 0.76 |
| lanjian | input-lanjian | 1061.0 ± 202.7 | 490.6 | 1766.5 | 2.06 ± 0.77 |
| mattcl-py | input-whyando | 20172.2 ± 574.7 | 19187.6 | 22970.3 | 39.15 ± 12.71 |
| mattcl-py | input-lanjian | 20454.7 ± 663.0 | 19340.0 | 23386.8 | 39.70 ± 12.91 |
| mattcl-py | input-mattcl | 20581.7 ± 694.2 | 19513.6 | 23925.7 | 39.94 ± 12.99 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|