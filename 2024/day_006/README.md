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
| mattcl | input-mattcl | 1.9 ± 0.3 | 1.4 | 2.8 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.4 | 2.8 | 1.02 ± 0.19 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.5 | 2.5 | 1.03 ± 0.19 |
| mattcl | input-mikofo | 2.1 ± 0.2 | 1.7 | 3.2 | 1.12 ± 0.18 |
| lanjian | input-mattcl | 38.4 ± 0.9 | 36.9 | 41.0 | 20.08 ± 2.74 |
| lanjian | input-lanjian | 42.5 ± 1.1 | 40.5 | 45.5 | 22.20 ± 3.04 |
| lanjian | input-kcen | 45.8 ± 1.1 | 44.3 | 48.8 | 23.95 ± 3.27 |
| lanjian | input-mikofo | 63.7 ± 1.1 | 62.0 | 65.8 | 33.26 ± 4.51 |
| mattcl-py | input-mattcl | 95.6 ± 1.1 | 93.5 | 98.0 | 49.97 ± 6.75 |
| mattcl-py | input-lanjian | 102.3 ± 1.4 | 100.5 | 106.2 | 53.45 ± 7.23 |
| mattcl-py | input-kcen | 109.1 ± 1.4 | 106.8 | 111.3 | 57.02 ± 7.71 |
| mattcl-py | input-mikofo | 145.8 ± 3.6 | 141.2 | 153.2 | 76.21 ± 10.42 |
| kcen | input-mattcl | 199.4 ± 4.3 | 194.1 | 209.0 | 104.20 ± 14.20 |
| kcen | input-lanjian | 209.6 ± 4.2 | 204.3 | 221.0 | 109.51 ± 14.89 |
| kcen | input-kcen | 241.7 ± 4.2 | 236.1 | 250.5 | 126.31 ± 17.13 |
| kcen | input-mikofo | 293.0 ± 6.5 | 286.8 | 303.0 | 153.12 ± 20.88 |
| mikofo | input-mattcl | 1443.1 ± 33.6 | 1406.9 | 1473.3 | 754.11 ± 102.98 |
| mikofo | input-lanjian | 1521.5 ± 11.3 | 1512.5 | 1534.2 | 795.08 ± 107.14 |
| mikofo | input-kcen | 1740.6 ± 33.8 | 1702.1 | 1765.5 | 909.57 ± 123.65 |
| mikofo | input-mikofo | 2151.4 ± 39.8 | 2107.3 | 2184.5 | 1124.27 ± 152.69 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|