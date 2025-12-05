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
| whyando | input-mattcl | 339.5 ± 249.0 | 0.0 | 838.5 | 1.00 |
| kcen | input-whyando | 428.1 ± 326.2 | 0.0 | 1465.7 | 1.26 ± 1.33 |
| whyando | input-lanjian | 542.0 ± 187.5 | 0.0 | 1123.1 | 1.60 ± 1.29 |
| whyando | input-whyando | 551.1 ± 159.4 | 0.0 | 1073.7 | 1.62 ± 1.28 |
| kcen | input-mattcl | 798.4 ± 139.1 | 0.0 | 1422.6 | 2.35 ± 1.77 |
| kcen | input-lanjian | 831.0 ± 160.4 | 0.0 | 1431.3 | 2.45 ± 1.86 |
| mattcl | input-whyando | 954.8 ± 192.3 | 2.3 | 1602.6 | 2.81 ± 2.14 |
| mattcl | input-lanjian | 993.9 ± 135.8 | 510.6 | 1387.3 | 2.93 ± 2.18 |
| mattcl | input-mattcl | 999.0 ± 153.1 | 206.2 | 1558.5 | 2.94 ± 2.20 |
| lanjian | input-whyando | 1045.3 ± 276.2 | 131.7 | 1832.7 | 3.08 ± 2.40 |
| lanjian | input-mattcl | 1137.3 ± 193.6 | 475.5 | 1916.3 | 3.35 ± 2.52 |
| lanjian | input-lanjian | 1140.6 ± 212.4 | 514.4 | 1862.2 | 3.36 ± 2.54 |
| mattcl-py | input-whyando | 20335.8 ± 773.2 | 19004.7 | 23537.5 | 59.90 ± 43.99 |
| mattcl-py | input-lanjian | 20683.9 ± 627.5 | 19763.8 | 23420.5 | 60.93 ± 44.72 |
| mattcl-py | input-mattcl | 20802.6 ± 775.1 | 19650.3 | 26512.4 | 61.28 ± 45.00 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|