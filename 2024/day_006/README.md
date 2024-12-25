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
| mattcl | input-mattcl | 2.0 ± 0.2 | 1.4 | 3.0 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 2.6 | 1.00 ± 0.16 |
| mattcl | input-kcen | 2.1 ± 0.2 | 1.6 | 3.0 | 1.04 ± 0.17 |
| mattcl | input-mikofo | 2.2 ± 0.2 | 1.7 | 2.7 | 1.10 ± 0.16 |
| lanjian | input-mattcl | 39.5 ± 1.1 | 37.7 | 42.7 | 20.07 ± 2.52 |
| lanjian | input-lanjian | 43.4 ± 1.1 | 41.9 | 48.0 | 22.04 ± 2.76 |
| lanjian | input-kcen | 47.1 ± 1.0 | 45.3 | 49.9 | 23.94 ± 2.97 |
| mattcl-py | input-mattcl | 57.7 ± 0.7 | 56.3 | 59.3 | 29.35 ± 3.60 |
| mattcl-py | input-lanjian | 58.5 ± 0.7 | 57.1 | 60.1 | 29.76 ± 3.66 |
| mattcl-py | input-kcen | 60.4 ± 0.8 | 58.9 | 62.5 | 30.73 ± 3.78 |
| mattcl-py | input-mikofo | 64.9 ± 0.8 | 63.3 | 67.0 | 33.01 ± 4.06 |
| lanjian | input-mikofo | 66.0 ± 1.4 | 63.5 | 69.8 | 33.58 ± 4.17 |
| kcen | input-mattcl | 200.2 ± 2.9 | 195.3 | 205.5 | 101.80 ± 12.53 |
| kcen | input-lanjian | 206.2 ± 4.2 | 199.7 | 214.0 | 104.85 ± 12.99 |
| kcen | input-kcen | 241.7 ± 4.2 | 233.8 | 246.8 | 122.93 ± 15.17 |
| kcen | input-mikofo | 288.8 ± 5.4 | 281.6 | 296.7 | 146.86 ± 18.15 |
| mikofo | input-mattcl | 1381.1 ± 32.2 | 1350.4 | 1414.7 | 702.29 ± 87.36 |
| mikofo | input-lanjian | 1439.7 ± 38.0 | 1404.8 | 1480.2 | 732.05 ± 91.52 |
| mikofo | input-kcen | 1673.7 ± 43.2 | 1625.5 | 1709.0 | 851.04 ± 106.29 |
| mikofo | input-mikofo | 2049.8 ± 51.8 | 1995.8 | 2099.1 | 1042.31 ± 130.05 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|