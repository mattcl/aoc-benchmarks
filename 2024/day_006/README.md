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
| mattcl | input-mattcl | 2.1 ± 0.2 | 1.6 | 3.0 | 1.00 |
| mattcl | input-lanjian | 2.1 ± 0.2 | 1.7 | 2.8 | 1.01 ± 0.14 |
| mattcl | input-kcen | 2.2 ± 0.2 | 1.7 | 2.9 | 1.06 ± 0.14 |
| mattcl | input-mikofo | 2.5 ± 0.2 | 2.1 | 4.6 | 1.19 ± 0.17 |
| lanjian | input-mattcl | 38.5 ± 1.0 | 37.1 | 42.3 | 18.62 ± 2.06 |
| lanjian | input-lanjian | 42.5 ± 1.9 | 40.7 | 55.0 | 20.55 ± 2.40 |
| lanjian | input-kcen | 45.8 ± 1.3 | 43.8 | 49.4 | 22.13 ± 2.46 |
| lanjian | input-mikofo | 64.5 ± 1.2 | 62.6 | 67.6 | 31.21 ± 3.40 |
| mattcl-py | input-mattcl | 95.8 ± 1.2 | 93.9 | 98.3 | 46.31 ± 5.01 |
| mattcl-py | input-lanjian | 103.0 ± 2.7 | 99.6 | 113.0 | 49.79 ± 5.51 |
| mattcl-py | input-kcen | 109.5 ± 1.3 | 107.6 | 112.8 | 52.98 ± 5.73 |
| mattcl-py | input-mikofo | 147.7 ± 4.2 | 141.2 | 156.9 | 71.44 ± 7.94 |
| kcen | input-mattcl | 348.7 ± 3.0 | 344.8 | 353.1 | 168.62 ± 18.18 |
| kcen | input-lanjian | 358.8 ± 3.4 | 355.5 | 364.4 | 173.51 ± 18.72 |
| kcen | input-kcen | 409.6 ± 2.9 | 405.1 | 413.7 | 198.10 ± 21.33 |
| kcen | input-mikofo | 534.8 ± 8.4 | 528.3 | 546.4 | 258.65 ± 28.10 |
| mikofo | input-mattcl | 1421.8 ± 29.9 | 1387.4 | 1441.0 | 687.58 ± 75.29 |
| mikofo | input-lanjian | 1521.0 ± 63.7 | 1447.5 | 1560.6 | 735.55 ± 84.84 |
| mikofo | input-kcen | 1723.1 ± 26.4 | 1693.5 | 1744.2 | 833.28 ± 90.46 |
| mikofo | input-mikofo | 2144.1 ± 34.0 | 2122.4 | 2183.3 | 1036.90 ± 112.64 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|