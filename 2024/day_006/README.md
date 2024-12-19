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
| mattcl | input-mattcl | 1.9 ± 0.2 | 1.4 | 2.7 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 2.8 | 1.01 ± 0.18 |
| mattcl | input-kcen | 2.1 ± 0.3 | 1.6 | 3.7 | 1.05 ± 0.19 |
| mattcl | input-mikofo | 2.2 ± 0.2 | 1.8 | 2.8 | 1.11 ± 0.17 |
| lanjian | input-mattcl | 41.0 ± 1.3 | 39.1 | 45.1 | 21.07 ± 2.70 |
| lanjian | input-lanjian | 44.9 ± 0.8 | 43.4 | 47.2 | 23.08 ± 2.90 |
| lanjian | input-kcen | 49.3 ± 1.5 | 47.3 | 54.7 | 25.33 ± 3.25 |
| lanjian | input-mikofo | 68.7 ± 1.3 | 66.2 | 72.4 | 35.31 ± 4.44 |
| mattcl-py | input-mattcl | 95.3 ± 1.2 | 92.6 | 98.0 | 48.98 ± 6.12 |
| mattcl-py | input-lanjian | 102.6 ± 1.7 | 99.7 | 105.8 | 52.73 ± 6.61 |
| mattcl-py | input-kcen | 109.7 ± 1.9 | 106.5 | 112.9 | 56.41 ± 7.08 |
| mattcl-py | input-mikofo | 145.5 ± 2.9 | 141.8 | 151.8 | 74.79 ± 9.42 |
| kcen | input-mattcl | 199.8 ± 3.3 | 193.4 | 204.8 | 102.68 ± 12.88 |
| kcen | input-lanjian | 207.1 ± 3.9 | 201.9 | 213.4 | 106.44 ± 13.38 |
| kcen | input-kcen | 240.8 ± 3.3 | 236.2 | 248.1 | 123.77 ± 15.48 |
| kcen | input-mikofo | 292.3 ± 5.6 | 281.3 | 298.4 | 150.23 ± 18.90 |
| mikofo | input-mattcl | 1407.6 ± 25.6 | 1381.8 | 1433.0 | 723.46 ± 90.92 |
| mikofo | input-lanjian | 1497.2 ± 35.7 | 1461.6 | 1532.9 | 769.52 ± 97.43 |
| mikofo | input-kcen | 1731.2 ± 28.9 | 1698.4 | 1752.7 | 889.81 ± 111.64 |
| mikofo | input-mikofo | 2127.7 ± 41.0 | 2099.7 | 2174.8 | 1093.57 ± 137.61 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|