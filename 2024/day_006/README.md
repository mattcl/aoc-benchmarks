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
| mattcl | input-mattcl | 2.0 ± 0.2 | 1.6 | 2.5 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.6 | 2.7 | 1.01 ± 0.15 |
| mattcl | input-kcen | 2.1 ± 0.2 | 1.6 | 2.9 | 1.05 ± 0.16 |
| mattcl | input-mikofo | 2.3 ± 0.2 | 1.8 | 3.5 | 1.13 ± 0.16 |
| lanjian | input-mattcl | 41.3 ± 1.4 | 38.9 | 45.7 | 20.46 ± 2.34 |
| lanjian | input-lanjian | 45.5 ± 1.4 | 43.3 | 49.8 | 22.56 ± 2.56 |
| lanjian | input-kcen | 49.2 ± 3.6 | 46.8 | 75.1 | 24.39 ± 3.21 |
| lanjian | input-mikofo | 69.1 ± 1.4 | 66.8 | 73.5 | 34.29 ± 3.81 |
| mattcl-py | input-mattcl | 95.5 ± 1.0 | 93.3 | 98.1 | 47.38 ± 5.20 |
| mattcl-py | input-lanjian | 102.4 ± 1.6 | 99.8 | 105.3 | 50.81 ± 5.61 |
| mattcl-py | input-kcen | 109.0 ± 1.3 | 106.3 | 110.7 | 54.07 ± 5.94 |
| mattcl-py | input-mikofo | 145.6 ± 3.1 | 142.1 | 152.1 | 72.23 ± 8.04 |
| kcen | input-mattcl | 198.1 ± 2.4 | 194.6 | 203.1 | 98.27 ± 10.80 |
| kcen | input-lanjian | 206.3 ± 5.4 | 198.5 | 214.7 | 102.32 ± 11.50 |
| kcen | input-kcen | 237.8 ± 3.7 | 229.4 | 246.0 | 117.95 ± 13.02 |
| kcen | input-mikofo | 292.5 ± 4.6 | 284.4 | 300.3 | 145.10 ± 16.02 |
| mikofo | input-mattcl | 1431.3 ± 34.0 | 1396.2 | 1464.0 | 710.00 ± 79.40 |
| mikofo | input-lanjian | 1541.4 ± 68.4 | 1462.4 | 1582.5 | 764.60 ± 90.18 |
| mikofo | input-kcen | 1738.4 ± 56.5 | 1678.5 | 1790.7 | 862.32 ± 98.32 |
| mikofo | input-mikofo | 2134.0 ± 20.9 | 2114.6 | 2156.1 | 1058.59 ± 116.15 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|