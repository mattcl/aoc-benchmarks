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
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.4 | 2.7 | 1.00 |
| mattcl | input-mattcl | 2.0 ± 0.4 | 1.5 | 5.5 | 1.04 ± 0.24 |
| mattcl | input-kcen | 2.1 ± 0.3 | 1.6 | 4.3 | 1.05 ± 0.19 |
| mattcl | input-mikofo | 2.2 ± 0.2 | 1.8 | 3.1 | 1.12 ± 0.17 |
| lanjian | input-mattcl | 39.7 ± 2.3 | 38.1 | 56.3 | 20.23 ± 2.76 |
| lanjian | input-lanjian | 43.9 ± 1.4 | 41.9 | 48.9 | 22.33 ± 2.85 |
| lanjian | input-kcen | 47.3 ± 1.1 | 45.7 | 51.0 | 24.10 ± 3.04 |
| mattcl-py | input-mattcl | 57.6 ± 0.8 | 56.3 | 60.0 | 29.31 ± 3.65 |
| mattcl-py | input-lanjian | 58.2 ± 0.5 | 57.3 | 59.6 | 29.61 ± 3.68 |
| mattcl-py | input-kcen | 61.0 ± 1.5 | 58.8 | 65.6 | 31.04 ± 3.93 |
| mattcl-py | input-mikofo | 64.8 ± 0.8 | 63.0 | 67.8 | 32.98 ± 4.11 |
| lanjian | input-mikofo | 65.9 ± 1.1 | 64.0 | 68.9 | 33.54 ± 4.20 |
| kcen | input-mattcl | 199.5 ± 2.7 | 195.0 | 204.8 | 101.56 ± 12.67 |
| kcen | input-lanjian | 208.8 ± 4.5 | 202.4 | 216.8 | 106.31 ± 13.38 |
| kcen | input-kcen | 242.1 ± 7.4 | 233.2 | 253.5 | 123.24 ± 15.74 |
| kcen | input-mikofo | 291.7 ± 7.4 | 281.1 | 303.6 | 148.50 ± 18.79 |
| mikofo | input-mattcl | 1359.4 ± 43.6 | 1326.8 | 1408.9 | 691.99 ± 88.63 |
| mikofo | input-lanjian | 1462.3 ± 40.7 | 1416.0 | 1492.2 | 744.42 ± 94.61 |
| mikofo | input-kcen | 1683.2 ± 32.6 | 1653.3 | 1717.9 | 856.85 ± 107.54 |
| mikofo | input-mikofo | 2031.4 ± 26.8 | 2000.7 | 2049.8 | 1034.12 ± 128.96 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|