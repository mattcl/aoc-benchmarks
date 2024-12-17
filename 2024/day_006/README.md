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
| mattcl | input-mattcl | 2.0 ± 0.2 | 1.5 | 2.7 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 3.1 | 1.01 ± 0.16 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.5 | 3.6 | 1.04 ± 0.17 |
| mattcl | input-mikofo | 2.2 ± 0.2 | 1.8 | 3.9 | 1.11 ± 0.17 |
| lanjian | input-mattcl | 41.0 ± 1.3 | 38.8 | 47.0 | 20.92 ± 2.43 |
| lanjian | input-lanjian | 44.8 ± 1.3 | 43.0 | 48.9 | 22.86 ± 2.63 |
| lanjian | input-kcen | 48.5 ± 1.4 | 46.2 | 51.5 | 24.74 ± 2.85 |
| lanjian | input-mikofo | 68.5 ± 1.6 | 66.0 | 74.3 | 34.93 ± 3.98 |
| mattcl-py | input-mattcl | 95.2 ± 1.1 | 92.9 | 97.4 | 48.51 ± 5.43 |
| mattcl-py | input-lanjian | 102.9 ± 5.1 | 99.7 | 128.7 | 52.46 ± 6.41 |
| mattcl-py | input-kcen | 109.6 ± 1.8 | 107.0 | 113.0 | 55.88 ± 6.29 |
| mattcl-py | input-mikofo | 145.3 ± 4.2 | 140.5 | 154.2 | 74.08 ± 8.53 |
| kcen | input-mattcl | 197.3 ± 3.7 | 191.2 | 205.4 | 100.58 ± 11.37 |
| kcen | input-lanjian | 204.8 ± 2.7 | 199.9 | 208.6 | 104.39 ± 11.72 |
| kcen | input-kcen | 237.8 ± 3.6 | 233.1 | 245.4 | 121.23 ± 13.63 |
| kcen | input-mikofo | 288.8 ± 6.6 | 279.6 | 301.2 | 147.20 ± 16.75 |
| mikofo | input-mattcl | 1420.9 ± 28.9 | 1387.6 | 1438.1 | 724.31 ± 82.07 |
| mikofo | input-lanjian | 1511.9 ± 32.0 | 1475.0 | 1531.1 | 770.70 ± 87.44 |
| mikofo | input-kcen | 1703.2 ± 25.1 | 1680.7 | 1730.2 | 868.17 ± 97.61 |
| mikofo | input-mikofo | 2114.0 ± 37.8 | 2070.8 | 2141.1 | 1077.59 ± 121.65 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|