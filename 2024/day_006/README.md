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
| mattcl | input-mattcl | 2.0 ± 0.2 | 1.5 | 2.5 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 3.1 | 1.01 ± 0.17 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.6 | 2.8 | 1.04 ± 0.16 |
| mattcl | input-mikofo | 2.2 ± 0.2 | 1.7 | 3.1 | 1.13 ± 0.16 |
| lanjian | input-mattcl | 39.2 ± 1.0 | 37.0 | 42.5 | 20.03 ± 2.31 |
| lanjian | input-lanjian | 42.3 ± 0.8 | 41.0 | 44.6 | 21.62 ± 2.46 |
| lanjian | input-kcen | 46.2 ± 1.2 | 44.1 | 50.1 | 23.58 ± 2.72 |
| lanjian | input-mikofo | 64.7 ± 1.2 | 62.2 | 68.0 | 33.04 ± 3.76 |
| mattcl-py | input-mattcl | 94.9 ± 1.0 | 91.8 | 97.2 | 48.48 ± 5.47 |
| mattcl-py | input-lanjian | 102.4 ± 1.4 | 99.6 | 105.1 | 52.29 ± 5.91 |
| mattcl-py | input-kcen | 109.5 ± 1.7 | 106.7 | 113.0 | 55.90 ± 6.33 |
| mattcl-py | input-mikofo | 146.3 ± 3.6 | 141.4 | 153.1 | 74.69 ± 8.58 |
| kcen | input-mattcl | 198.8 ± 3.0 | 194.3 | 205.8 | 101.50 ± 11.50 |
| kcen | input-lanjian | 205.4 ± 3.9 | 199.3 | 211.3 | 104.87 ± 11.94 |
| kcen | input-kcen | 237.8 ± 5.0 | 230.1 | 245.2 | 121.43 ± 13.87 |
| kcen | input-mikofo | 289.6 ± 2.6 | 283.8 | 292.4 | 147.87 ± 16.65 |
| mikofo | input-mattcl | 1429.1 ± 55.6 | 1369.0 | 1478.5 | 729.76 ± 86.69 |
| mikofo | input-lanjian | 1513.1 ± 37.1 | 1470.9 | 1540.5 | 772.67 ± 88.79 |
| mikofo | input-kcen | 1719.3 ± 30.2 | 1691.5 | 1751.4 | 877.93 ± 99.75 |
| mikofo | input-mikofo | 2107.8 ± 31.7 | 2071.5 | 2129.8 | 1076.32 ± 121.90 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|