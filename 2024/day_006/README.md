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
| mattcl | input-mattcl | 1.9 ± 0.2 | 1.5 | 2.7 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 2.6 | 1.02 ± 0.17 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.5 | 3.1 | 1.04 ± 0.18 |
| mattcl | input-mikofo | 2.2 ± 0.2 | 1.7 | 3.9 | 1.13 ± 0.19 |
| lanjian | input-mattcl | 39.7 ± 1.0 | 38.0 | 42.5 | 20.47 ± 2.58 |
| lanjian | input-lanjian | 43.4 ± 0.9 | 42.3 | 46.7 | 22.39 ± 2.81 |
| lanjian | input-kcen | 47.2 ± 1.6 | 45.4 | 54.9 | 24.36 ± 3.12 |
| mattcl-py | input-mattcl | 57.4 ± 0.7 | 56.2 | 59.7 | 29.61 ± 3.67 |
| mattcl-py | input-lanjian | 58.4 ± 0.7 | 57.1 | 60.0 | 30.16 ± 3.74 |
| mattcl-py | input-kcen | 60.3 ± 0.7 | 58.7 | 61.9 | 31.12 ± 3.86 |
| mattcl-py | input-mikofo | 64.5 ± 0.8 | 62.4 | 66.1 | 33.31 ± 4.13 |
| lanjian | input-mikofo | 66.4 ± 0.9 | 64.9 | 68.4 | 34.27 ± 4.26 |
| kcen | input-mattcl | 196.5 ± 3.9 | 189.8 | 202.6 | 101.39 ± 12.67 |
| kcen | input-lanjian | 204.1 ± 3.3 | 198.7 | 210.5 | 105.35 ± 13.11 |
| kcen | input-kcen | 239.9 ± 4.6 | 232.4 | 245.4 | 123.82 ± 15.46 |
| kcen | input-mikofo | 290.9 ± 5.4 | 281.9 | 297.1 | 150.12 ± 18.74 |
| mikofo | input-mattcl | 1372.3 ± 29.7 | 1353.3 | 1406.6 | 708.21 ± 88.74 |
| mikofo | input-lanjian | 1469.8 ± 47.8 | 1426.8 | 1521.3 | 758.56 ± 96.81 |
| mikofo | input-kcen | 1656.3 ± 26.4 | 1625.9 | 1673.6 | 854.79 ± 106.37 |
| mikofo | input-mikofo | 2069.8 ± 33.6 | 2037.0 | 2104.1 | 1068.22 ± 132.96 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|