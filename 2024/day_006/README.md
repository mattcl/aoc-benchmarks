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
| mattcl | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.5 | 1.00 |
| mattcl | input-lanjian | 2.1 ± 0.2 | 1.7 | 3.0 | 1.04 ± 0.13 |
| mattcl | input-kcen | 2.2 ± 0.2 | 1.8 | 3.2 | 1.09 ± 0.14 |
| mattcl | input-mikofo | 2.4 ± 0.2 | 2.1 | 4.3 | 1.20 ± 0.14 |
| lanjian | input-mattcl | 38.6 ± 2.3 | 37.0 | 53.1 | 19.10 ± 2.08 |
| lanjian | input-lanjian | 41.9 ± 0.9 | 40.2 | 44.2 | 20.72 ± 1.93 |
| lanjian | input-kcen | 45.5 ± 1.0 | 43.8 | 48.3 | 22.49 ± 2.10 |
| lanjian | input-mikofo | 63.3 ± 1.3 | 60.9 | 68.7 | 31.32 ± 2.91 |
| mattcl-py | input-mattcl | 94.3 ± 1.1 | 92.3 | 96.7 | 46.66 ± 4.26 |
| mattcl-py | input-lanjian | 101.6 ± 1.8 | 98.2 | 104.4 | 50.26 ± 4.64 |
| mattcl-py | input-kcen | 108.7 ± 1.6 | 106.0 | 113.1 | 53.75 ± 4.93 |
| mattcl-py | input-mikofo | 144.3 ± 3.4 | 139.4 | 151.6 | 71.34 ± 6.68 |
| kcen | input-mattcl | 349.4 ± 4.3 | 343.6 | 354.2 | 172.79 ± 15.79 |
| kcen | input-lanjian | 366.1 ± 10.4 | 355.3 | 383.2 | 181.04 ± 17.18 |
| kcen | input-kcen | 418.3 ± 2.7 | 415.0 | 421.1 | 206.83 ± 18.78 |
| kcen | input-mikofo | 532.0 ± 5.2 | 523.9 | 537.8 | 263.08 ± 23.96 |
| mikofo | input-mattcl | 1384.6 ± 15.3 | 1370.4 | 1400.8 | 684.73 ± 62.46 |
| mikofo | input-lanjian | 1473.3 ± 39.7 | 1430.1 | 1508.1 | 728.59 ± 68.83 |
| mikofo | input-kcen | 1689.6 ± 37.2 | 1649.1 | 1722.2 | 835.52 ± 77.86 |
| mikofo | input-mikofo | 2063.9 ± 23.2 | 2045.8 | 2090.0 | 1020.66 ± 93.13 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|