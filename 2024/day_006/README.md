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
| mattcl | input-mattcl | 2.0 ± 0.2 | 1.5 | 2.9 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 2.6 | 1.01 ± 0.16 |
| mattcl | input-kcen | 2.1 ± 0.2 | 1.6 | 3.5 | 1.04 ± 0.16 |
| mattcl | input-mikofo | 2.2 ± 0.2 | 1.7 | 2.8 | 1.12 ± 0.15 |
| lanjian | input-mattcl | 40.0 ± 1.1 | 37.9 | 42.8 | 20.07 ± 2.30 |
| lanjian | input-lanjian | 43.8 ± 0.9 | 42.3 | 46.6 | 22.02 ± 2.50 |
| lanjian | input-kcen | 47.6 ± 1.1 | 46.1 | 52.7 | 23.93 ± 2.73 |
| mattcl-py | input-mattcl | 58.7 ± 0.7 | 57.3 | 60.6 | 29.51 ± 3.31 |
| mattcl-py | input-lanjian | 59.3 ± 0.8 | 57.7 | 61.7 | 29.80 ± 3.35 |
| mattcl-py | input-kcen | 61.2 ± 0.7 | 59.9 | 63.1 | 30.73 ± 3.44 |
| mattcl-py | input-mikofo | 66.1 ± 0.8 | 64.2 | 67.6 | 33.21 ± 3.72 |
| lanjian | input-mikofo | 66.8 ± 0.9 | 64.6 | 68.7 | 33.54 ± 3.77 |
| kcen | input-mattcl | 200.1 ± 2.9 | 194.2 | 205.9 | 100.51 ± 11.30 |
| kcen | input-lanjian | 211.7 ± 6.4 | 203.0 | 225.6 | 106.34 ± 12.29 |
| kcen | input-kcen | 246.0 ± 4.5 | 235.8 | 253.3 | 123.58 ± 13.96 |
| kcen | input-mikofo | 294.5 ± 4.7 | 286.6 | 301.9 | 147.96 ± 16.67 |
| mikofo | input-mattcl | 1409.2 ± 47.5 | 1378.8 | 1463.9 | 707.89 ± 82.45 |
| mikofo | input-lanjian | 1519.4 ± 53.6 | 1460.2 | 1564.7 | 763.24 ± 89.25 |
| mikofo | input-kcen | 1726.8 ± 63.8 | 1654.4 | 1774.9 | 867.42 ± 101.88 |
| mikofo | input-mikofo | 2104.2 ± 61.4 | 2039.1 | 2161.0 | 1057.01 ± 121.82 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|