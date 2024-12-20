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
| mattcl | input-lanjian | 1.9 ± 0.2 | 1.4 | 2.4 | 1.00 |
| mattcl | input-mattcl | 1.9 ± 0.2 | 1.4 | 2.8 | 1.00 ± 0.17 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.5 | 2.7 | 1.04 ± 0.16 |
| mattcl | input-mikofo | 2.2 ± 0.2 | 1.7 | 3.2 | 1.12 ± 0.16 |
| lanjian | input-mattcl | 41.1 ± 1.5 | 39.2 | 50.2 | 21.23 ± 2.41 |
| lanjian | input-lanjian | 45.0 ± 1.1 | 43.3 | 48.1 | 23.27 ± 2.56 |
| lanjian | input-kcen | 49.0 ± 1.2 | 47.0 | 52.0 | 25.30 ± 2.79 |
| lanjian | input-mikofo | 69.4 ± 1.7 | 66.5 | 74.7 | 35.85 ± 3.95 |
| mattcl-py | input-mattcl | 95.7 ± 1.2 | 92.9 | 97.9 | 49.45 ± 5.35 |
| mattcl-py | input-lanjian | 102.5 ± 1.6 | 99.5 | 105.6 | 52.94 ± 5.75 |
| mattcl-py | input-kcen | 109.3 ± 1.4 | 107.0 | 112.4 | 56.49 ± 6.11 |
| mattcl-py | input-mikofo | 145.9 ± 2.7 | 141.6 | 151.7 | 75.37 ± 8.22 |
| kcen | input-mattcl | 201.3 ± 4.5 | 194.4 | 209.7 | 104.01 ± 11.43 |
| kcen | input-lanjian | 208.0 ± 2.9 | 201.2 | 213.7 | 107.46 ± 11.65 |
| kcen | input-kcen | 241.4 ± 5.4 | 234.5 | 250.2 | 124.73 ± 13.70 |
| kcen | input-mikofo | 293.6 ± 3.5 | 286.0 | 298.5 | 151.72 ± 16.41 |
| mikofo | input-mattcl | 1443.2 ± 55.0 | 1385.5 | 1495.1 | 745.74 ± 85.06 |
| mikofo | input-lanjian | 1513.8 ± 68.8 | 1435.2 | 1563.0 | 782.23 ± 91.29 |
| mikofo | input-kcen | 1739.9 ± 29.6 | 1706.0 | 1760.8 | 899.06 ± 97.86 |
| mikofo | input-mikofo | 2118.7 ± 28.3 | 2088.5 | 2144.5 | 1094.78 ± 118.60 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|