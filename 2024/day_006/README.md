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
| mattcl | input-mattcl | 2.0 ± 0.2 | 1.5 | 2.8 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 2.9 | 1.00 ± 0.17 |
| mattcl | input-kcen | 2.1 ± 0.3 | 1.6 | 3.3 | 1.04 ± 0.17 |
| mattcl | input-mikofo | 2.2 ± 0.2 | 1.8 | 3.1 | 1.12 ± 0.16 |
| lanjian | input-mattcl | 41.0 ± 1.4 | 39.3 | 45.9 | 20.70 ± 2.48 |
| lanjian | input-lanjian | 45.4 ± 1.2 | 43.5 | 48.4 | 22.88 ± 2.70 |
| lanjian | input-kcen | 48.9 ± 1.2 | 46.8 | 51.8 | 24.65 ± 2.89 |
| lanjian | input-mikofo | 68.7 ± 1.7 | 66.4 | 74.3 | 34.64 ± 4.06 |
| mattcl-py | input-mattcl | 95.7 ± 0.9 | 94.1 | 97.3 | 48.27 ± 5.56 |
| mattcl-py | input-lanjian | 102.8 ± 1.3 | 100.0 | 105.8 | 51.87 ± 5.99 |
| mattcl-py | input-kcen | 110.0 ± 2.0 | 107.0 | 113.5 | 55.51 ± 6.44 |
| mattcl-py | input-mikofo | 145.7 ± 3.6 | 141.2 | 153.6 | 73.50 ± 8.62 |
| kcen | input-mattcl | 197.4 ± 2.5 | 191.6 | 202.0 | 99.55 ± 11.49 |
| kcen | input-lanjian | 208.9 ± 5.1 | 204.0 | 220.7 | 105.35 ± 12.36 |
| kcen | input-kcen | 240.8 ± 4.7 | 234.1 | 250.1 | 121.46 ± 14.13 |
| kcen | input-mikofo | 292.8 ± 3.6 | 287.1 | 300.5 | 147.68 ± 17.04 |
| mikofo | input-mattcl | 1426.0 ± 48.4 | 1382.2 | 1478.0 | 719.26 ± 86.04 |
| mikofo | input-lanjian | 1497.9 ± 34.8 | 1457.9 | 1521.9 | 755.49 ± 88.42 |
| mikofo | input-kcen | 1722.2 ± 51.4 | 1662.9 | 1755.0 | 868.65 ± 102.96 |
| mikofo | input-mikofo | 2125.2 ± 6.8 | 2117.4 | 2129.3 | 1071.94 ± 123.00 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|