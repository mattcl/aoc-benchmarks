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
| mattcl | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.7 | 1.00 |
| mattcl | input-lanjian | 2.1 ± 0.2 | 1.6 | 3.1 | 1.02 ± 0.14 |
| mattcl | input-kcen | 2.1 ± 0.2 | 1.8 | 3.0 | 1.06 ± 0.12 |
| mattcl | input-mikofo | 2.5 ± 0.2 | 2.1 | 3.7 | 1.21 ± 0.16 |
| lanjian | input-mattcl | 41.0 ± 1.1 | 39.1 | 44.7 | 20.23 ± 1.79 |
| lanjian | input-lanjian | 45.1 ± 1.2 | 43.0 | 48.2 | 22.22 ± 1.97 |
| lanjian | input-kcen | 48.6 ± 1.2 | 47.0 | 51.7 | 23.96 ± 2.11 |
| lanjian | input-mikofo | 68.8 ± 1.0 | 67.0 | 71.2 | 33.92 ± 2.92 |
| mattcl-py | input-mattcl | 95.5 ± 1.3 | 93.3 | 98.6 | 47.07 ± 4.04 |
| mattcl-py | input-lanjian | 103.1 ± 1.4 | 99.2 | 105.6 | 50.86 ± 4.37 |
| mattcl-py | input-kcen | 108.8 ± 1.3 | 106.1 | 111.8 | 53.67 ± 4.60 |
| mattcl-py | input-mikofo | 146.5 ± 3.0 | 141.7 | 151.2 | 72.25 ± 6.30 |
| kcen | input-mattcl | 345.4 ± 3.9 | 340.9 | 352.9 | 170.29 ± 14.57 |
| kcen | input-lanjian | 356.6 ± 7.4 | 351.3 | 373.7 | 175.81 ± 15.35 |
| kcen | input-kcen | 403.1 ± 5.3 | 396.8 | 410.7 | 198.73 ± 17.05 |
| kcen | input-mikofo | 531.4 ± 6.0 | 525.7 | 538.8 | 262.03 ± 22.42 |
| mikofo | input-mattcl | 1441.4 ± 40.5 | 1396.0 | 1473.6 | 710.69 ± 63.50 |
| mikofo | input-lanjian | 1510.0 ± 43.3 | 1463.7 | 1549.5 | 744.52 ± 66.67 |
| mikofo | input-kcen | 1712.2 ± 42.0 | 1668.6 | 1752.4 | 844.20 ± 74.54 |
| mikofo | input-mikofo | 2129.7 ± 6.4 | 2122.5 | 2134.6 | 1050.05 ± 89.12 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|