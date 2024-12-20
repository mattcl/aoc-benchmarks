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
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 2.7 | 1.00 |
| mattcl | input-mattcl | 2.0 ± 0.2 | 1.5 | 2.7 | 1.00 ± 0.16 |
| mattcl | input-kcen | 2.1 ± 0.2 | 1.6 | 2.7 | 1.02 ± 0.15 |
| mattcl | input-mikofo | 2.2 ± 0.3 | 1.7 | 5.5 | 1.10 ± 0.19 |
| lanjian | input-mattcl | 37.6 ± 1.1 | 36.2 | 41.2 | 18.72 ± 2.08 |
| lanjian | input-lanjian | 41.0 ± 1.1 | 39.3 | 43.7 | 20.42 ± 2.26 |
| lanjian | input-kcen | 43.9 ± 1.3 | 42.3 | 47.0 | 21.85 ± 2.42 |
| lanjian | input-mikofo | 61.3 ± 0.8 | 59.7 | 63.4 | 30.48 ± 3.29 |
| mattcl-py | input-mattcl | 95.9 ± 1.0 | 94.3 | 97.8 | 47.69 ± 5.12 |
| mattcl-py | input-lanjian | 103.0 ± 1.6 | 99.0 | 107.4 | 51.25 ± 5.54 |
| mattcl-py | input-kcen | 109.6 ± 1.4 | 107.1 | 112.0 | 54.51 ± 5.87 |
| mattcl-py | input-mikofo | 145.5 ± 2.9 | 140.2 | 150.8 | 72.34 ± 7.87 |
| kcen | input-mattcl | 199.0 ± 4.6 | 189.8 | 205.0 | 98.98 ± 10.83 |
| kcen | input-lanjian | 206.5 ± 2.4 | 201.2 | 211.0 | 102.69 ± 11.05 |
| kcen | input-kcen | 240.0 ± 2.1 | 236.5 | 243.9 | 119.34 ± 12.80 |
| kcen | input-mikofo | 289.0 ± 5.6 | 282.5 | 298.7 | 143.71 ± 15.62 |
| mikofo | input-mattcl | 1427.8 ± 43.8 | 1377.2 | 1453.5 | 710.10 ± 79.00 |
| mikofo | input-lanjian | 1517.7 ± 43.0 | 1471.2 | 1556.2 | 754.81 ± 83.51 |
| mikofo | input-kcen | 1732.6 ± 26.0 | 1704.0 | 1754.9 | 861.70 ± 93.05 |
| mikofo | input-mikofo | 2125.9 ± 2.1 | 2123.7 | 2127.8 | 1057.31 ± 113.07 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|