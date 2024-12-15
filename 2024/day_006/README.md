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
| mattcl | input-mattcl | 1.9 ± 0.2 | 1.5 | 2.7 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.3 | 1.5 | 2.6 | 1.02 ± 0.18 |
| mattcl | input-kcen | 2.0 ± 0.3 | 1.5 | 3.6 | 1.04 ± 0.19 |
| mattcl | input-mikofo | 2.2 ± 0.2 | 1.7 | 4.4 | 1.12 ± 0.18 |
| lanjian | input-mattcl | 41.3 ± 1.3 | 39.2 | 45.1 | 21.48 ± 2.59 |
| lanjian | input-lanjian | 45.2 ± 1.1 | 43.5 | 47.9 | 23.49 ± 2.79 |
| lanjian | input-kcen | 49.0 ± 1.4 | 47.0 | 54.5 | 25.47 ± 3.04 |
| lanjian | input-mikofo | 68.7 ± 1.6 | 66.0 | 74.4 | 35.74 ± 4.23 |
| mattcl-py | input-mattcl | 95.5 ± 1.0 | 93.7 | 97.4 | 49.64 ± 5.79 |
| mattcl-py | input-lanjian | 103.2 ± 1.8 | 99.3 | 108.9 | 53.65 ± 6.29 |
| mattcl-py | input-kcen | 110.1 ± 1.7 | 107.9 | 114.2 | 57.24 ± 6.70 |
| mattcl-py | input-mikofo | 144.2 ± 2.6 | 140.4 | 151.2 | 74.97 ± 8.81 |
| kcen | input-mattcl | 197.9 ± 4.2 | 193.7 | 209.9 | 102.88 ± 12.14 |
| kcen | input-lanjian | 206.3 ± 2.9 | 201.0 | 210.8 | 107.27 ± 12.54 |
| kcen | input-kcen | 240.4 ± 4.9 | 227.5 | 245.7 | 124.98 ± 14.72 |
| kcen | input-mikofo | 291.1 ± 5.4 | 284.5 | 300.8 | 151.38 ± 17.79 |
| mikofo | input-mattcl | 1407.9 ± 34.9 | 1368.0 | 1432.5 | 732.09 ± 86.87 |
| mikofo | input-lanjian | 1526.0 ± 46.8 | 1475.4 | 1567.7 | 793.51 ± 95.24 |
| mikofo | input-kcen | 1736.6 ± 30.5 | 1704.9 | 1765.6 | 902.99 ± 105.97 |
| mikofo | input-mikofo | 2131.3 ± 19.6 | 2112.0 | 2151.3 | 1108.25 ± 129.00 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|