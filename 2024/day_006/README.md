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
| mattcl | input-mattcl | 1.9 ± 0.2 | 1.3 | 3.0 | 1.00 |
| mattcl | input-lanjian | 1.9 ± 0.2 | 1.4 | 3.2 | 1.01 ± 0.18 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.5 | 2.6 | 1.05 ± 0.18 |
| mattcl | input-mikofo | 2.1 ± 0.2 | 1.7 | 2.9 | 1.11 ± 0.17 |
| lanjian | input-mattcl | 38.4 ± 1.5 | 37.1 | 48.3 | 20.34 ± 2.69 |
| lanjian | input-lanjian | 42.6 ± 1.2 | 40.2 | 45.2 | 22.56 ± 2.92 |
| lanjian | input-kcen | 45.5 ± 1.0 | 44.0 | 48.0 | 24.06 ± 3.08 |
| lanjian | input-mikofo | 63.9 ± 1.3 | 61.8 | 67.5 | 33.81 ± 4.31 |
| mattcl-py | input-mattcl | 93.9 ± 1.2 | 91.4 | 96.5 | 49.70 ± 6.30 |
| mattcl-py | input-lanjian | 101.7 ± 1.5 | 99.0 | 105.1 | 53.82 ± 6.83 |
| mattcl-py | input-kcen | 107.9 ± 1.7 | 104.9 | 112.5 | 57.10 ± 7.25 |
| mattcl-py | input-mikofo | 144.8 ± 3.9 | 140.2 | 153.7 | 76.62 ± 9.88 |
| kcen | input-mattcl | 199.3 ± 4.7 | 192.5 | 205.8 | 105.50 ± 13.53 |
| kcen | input-lanjian | 207.3 ± 5.4 | 198.5 | 215.5 | 109.71 ± 14.12 |
| kcen | input-kcen | 243.7 ± 5.4 | 231.9 | 252.8 | 128.96 ± 16.50 |
| kcen | input-mikofo | 294.8 ± 5.3 | 288.5 | 303.6 | 156.02 ± 19.87 |
| mikofo | input-mattcl | 1387.0 ± 26.8 | 1356.3 | 1405.9 | 734.07 ± 93.61 |
| mikofo | input-lanjian | 1490.5 ± 25.8 | 1463.5 | 1515.0 | 788.85 ± 100.37 |
| mikofo | input-kcen | 1688.5 ± 37.7 | 1645.5 | 1715.7 | 893.64 ± 114.40 |
| mikofo | input-mikofo | 2072.1 ± 8.1 | 2063.7 | 2079.9 | 1096.64 ± 138.30 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|