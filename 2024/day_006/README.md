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
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 2.5 | 1.00 ± 0.15 |
| mattcl | input-kcen | 2.1 ± 0.2 | 1.5 | 2.9 | 1.03 ± 0.14 |
| mattcl | input-mikofo | 2.3 ± 0.2 | 1.8 | 3.1 | 1.15 ± 0.16 |
| lanjian | input-mattcl | 40.2 ± 1.2 | 38.4 | 43.2 | 20.24 ± 2.12 |
| lanjian | input-lanjian | 43.7 ± 0.7 | 42.5 | 46.2 | 22.01 ± 2.25 |
| lanjian | input-kcen | 47.4 ± 1.1 | 46.3 | 52.8 | 23.92 ± 2.47 |
| mattcl-py | input-mattcl | 58.2 ± 0.7 | 56.6 | 59.8 | 29.34 ± 2.98 |
| mattcl-py | input-lanjian | 59.1 ± 0.9 | 57.6 | 61.9 | 29.80 ± 3.04 |
| mattcl-py | input-kcen | 61.1 ± 0.8 | 59.3 | 63.4 | 30.79 ± 3.13 |
| mattcl-py | input-mikofo | 65.6 ± 0.7 | 64.0 | 67.0 | 33.07 ± 3.35 |
| lanjian | input-mikofo | 66.8 ± 1.0 | 65.2 | 69.6 | 33.67 ± 3.43 |
| kcen | input-mattcl | 199.9 ± 2.0 | 196.5 | 205.2 | 100.77 ± 10.20 |
| kcen | input-lanjian | 208.8 ± 3.6 | 201.7 | 214.9 | 105.26 ± 10.76 |
| kcen | input-kcen | 244.4 ± 4.8 | 236.6 | 254.1 | 123.19 ± 12.65 |
| kcen | input-mikofo | 296.5 ± 5.4 | 288.7 | 306.2 | 149.44 ± 15.31 |
| mikofo | input-mattcl | 1424.8 ± 43.4 | 1393.4 | 1474.4 | 718.14 ± 75.61 |
| mikofo | input-lanjian | 1511.5 ± 40.8 | 1483.2 | 1558.3 | 761.85 ± 79.48 |
| mikofo | input-kcen | 1709.6 ± 58.2 | 1642.7 | 1748.2 | 861.69 ± 91.65 |
| mikofo | input-mikofo | 2091.3 ± 45.1 | 2039.2 | 2118.4 | 1054.05 ± 108.63 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|