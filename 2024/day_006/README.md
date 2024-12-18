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
| mattcl | input-mattcl | 1.9 ± 0.2 | 1.4 | 2.9 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.4 | 2.8 | 1.02 ± 0.18 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.5 | 2.8 | 1.04 ± 0.18 |
| mattcl | input-mikofo | 2.2 ± 0.2 | 1.7 | 3.8 | 1.12 ± 0.18 |
| lanjian | input-mattcl | 41.1 ± 1.0 | 39.6 | 43.8 | 21.19 ± 2.70 |
| lanjian | input-lanjian | 45.1 ± 1.0 | 43.3 | 48.2 | 23.29 ± 2.95 |
| lanjian | input-kcen | 48.6 ± 1.3 | 46.9 | 52.2 | 25.07 ± 3.20 |
| lanjian | input-mikofo | 69.0 ± 1.2 | 67.1 | 71.3 | 35.59 ± 4.48 |
| mattcl-py | input-mattcl | 95.6 ± 1.4 | 92.9 | 99.3 | 49.35 ± 6.20 |
| mattcl-py | input-lanjian | 102.8 ± 1.2 | 100.7 | 105.5 | 53.02 ± 6.65 |
| mattcl-py | input-kcen | 109.7 ± 1.6 | 107.3 | 113.3 | 56.61 ± 7.12 |
| mattcl-py | input-mikofo | 145.5 ± 3.7 | 139.9 | 152.3 | 75.07 ± 9.57 |
| kcen | input-mattcl | 199.4 ± 2.8 | 194.8 | 204.2 | 102.88 ± 12.93 |
| kcen | input-lanjian | 207.3 ± 2.9 | 201.6 | 212.2 | 106.97 ± 13.44 |
| kcen | input-kcen | 241.1 ± 4.2 | 234.9 | 247.6 | 124.39 ± 15.68 |
| kcen | input-mikofo | 293.6 ± 4.5 | 286.4 | 299.7 | 151.45 ± 19.05 |
| mikofo | input-mattcl | 1418.3 ± 43.6 | 1369.4 | 1453.1 | 731.76 ± 94.08 |
| mikofo | input-lanjian | 1541.4 ± 35.4 | 1503.4 | 1573.4 | 795.28 ± 100.95 |
| mikofo | input-kcen | 1741.7 ± 28.6 | 1712.6 | 1769.9 | 898.59 ± 113.15 |
| mikofo | input-mikofo | 2119.0 ± 16.9 | 2099.5 | 2129.7 | 1093.23 ± 136.76 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|