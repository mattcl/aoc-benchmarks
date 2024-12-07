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
| mattcl | input-lanjian | 2.1 ± 0.2 | 1.6 | 2.6 | 1.00 |
| mattcl | input-mattcl | 2.1 ± 0.3 | 1.6 | 3.4 | 1.02 ± 0.15 |
| mattcl | input-kcen | 2.2 ± 0.2 | 1.7 | 3.2 | 1.06 ± 0.13 |
| mattcl | input-mikofo | 2.5 ± 0.3 | 2.2 | 4.7 | 1.21 ± 0.16 |
| lanjian | input-mattcl | 40.9 ± 1.0 | 39.1 | 43.7 | 19.71 ± 1.52 |
| lanjian | input-lanjian | 45.2 ± 1.0 | 42.9 | 47.8 | 21.79 ± 1.65 |
| lanjian | input-kcen | 48.8 ± 1.1 | 46.8 | 51.9 | 23.52 ± 1.79 |
| lanjian | input-mikofo | 68.9 ± 0.9 | 66.7 | 70.7 | 33.21 ± 2.46 |
| mattcl-py | input-mattcl | 95.5 ± 1.1 | 93.1 | 97.8 | 46.05 ± 3.39 |
| mattcl-py | input-lanjian | 102.3 ± 1.0 | 100.0 | 104.0 | 49.34 ± 3.62 |
| mattcl-py | input-kcen | 108.7 ± 1.2 | 106.0 | 111.5 | 52.42 ± 3.86 |
| mattcl-py | input-mikofo | 145.7 ± 2.8 | 141.8 | 152.3 | 70.24 ± 5.29 |
| kcen | input-mattcl | 343.7 ± 3.0 | 339.2 | 348.0 | 165.72 ± 12.14 |
| kcen | input-lanjian | 353.6 ± 2.5 | 351.0 | 357.8 | 170.47 ± 12.45 |
| kcen | input-kcen | 402.0 ± 2.7 | 398.4 | 405.9 | 193.82 ± 14.15 |
| kcen | input-mikofo | 527.9 ± 3.3 | 524.2 | 531.4 | 254.50 ± 18.58 |
| mikofo | input-mattcl | 1407.6 ± 48.6 | 1359.7 | 1456.9 | 678.64 ± 54.63 |
| mikofo | input-lanjian | 1510.2 ± 75.3 | 1425.2 | 1568.6 | 728.09 ± 64.19 |
| mikofo | input-kcen | 1705.5 ± 20.4 | 1683.4 | 1723.6 | 822.29 ± 60.60 |
| mikofo | input-mikofo | 2114.6 ± 19.3 | 2098.3 | 2135.9 | 1019.52 ± 74.72 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|