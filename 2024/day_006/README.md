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
| mattcl | input-mattcl | 1.9 ± 0.2 | 1.4 | 2.6 | 1.00 |
| mattcl | input-lanjian | 1.9 ± 0.2 | 1.4 | 2.8 | 1.01 ± 0.17 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.5 | 3.1 | 1.04 ± 0.16 |
| mattcl | input-mikofo | 2.2 ± 0.3 | 1.7 | 4.3 | 1.13 ± 0.19 |
| lanjian | input-mattcl | 39.4 ± 0.8 | 37.9 | 42.8 | 20.53 ± 2.41 |
| lanjian | input-lanjian | 43.7 ± 1.2 | 42.0 | 47.1 | 22.76 ± 2.70 |
| lanjian | input-kcen | 47.1 ± 1.1 | 45.3 | 50.6 | 24.57 ± 2.90 |
| lanjian | input-mikofo | 66.3 ± 1.0 | 64.4 | 68.1 | 34.58 ± 4.03 |
| mattcl-py | input-mattcl | 95.1 ± 1.2 | 92.4 | 97.4 | 49.59 ± 5.77 |
| mattcl-py | input-lanjian | 102.1 ± 1.6 | 98.9 | 105.2 | 53.21 ± 6.21 |
| mattcl-py | input-kcen | 109.7 ± 1.8 | 107.0 | 113.0 | 57.16 ± 6.67 |
| mattcl-py | input-mikofo | 146.0 ± 3.3 | 140.3 | 153.1 | 76.12 ± 8.97 |
| kcen | input-mattcl | 197.7 ± 3.3 | 191.7 | 203.3 | 103.07 ± 12.04 |
| kcen | input-lanjian | 205.1 ± 2.6 | 200.0 | 208.0 | 106.90 ± 12.43 |
| kcen | input-kcen | 239.9 ± 3.4 | 234.9 | 244.8 | 125.06 ± 14.56 |
| kcen | input-mikofo | 289.7 ± 6.6 | 280.0 | 299.1 | 150.99 ± 17.79 |
| mikofo | input-mattcl | 1418.0 ± 45.0 | 1366.1 | 1447.0 | 739.11 ± 88.60 |
| mikofo | input-lanjian | 1543.9 ± 42.5 | 1495.2 | 1573.5 | 804.74 ± 95.62 |
| mikofo | input-kcen | 1710.4 ± 44.9 | 1658.6 | 1739.7 | 891.55 ± 105.69 |
| mikofo | input-mikofo | 2123.2 ± 11.5 | 2112.0 | 2135.0 | 1106.74 ± 128.07 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|