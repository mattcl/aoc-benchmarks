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
| mattcl | input-mattcl | 2.0 ± 0.2 | 1.5 | 2.5 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 2.7 | 1.01 ± 0.16 |
| mattcl | input-kcen | 2.1 ± 0.2 | 1.6 | 2.8 | 1.05 ± 0.16 |
| mattcl | input-mikofo | 2.2 ± 0.2 | 1.8 | 3.0 | 1.12 ± 0.16 |
| lanjian | input-mattcl | 38.9 ± 0.8 | 37.5 | 42.0 | 19.84 ± 2.17 |
| lanjian | input-lanjian | 42.5 ± 1.2 | 41.0 | 46.8 | 21.68 ± 2.41 |
| lanjian | input-kcen | 46.3 ± 1.2 | 44.4 | 49.3 | 23.58 ± 2.61 |
| lanjian | input-mikofo | 64.8 ± 1.5 | 62.5 | 69.8 | 33.02 ± 3.64 |
| mattcl-py | input-mattcl | 95.4 ± 1.1 | 93.0 | 97.0 | 48.62 ± 5.26 |
| mattcl-py | input-lanjian | 102.2 ± 1.2 | 100.1 | 104.8 | 52.06 ± 5.64 |
| mattcl-py | input-kcen | 108.7 ± 1.4 | 106.4 | 112.8 | 55.41 ± 6.01 |
| mattcl-py | input-mikofo | 146.4 ± 3.6 | 141.5 | 155.0 | 74.59 ± 8.24 |
| kcen | input-mattcl | 196.3 ± 3.7 | 189.1 | 204.1 | 100.02 ± 10.93 |
| kcen | input-lanjian | 207.1 ± 8.3 | 200.9 | 234.7 | 105.53 ± 12.13 |
| kcen | input-kcen | 240.8 ± 5.4 | 234.4 | 253.5 | 122.72 ± 13.49 |
| kcen | input-mikofo | 289.6 ± 3.7 | 281.4 | 294.8 | 147.57 ± 16.00 |
| mikofo | input-mattcl | 1430.6 ± 45.4 | 1379.2 | 1465.0 | 728.96 ± 81.83 |
| mikofo | input-lanjian | 1526.7 ± 54.9 | 1463.9 | 1565.4 | 777.93 ± 88.32 |
| mikofo | input-kcen | 1707.7 ± 45.7 | 1656.6 | 1744.7 | 870.16 ± 96.56 |
| mikofo | input-mikofo | 2127.5 ± 44.0 | 2077.4 | 2159.4 | 1084.11 ± 118.87 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|