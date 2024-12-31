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
| mattcl | input-mattcl | 2.0 ± 0.2 | 1.6 | 2.5 | 1.00 |
| mattcl | input-lanjian | 2.1 ± 0.2 | 1.5 | 2.8 | 1.02 ± 0.14 |
| mattcl | input-kcen | 2.1 ± 0.2 | 1.6 | 3.2 | 1.05 ± 0.14 |
| mattcl | input-mikofo | 2.3 ± 0.3 | 1.9 | 4.9 | 1.15 ± 0.17 |
| lanjian | input-mattcl | 39.4 ± 0.9 | 38.2 | 43.1 | 19.42 ± 1.90 |
| lanjian | input-lanjian | 43.5 ± 1.0 | 42.2 | 46.4 | 21.47 ± 2.09 |
| lanjian | input-kcen | 47.3 ± 1.1 | 45.6 | 51.4 | 23.31 ± 2.28 |
| mattcl-py | input-mattcl | 58.6 ± 0.7 | 56.6 | 60.0 | 28.89 ± 2.76 |
| mattcl-py | input-lanjian | 59.1 ± 0.7 | 57.7 | 61.3 | 29.11 ± 2.78 |
| mattcl-py | input-kcen | 61.5 ± 1.0 | 59.2 | 63.9 | 30.29 ± 2.91 |
| mattcl-py | input-mikofo | 65.9 ± 1.0 | 63.8 | 68.1 | 32.50 ± 3.11 |
| lanjian | input-mikofo | 66.5 ± 0.9 | 65.2 | 68.3 | 32.78 ± 3.14 |
| kcen | input-mattcl | 198.2 ± 3.0 | 193.9 | 203.5 | 97.72 ± 9.36 |
| kcen | input-lanjian | 207.7 ± 2.6 | 203.2 | 213.1 | 102.37 ± 9.77 |
| kcen | input-kcen | 243.3 ± 3.3 | 238.0 | 248.8 | 119.93 ± 11.46 |
| kcen | input-mikofo | 294.2 ± 3.1 | 289.7 | 299.6 | 145.03 ± 13.81 |
| mikofo | input-mattcl | 1424.4 ± 38.8 | 1401.0 | 1469.2 | 702.19 ± 69.14 |
| mikofo | input-lanjian | 1519.9 ± 48.2 | 1488.9 | 1575.5 | 749.26 ± 74.78 |
| mikofo | input-kcen | 1719.9 ± 61.8 | 1648.7 | 1760.7 | 847.83 ± 85.82 |
| mikofo | input-mikofo | 2113.2 ± 45.3 | 2062.0 | 2148.1 | 1041.70 ± 101.07 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|