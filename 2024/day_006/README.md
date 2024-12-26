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
| mattcl | input-mattcl | 2.0 ± 0.2 | 1.5 | 2.9 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 2.7 | 1.01 ± 0.16 |
| mattcl | input-kcen | 2.1 ± 0.2 | 1.5 | 3.3 | 1.04 ± 0.17 |
| mattcl | input-mikofo | 2.2 ± 0.2 | 1.8 | 2.6 | 1.10 ± 0.15 |
| lanjian | input-mattcl | 37.0 ± 0.9 | 35.8 | 39.8 | 18.66 ± 2.14 |
| lanjian | input-lanjian | 41.0 ± 1.4 | 39.2 | 47.5 | 20.67 ± 2.41 |
| lanjian | input-kcen | 44.2 ± 1.1 | 42.7 | 47.0 | 22.28 ± 2.55 |
| mattcl-py | input-mattcl | 57.7 ± 0.7 | 56.3 | 59.2 | 29.11 ± 3.27 |
| mattcl-py | input-lanjian | 58.6 ± 0.7 | 56.7 | 60.4 | 29.53 ± 3.32 |
| mattcl-py | input-kcen | 60.3 ± 0.8 | 58.4 | 61.6 | 30.39 ± 3.41 |
| lanjian | input-mikofo | 62.0 ± 1.5 | 59.7 | 65.1 | 31.25 ± 3.57 |
| mattcl-py | input-mikofo | 64.8 ± 1.0 | 62.6 | 67.2 | 32.66 ± 3.68 |
| kcen | input-mattcl | 198.2 ± 4.1 | 191.1 | 204.3 | 99.95 ± 11.34 |
| kcen | input-lanjian | 206.2 ± 3.3 | 200.6 | 211.7 | 103.97 ± 11.73 |
| kcen | input-kcen | 243.8 ± 7.2 | 236.3 | 262.6 | 122.94 ± 14.20 |
| kcen | input-mikofo | 293.0 ± 9.9 | 283.9 | 312.0 | 147.70 ± 17.22 |
| mikofo | input-mattcl | 1390.9 ± 34.2 | 1356.3 | 1424.7 | 701.25 ± 80.16 |
| mikofo | input-lanjian | 1482.4 ± 12.5 | 1470.3 | 1495.2 | 747.39 ± 83.68 |
| mikofo | input-kcen | 1678.0 ± 38.2 | 1638.1 | 1714.2 | 846.00 ± 96.39 |
| mikofo | input-mikofo | 2075.5 ± 51.7 | 2027.6 | 2130.2 | 1046.40 ± 119.69 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|