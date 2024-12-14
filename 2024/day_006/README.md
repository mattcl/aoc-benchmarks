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
| mattcl | input-mattcl | 1.9 ± 0.3 | 1.4 | 2.9 | 1.00 |
| mattcl | input-lanjian | 1.9 ± 0.2 | 1.4 | 3.0 | 1.01 ± 0.18 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.5 | 3.0 | 1.04 ± 0.19 |
| mattcl | input-mikofo | 2.1 ± 0.2 | 1.7 | 2.8 | 1.11 ± 0.17 |
| lanjian | input-mattcl | 38.4 ± 1.0 | 36.6 | 42.2 | 20.04 ± 2.68 |
| lanjian | input-lanjian | 42.2 ± 1.2 | 39.7 | 45.6 | 22.07 ± 2.97 |
| lanjian | input-kcen | 45.4 ± 0.9 | 43.8 | 47.7 | 23.73 ± 3.15 |
| lanjian | input-mikofo | 63.4 ± 1.3 | 61.3 | 66.3 | 33.13 ± 4.40 |
| mattcl-py | input-mattcl | 93.5 ± 1.0 | 91.9 | 95.3 | 48.83 ± 6.43 |
| mattcl-py | input-lanjian | 100.9 ± 1.3 | 99.0 | 103.2 | 52.72 ± 6.95 |
| mattcl-py | input-kcen | 107.9 ± 1.5 | 104.8 | 111.1 | 56.36 ± 7.43 |
| mattcl-py | input-mikofo | 143.7 ± 3.3 | 140.0 | 151.4 | 75.04 ± 9.99 |
| kcen | input-mattcl | 197.6 ± 4.9 | 189.0 | 205.3 | 103.20 ± 13.78 |
| kcen | input-lanjian | 209.0 ± 6.4 | 198.5 | 223.4 | 109.19 ± 14.71 |
| kcen | input-kcen | 243.3 ± 6.1 | 233.0 | 253.5 | 127.10 ± 16.97 |
| kcen | input-mikofo | 291.9 ± 5.1 | 284.7 | 298.9 | 152.49 ± 20.18 |
| mikofo | input-mattcl | 1402.3 ± 30.1 | 1379.6 | 1436.5 | 732.52 ± 97.36 |
| mikofo | input-lanjian | 1469.3 ± 22.9 | 1448.3 | 1493.7 | 767.51 ± 101.38 |
| mikofo | input-kcen | 1678.3 ± 38.4 | 1641.7 | 1718.3 | 876.68 ± 116.73 |
| mikofo | input-mikofo | 2076.8 ± 29.6 | 2057.2 | 2110.9 | 1084.87 ± 143.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|