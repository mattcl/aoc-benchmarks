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
| mattcl | input-mattcl | 1.9 ± 0.2 | 1.4 | 2.3 | 1.00 |
| mattcl | input-lanjian | 1.9 ± 0.2 | 1.4 | 2.4 | 1.01 ± 0.17 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.5 | 2.6 | 1.05 ± 0.18 |
| mattcl | input-mikofo | 2.1 ± 0.3 | 1.6 | 4.9 | 1.12 ± 0.20 |
| lanjian | input-mattcl | 38.9 ± 1.0 | 37.2 | 42.3 | 20.75 ± 2.51 |
| lanjian | input-lanjian | 42.7 ± 1.1 | 41.3 | 46.0 | 22.79 ± 2.76 |
| lanjian | input-kcen | 46.3 ± 1.2 | 44.3 | 50.3 | 24.74 ± 2.99 |
| lanjian | input-mikofo | 64.2 ± 1.4 | 62.1 | 67.6 | 34.28 ± 4.12 |
| mattcl-py | input-mattcl | 96.2 ± 1.3 | 93.5 | 99.4 | 51.35 ± 6.11 |
| mattcl-py | input-lanjian | 102.8 ± 1.6 | 98.9 | 107.1 | 54.87 ± 6.54 |
| mattcl-py | input-kcen | 109.9 ± 1.5 | 107.7 | 112.8 | 58.69 ± 6.97 |
| mattcl-py | input-mikofo | 145.9 ± 2.5 | 142.9 | 150.5 | 77.91 ± 9.30 |
| kcen | input-mattcl | 200.7 ± 2.7 | 196.1 | 205.3 | 107.15 ± 12.73 |
| kcen | input-lanjian | 210.9 ± 3.0 | 206.4 | 216.7 | 112.62 ± 13.39 |
| kcen | input-kcen | 242.6 ± 4.2 | 236.2 | 248.4 | 129.51 ± 15.45 |
| kcen | input-mikofo | 293.9 ± 3.3 | 288.4 | 298.6 | 156.93 ± 18.61 |
| mikofo | input-mattcl | 1429.9 ± 50.9 | 1374.0 | 1473.5 | 763.41 ± 94.15 |
| mikofo | input-lanjian | 1511.4 ± 47.5 | 1456.9 | 1543.2 | 806.94 ± 98.60 |
| mikofo | input-kcen | 1742.1 ± 63.1 | 1673.4 | 1797.4 | 930.12 ± 114.88 |
| mikofo | input-mikofo | 2110.5 ± 31.0 | 2075.0 | 2132.1 | 1126.78 ± 134.08 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|