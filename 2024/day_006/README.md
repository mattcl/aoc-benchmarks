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
| mattcl | input-mattcl | 1.9 ± 0.3 | 1.4 | 3.4 | 1.00 |
| mattcl | input-lanjian | 1.9 ± 0.3 | 1.4 | 3.0 | 1.01 ± 0.19 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.5 | 2.7 | 1.05 ± 0.19 |
| mattcl | input-mikofo | 2.1 ± 0.3 | 1.6 | 3.8 | 1.13 ± 0.21 |
| lanjian | input-mattcl | 40.7 ± 1.3 | 39.1 | 44.7 | 21.54 ± 2.93 |
| lanjian | input-lanjian | 44.9 ± 1.4 | 43.0 | 48.2 | 23.77 ± 3.24 |
| lanjian | input-kcen | 48.5 ± 1.1 | 46.6 | 50.8 | 25.69 ± 3.45 |
| lanjian | input-mikofo | 67.9 ± 1.2 | 65.5 | 71.0 | 35.92 ± 4.81 |
| mattcl-py | input-mattcl | 93.8 ± 1.3 | 91.9 | 96.8 | 49.67 ± 6.62 |
| mattcl-py | input-lanjian | 101.1 ± 1.6 | 97.8 | 104.0 | 53.51 ± 7.15 |
| mattcl-py | input-kcen | 107.7 ± 1.7 | 105.1 | 112.9 | 57.00 ± 7.61 |
| mattcl-py | input-mikofo | 142.8 ± 3.1 | 139.1 | 149.7 | 75.61 ± 10.16 |
| kcen | input-mattcl | 197.3 ± 4.1 | 191.6 | 205.5 | 104.47 ± 14.02 |
| kcen | input-lanjian | 210.8 ± 6.2 | 205.2 | 230.5 | 111.59 ± 15.16 |
| kcen | input-kcen | 237.8 ± 5.7 | 229.2 | 251.9 | 125.87 ± 16.96 |
| kcen | input-mikofo | 289.1 ± 4.1 | 280.7 | 295.4 | 153.02 ± 20.41 |
| mikofo | input-mattcl | 1392.8 ± 23.9 | 1373.8 | 1419.6 | 737.36 ± 98.59 |
| mikofo | input-lanjian | 1471.6 ± 64.1 | 1397.6 | 1508.6 | 779.07 ± 108.74 |
| mikofo | input-kcen | 1686.0 ± 58.2 | 1623.8 | 1739.1 | 892.55 ± 122.30 |
| mikofo | input-mikofo | 2049.3 ± 11.6 | 2036.6 | 2059.3 | 1084.88 ± 143.99 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|