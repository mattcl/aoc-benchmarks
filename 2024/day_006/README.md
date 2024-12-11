# Day 6 benchmarks

[link to problem](https://adventofcode.com/2024/day/6)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 6)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)
- [mikofo](https://github.com/mikofo/aoc2024) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 1.8 ± 0.2 | 1.3 | 2.4 | 1.00 |
| mattcl | input-lanjian | 1.9 ± 0.2 | 1.4 | 2.8 | 1.02 ± 0.19 |
| mattcl | input-kcen | 1.9 ± 0.2 | 1.5 | 2.8 | 1.06 ± 0.18 |
| mattcl | input-mikofo | 2.1 ± 0.2 | 1.7 | 3.2 | 1.14 ± 0.19 |
| lanjian | input-mattcl | 38.0 ± 1.0 | 36.4 | 40.6 | 20.92 ± 2.80 |
| lanjian | input-lanjian | 42.0 ± 1.6 | 40.1 | 51.8 | 23.10 ± 3.15 |
| lanjian | input-kcen | 45.4 ± 1.4 | 43.6 | 52.0 | 24.96 ± 3.35 |
| lanjian | input-mikofo | 63.2 ± 1.2 | 61.4 | 66.1 | 34.75 ± 4.60 |
| mattcl-py | input-mattcl | 94.1 ± 1.2 | 91.7 | 96.2 | 51.76 ± 6.81 |
| mattcl-py | input-lanjian | 101.4 ± 1.6 | 98.5 | 104.6 | 55.77 ± 7.36 |
| mattcl-py | input-kcen | 107.5 ± 1.8 | 104.7 | 111.7 | 59.15 ± 7.81 |
| mattcl-py | input-mikofo | 142.3 ± 2.7 | 139.9 | 151.3 | 78.26 ± 10.36 |
| kcen | input-mattcl | 200.0 ± 3.7 | 191.6 | 205.0 | 110.00 ± 14.55 |
| kcen | input-lanjian | 209.4 ± 3.5 | 204.6 | 215.0 | 115.19 ± 15.21 |
| kcen | input-kcen | 239.3 ± 4.6 | 232.8 | 247.8 | 131.63 ± 17.43 |
| kcen | input-mikofo | 291.8 ± 6.0 | 283.0 | 303.5 | 160.53 ± 21.29 |
| mikofo | input-mattcl | 1370.3 ± 30.9 | 1339.8 | 1401.6 | 753.76 ± 100.19 |
| mikofo | input-lanjian | 1485.5 ± 22.1 | 1462.9 | 1507.2 | 817.14 ± 107.74 |
| mikofo | input-kcen | 1686.5 ± 17.1 | 1667.2 | 1699.6 | 927.71 ± 121.89 |
| mikofo | input-mikofo | 2093.3 ± 39.9 | 2047.3 | 2118.3 | 1151.45 ± 152.43 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|