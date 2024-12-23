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
| mattcl | input-mattcl | 2.0 ± 0.2 | 1.5 | 2.6 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 2.8 | 1.01 ± 0.17 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.5 | 3.2 | 1.03 ± 0.18 |
| mattcl | input-mikofo | 2.1 ± 0.2 | 1.7 | 3.4 | 1.09 ± 0.17 |
| lanjian | input-mattcl | 39.1 ± 1.1 | 37.7 | 42.9 | 20.02 ± 2.49 |
| lanjian | input-lanjian | 43.4 ± 1.1 | 41.9 | 46.3 | 22.19 ± 2.74 |
| lanjian | input-kcen | 47.2 ± 1.1 | 45.2 | 49.9 | 24.12 ± 2.97 |
| lanjian | input-mikofo | 66.3 ± 1.1 | 64.2 | 68.7 | 33.91 ± 4.14 |
| mattcl-py | input-mattcl | 94.5 ± 1.3 | 91.9 | 97.3 | 48.33 ± 5.88 |
| mattcl-py | input-lanjian | 101.1 ± 1.4 | 98.5 | 103.9 | 51.73 ± 6.30 |
| mattcl-py | input-kcen | 107.8 ± 1.2 | 105.3 | 110.2 | 55.12 ± 6.69 |
| mattcl-py | input-mikofo | 143.5 ± 3.5 | 140.2 | 155.1 | 73.39 ± 9.05 |
| kcen | input-mattcl | 199.0 ± 4.7 | 191.7 | 207.7 | 101.78 ± 12.54 |
| kcen | input-lanjian | 207.0 ± 3.2 | 200.7 | 210.6 | 105.89 ± 12.90 |
| kcen | input-kcen | 241.8 ± 2.8 | 237.4 | 247.8 | 123.67 ± 15.01 |
| kcen | input-mikofo | 293.3 ± 4.7 | 287.6 | 299.6 | 149.99 ± 18.28 |
| mikofo | input-mattcl | 1381.0 ± 29.0 | 1363.6 | 1414.5 | 706.34 ± 86.65 |
| mikofo | input-lanjian | 1476.7 ± 37.6 | 1437.5 | 1512.5 | 755.27 ± 93.29 |
| mikofo | input-kcen | 1704.2 ± 38.1 | 1665.0 | 1741.2 | 871.65 ± 107.14 |
| mikofo | input-mikofo | 2070.6 ± 59.6 | 2001.9 | 2108.2 | 1059.04 ± 131.58 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|