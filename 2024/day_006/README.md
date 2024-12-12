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
| mattcl | input-mattcl | 2.1 ± 0.2 | 1.6 | 2.8 | 1.00 |
| mattcl | input-lanjian | 2.2 ± 0.3 | 1.6 | 3.1 | 1.01 ± 0.17 |
| mattcl | input-kcen | 2.2 ± 0.3 | 1.7 | 3.6 | 1.05 ± 0.18 |
| mattcl | input-mikofo | 2.4 ± 0.3 | 1.9 | 5.6 | 1.11 ± 0.19 |
| lanjian | input-mattcl | 38.6 ± 1.1 | 37.2 | 42.8 | 18.18 ± 2.17 |
| lanjian | input-lanjian | 42.5 ± 1.2 | 40.9 | 45.9 | 20.01 ± 2.39 |
| lanjian | input-kcen | 46.3 ± 1.2 | 44.3 | 49.4 | 21.79 ± 2.59 |
| lanjian | input-mikofo | 63.8 ± 1.2 | 62.4 | 69.3 | 30.05 ± 3.53 |
| mattcl-py | input-mattcl | 94.5 ± 1.1 | 91.9 | 97.3 | 44.51 ± 5.18 |
| mattcl-py | input-lanjian | 101.6 ± 1.5 | 99.0 | 104.4 | 47.85 ± 5.59 |
| mattcl-py | input-kcen | 108.5 ± 1.3 | 105.7 | 111.7 | 51.12 ± 5.95 |
| mattcl-py | input-mikofo | 144.1 ± 2.9 | 139.9 | 151.0 | 67.86 ± 7.98 |
| kcen | input-mattcl | 201.2 ± 3.9 | 193.2 | 207.2 | 94.77 ± 11.13 |
| kcen | input-lanjian | 210.5 ± 11.0 | 203.3 | 247.9 | 99.17 ± 12.60 |
| kcen | input-kcen | 245.2 ± 4.2 | 238.4 | 252.4 | 115.49 ± 13.52 |
| kcen | input-mikofo | 291.8 ± 6.0 | 282.6 | 299.8 | 137.45 ± 16.17 |
| mikofo | input-mattcl | 1387.3 ± 40.1 | 1343.4 | 1422.1 | 653.54 ± 78.03 |
| mikofo | input-lanjian | 1480.5 ± 25.4 | 1451.6 | 1499.0 | 697.45 ± 81.67 |
| mikofo | input-kcen | 1681.2 ± 39.4 | 1636.0 | 1708.5 | 791.98 ± 93.60 |
| mikofo | input-mikofo | 2078.2 ± 11.2 | 2067.3 | 2089.7 | 979.01 ± 113.53 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|