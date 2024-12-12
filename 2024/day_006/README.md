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
| mattcl | input-mattcl | 1.9 ± 0.2 | 1.4 | 2.5 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 2.6 | 1.00 ± 0.17 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.4 | 2.5 | 1.02 ± 0.16 |
| mattcl | input-mikofo | 2.2 ± 0.3 | 1.6 | 5.1 | 1.12 ± 0.22 |
| lanjian | input-mattcl | 38.7 ± 0.9 | 37.3 | 42.1 | 19.92 ± 2.43 |
| lanjian | input-lanjian | 42.5 ± 0.9 | 41.1 | 45.9 | 21.84 ± 2.66 |
| lanjian | input-kcen | 46.4 ± 1.1 | 44.8 | 49.0 | 23.83 ± 2.91 |
| lanjian | input-mikofo | 64.6 ± 1.1 | 62.6 | 66.8 | 33.22 ± 4.02 |
| mattcl-py | input-mattcl | 95.9 ± 1.1 | 94.0 | 98.1 | 49.28 ± 5.93 |
| mattcl-py | input-lanjian | 102.9 ± 1.2 | 99.6 | 104.8 | 52.91 ± 6.37 |
| mattcl-py | input-kcen | 109.9 ± 1.4 | 108.0 | 115.2 | 56.51 ± 6.81 |
| mattcl-py | input-mikofo | 146.1 ± 2.8 | 141.7 | 152.4 | 75.09 ± 9.11 |
| kcen | input-mattcl | 200.6 ± 3.1 | 194.1 | 205.6 | 103.12 ± 12.45 |
| kcen | input-lanjian | 208.1 ± 3.1 | 201.1 | 212.4 | 107.00 ± 12.92 |
| kcen | input-kcen | 241.5 ± 3.5 | 236.7 | 248.0 | 124.18 ± 14.98 |
| kcen | input-mikofo | 295.1 ± 3.4 | 291.3 | 300.4 | 151.72 ± 18.26 |
| mikofo | input-mattcl | 1433.1 ± 32.2 | 1396.0 | 1451.9 | 736.75 ± 89.78 |
| mikofo | input-lanjian | 1523.1 ± 36.4 | 1486.9 | 1559.7 | 783.01 ± 95.64 |
| mikofo | input-kcen | 1734.2 ± 38.8 | 1690.9 | 1765.7 | 891.57 ± 108.63 |
| mikofo | input-mikofo | 2140.4 ± 9.9 | 2134.1 | 2151.8 | 1100.41 ± 131.90 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|