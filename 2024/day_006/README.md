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
| mattcl | input-lanjian | 1.9 ± 0.2 | 1.4 | 2.8 | 1.00 ± 0.18 |
| mattcl | input-kcen | 2.0 ± 0.3 | 1.5 | 4.1 | 1.04 ± 0.19 |
| mattcl | input-mikofo | 2.1 ± 0.2 | 1.7 | 3.0 | 1.10 ± 0.17 |
| lanjian | input-mattcl | 38.9 ± 1.1 | 37.4 | 42.6 | 20.30 ± 2.59 |
| lanjian | input-lanjian | 42.6 ± 1.1 | 41.0 | 47.4 | 22.25 ± 2.83 |
| lanjian | input-kcen | 46.0 ± 1.2 | 44.4 | 49.1 | 24.01 ± 3.06 |
| lanjian | input-mikofo | 64.3 ± 1.2 | 62.2 | 66.8 | 33.55 ± 4.22 |
| mattcl-py | input-mattcl | 96.0 ± 1.2 | 93.5 | 99.2 | 50.09 ± 6.27 |
| mattcl-py | input-lanjian | 102.8 ± 1.3 | 100.0 | 106.2 | 53.67 ± 6.72 |
| mattcl-py | input-kcen | 109.5 ± 1.2 | 107.2 | 111.8 | 57.18 ± 7.15 |
| mattcl-py | input-mikofo | 146.6 ± 3.5 | 142.6 | 154.9 | 76.55 ± 9.71 |
| kcen | input-mattcl | 201.2 ± 4.2 | 196.1 | 211.6 | 105.02 ± 13.26 |
| kcen | input-lanjian | 211.4 ± 10.9 | 203.2 | 248.3 | 110.34 ± 14.88 |
| kcen | input-kcen | 243.4 ± 3.0 | 238.9 | 248.1 | 127.06 ± 15.89 |
| kcen | input-mikofo | 294.6 ± 5.1 | 288.0 | 305.4 | 153.78 ± 19.33 |
| mikofo | input-mattcl | 1416.5 ± 31.0 | 1381.0 | 1438.2 | 739.44 ± 93.46 |
| mikofo | input-lanjian | 1509.8 ± 69.1 | 1431.5 | 1562.4 | 788.15 ± 104.53 |
| mikofo | input-kcen | 1741.8 ± 29.3 | 1708.1 | 1761.1 | 909.28 ± 114.22 |
| mikofo | input-mikofo | 2136.8 ± 48.3 | 2081.3 | 2169.4 | 1115.47 ± 141.13 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|