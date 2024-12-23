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
| mattcl | input-lanjian | 2.0 ± 0.3 | 1.5 | 3.4 | 1.01 ± 0.19 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.6 | 2.6 | 1.02 ± 0.15 |
| mattcl | input-mikofo | 2.2 ± 0.2 | 1.8 | 3.3 | 1.11 ± 0.17 |
| lanjian | input-mattcl | 39.8 ± 0.9 | 38.5 | 42.6 | 20.26 ± 2.42 |
| lanjian | input-lanjian | 44.1 ± 1.1 | 42.6 | 47.4 | 22.48 ± 2.70 |
| lanjian | input-kcen | 47.7 ± 1.1 | 46.2 | 50.8 | 24.29 ± 2.90 |
| lanjian | input-mikofo | 66.8 ± 0.9 | 65.4 | 69.5 | 34.03 ± 4.01 |
| mattcl-py | input-mattcl | 95.6 ± 2.6 | 93.1 | 108.1 | 48.67 ± 5.85 |
| mattcl-py | input-lanjian | 103.3 ± 1.3 | 100.4 | 106.1 | 52.59 ± 6.20 |
| mattcl-py | input-kcen | 109.6 ± 1.5 | 107.2 | 113.1 | 55.79 ± 6.58 |
| mattcl-py | input-mikofo | 144.8 ± 2.1 | 140.6 | 149.3 | 73.72 ± 8.71 |
| kcen | input-mattcl | 200.8 ± 4.0 | 194.4 | 207.9 | 102.24 ± 12.16 |
| kcen | input-lanjian | 210.8 ± 3.8 | 204.9 | 217.5 | 107.34 ± 12.73 |
| kcen | input-kcen | 245.2 ± 3.3 | 239.2 | 249.6 | 124.87 ± 14.73 |
| kcen | input-mikofo | 295.9 ± 4.6 | 286.4 | 302.1 | 150.65 ± 17.81 |
| mikofo | input-mattcl | 1443.6 ± 44.8 | 1392.0 | 1472.3 | 735.04 ± 89.11 |
| mikofo | input-lanjian | 1530.3 ± 69.1 | 1452.6 | 1585.0 | 779.16 ± 97.85 |
| mikofo | input-kcen | 1730.7 ± 26.4 | 1700.7 | 1750.2 | 881.23 ± 104.14 |
| mikofo | input-mikofo | 2144.1 ± 6.6 | 2137.1 | 2150.3 | 1091.69 ± 127.98 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|