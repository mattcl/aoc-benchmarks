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
| mattcl | input-mattcl | 1.9 ± 0.2 | 1.3 | 2.7 | 1.00 |
| mattcl | input-lanjian | 1.9 ± 0.2 | 1.4 | 2.6 | 1.00 ± 0.18 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.4 | 2.7 | 1.03 ± 0.18 |
| mattcl | input-mikofo | 2.1 ± 0.2 | 1.6 | 2.8 | 1.10 ± 0.17 |
| lanjian | input-mattcl | 38.5 ± 1.0 | 36.7 | 41.5 | 20.35 ± 2.58 |
| lanjian | input-lanjian | 42.1 ± 0.9 | 40.3 | 44.6 | 22.26 ± 2.80 |
| lanjian | input-kcen | 45.8 ± 1.2 | 44.0 | 49.8 | 24.22 ± 3.07 |
| lanjian | input-mikofo | 63.1 ± 1.1 | 61.3 | 65.9 | 33.36 ± 4.18 |
| mattcl-py | input-mattcl | 93.9 ± 1.0 | 92.6 | 96.4 | 49.67 ± 6.19 |
| mattcl-py | input-lanjian | 101.1 ± 1.3 | 98.8 | 103.8 | 53.46 ± 6.67 |
| mattcl-py | input-kcen | 109.5 ± 2.6 | 104.9 | 116.3 | 57.90 ± 7.32 |
| mattcl-py | input-mikofo | 143.1 ± 2.8 | 139.4 | 149.6 | 75.70 ± 9.51 |
| kcen | input-mattcl | 202.3 ± 4.7 | 195.0 | 212.3 | 106.99 ± 13.51 |
| kcen | input-lanjian | 212.3 ± 4.1 | 206.0 | 220.4 | 112.25 ± 14.10 |
| kcen | input-kcen | 244.9 ± 5.2 | 235.2 | 252.8 | 129.50 ± 16.31 |
| kcen | input-mikofo | 291.2 ± 4.2 | 283.3 | 298.4 | 154.02 ± 19.25 |
| mikofo | input-mattcl | 1455.0 ± 171.9 | 1355.4 | 1653.5 | 769.51 ± 131.87 |
| mikofo | input-lanjian | 1498.8 ± 47.7 | 1453.5 | 1548.6 | 792.65 ± 101.58 |
| mikofo | input-kcen | 1811.8 ± 21.6 | 1787.9 | 1830.0 | 958.19 ± 119.50 |
| mikofo | input-mikofo | 2060.4 ± 19.8 | 2038.0 | 2075.5 | 1089.66 ± 135.67 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|