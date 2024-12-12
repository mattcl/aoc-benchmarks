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
| mattcl | input-mattcl | 1.9 ± 0.2 | 1.4 | 2.6 | 1.00 |
| mattcl | input-lanjian | 1.9 ± 0.2 | 1.4 | 2.8 | 1.01 ± 0.18 |
| mattcl | input-kcen | 2.0 ± 0.3 | 1.4 | 3.2 | 1.05 ± 0.19 |
| mattcl | input-mikofo | 2.1 ± 0.2 | 1.7 | 2.7 | 1.10 ± 0.16 |
| lanjian | input-mattcl | 38.8 ± 0.9 | 37.4 | 41.7 | 20.69 ± 2.61 |
| lanjian | input-lanjian | 42.5 ± 0.8 | 40.9 | 45.6 | 22.62 ± 2.83 |
| lanjian | input-kcen | 45.8 ± 1.2 | 44.1 | 49.0 | 24.40 ± 3.08 |
| lanjian | input-mikofo | 65.0 ± 1.2 | 62.7 | 68.4 | 34.65 ± 4.33 |
| mattcl-py | input-mattcl | 95.2 ± 0.8 | 93.8 | 96.7 | 50.74 ± 6.30 |
| mattcl-py | input-lanjian | 102.4 ± 1.7 | 99.3 | 105.7 | 54.58 ± 6.82 |
| mattcl-py | input-kcen | 109.9 ± 1.2 | 107.6 | 112.2 | 58.53 ± 7.27 |
| mattcl-py | input-mikofo | 146.4 ± 3.2 | 141.7 | 152.1 | 78.01 ± 9.80 |
| kcen | input-mattcl | 200.6 ± 4.5 | 191.0 | 206.0 | 106.88 ± 13.44 |
| kcen | input-lanjian | 207.9 ± 2.6 | 203.4 | 212.3 | 110.78 ± 13.78 |
| kcen | input-kcen | 242.1 ± 4.9 | 237.9 | 253.1 | 128.98 ± 16.17 |
| kcen | input-mikofo | 295.8 ± 4.6 | 290.2 | 303.2 | 157.61 ± 19.66 |
| mikofo | input-mattcl | 1439.1 ± 40.3 | 1392.6 | 1462.3 | 766.71 ± 97.27 |
| mikofo | input-lanjian | 1516.0 ± 34.2 | 1477.4 | 1542.4 | 807.69 ± 101.59 |
| mikofo | input-kcen | 1736.1 ± 43.6 | 1693.2 | 1780.4 | 924.96 ± 116.78 |
| mikofo | input-mikofo | 2112.5 ± 18.9 | 2091.4 | 2127.9 | 1125.51 ± 139.63 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|