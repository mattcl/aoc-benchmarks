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
| mattcl | input-mattcl | 1.9 ± 0.3 | 1.5 | 3.0 | 1.00 |
| mattcl | input-lanjian | 1.9 ± 0.2 | 1.5 | 2.9 | 1.01 ± 0.18 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.5 | 2.9 | 1.04 ± 0.19 |
| mattcl | input-mikofo | 2.1 ± 0.2 | 1.7 | 3.9 | 1.11 ± 0.19 |
| lanjian | input-mattcl | 38.5 ± 1.2 | 36.7 | 41.2 | 20.01 ± 2.69 |
| lanjian | input-lanjian | 42.7 ± 1.2 | 40.7 | 45.7 | 22.17 ± 2.97 |
| lanjian | input-kcen | 45.7 ± 1.1 | 43.7 | 48.5 | 23.71 ± 3.15 |
| lanjian | input-mikofo | 63.8 ± 1.2 | 61.6 | 67.8 | 33.14 ± 4.38 |
| mattcl-py | input-mattcl | 95.7 ± 1.3 | 93.8 | 98.3 | 49.68 ± 6.54 |
| mattcl-py | input-lanjian | 102.6 ± 1.6 | 98.9 | 105.7 | 53.25 ± 7.02 |
| mattcl-py | input-kcen | 109.6 ± 1.3 | 106.6 | 112.5 | 56.90 ± 7.48 |
| mattcl-py | input-mikofo | 145.7 ± 2.8 | 142.1 | 151.6 | 75.61 ± 10.01 |
| kcen | input-mattcl | 197.9 ± 2.6 | 193.7 | 203.2 | 102.75 ± 13.52 |
| kcen | input-lanjian | 208.4 ± 3.7 | 202.7 | 215.8 | 108.17 ± 14.30 |
| kcen | input-kcen | 240.2 ± 5.0 | 229.9 | 249.0 | 124.70 ± 16.53 |
| kcen | input-mikofo | 293.0 ± 6.2 | 283.3 | 302.3 | 152.11 ± 20.18 |
| mikofo | input-mattcl | 1412.2 ± 26.7 | 1381.4 | 1427.8 | 733.09 ± 96.99 |
| mikofo | input-lanjian | 1503.4 ± 45.7 | 1450.7 | 1532.4 | 780.42 ± 104.91 |
| mikofo | input-kcen | 1737.7 ± 34.8 | 1697.6 | 1758.9 | 902.09 ± 119.50 |
| mikofo | input-mikofo | 2121.8 ± 1.6 | 2120.0 | 2122.8 | 1101.47 ± 144.24 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|