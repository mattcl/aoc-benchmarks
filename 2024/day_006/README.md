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
| mattcl | input-mattcl | 2.0 ± 0.2 | 1.5 | 2.8 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 2.8 | 1.01 ± 0.16 |
| mattcl | input-kcen | 2.1 ± 0.2 | 1.6 | 3.1 | 1.05 ± 0.17 |
| mattcl | input-mikofo | 2.2 ± 0.2 | 1.8 | 3.0 | 1.11 ± 0.15 |
| lanjian | input-mattcl | 37.5 ± 1.0 | 35.9 | 40.4 | 18.81 ± 2.23 |
| lanjian | input-lanjian | 40.8 ± 1.2 | 39.0 | 46.5 | 20.46 ± 2.44 |
| lanjian | input-kcen | 43.6 ± 1.1 | 42.1 | 46.8 | 21.90 ± 2.59 |
| mattcl-py | input-mattcl | 57.7 ± 0.6 | 56.5 | 59.2 | 28.94 ± 3.36 |
| mattcl-py | input-lanjian | 58.4 ± 0.7 | 57.2 | 60.1 | 29.31 ± 3.40 |
| mattcl-py | input-kcen | 60.5 ± 0.9 | 59.0 | 64.3 | 30.39 ± 3.54 |
| lanjian | input-mikofo | 60.9 ± 1.3 | 59.5 | 65.7 | 30.54 ± 3.59 |
| mattcl-py | input-mikofo | 64.8 ± 0.8 | 62.9 | 67.3 | 32.52 ± 3.78 |
| kcen | input-mattcl | 200.4 ± 2.8 | 196.3 | 205.4 | 100.59 ± 11.71 |
| kcen | input-lanjian | 209.4 ± 3.4 | 202.8 | 215.5 | 105.09 ± 12.26 |
| kcen | input-kcen | 243.5 ± 5.0 | 235.4 | 250.6 | 122.18 ± 14.34 |
| kcen | input-mikofo | 293.4 ± 8.1 | 284.3 | 307.6 | 147.23 ± 17.50 |
| mikofo | input-mattcl | 1361.5 ± 23.9 | 1335.5 | 1382.5 | 683.26 ± 79.88 |
| mikofo | input-lanjian | 1503.8 ± 12.7 | 1492.5 | 1517.5 | 754.66 ± 87.45 |
| mikofo | input-kcen | 1682.0 ± 40.4 | 1638.4 | 1718.3 | 844.10 ± 99.65 |
| mikofo | input-mikofo | 2057.4 ± 41.4 | 2009.6 | 2081.3 | 1032.48 ± 121.12 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|