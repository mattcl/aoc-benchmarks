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
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 2.5 | 1.01 ± 0.17 |
| mattcl | input-kcen | 2.0 ± 0.3 | 1.5 | 2.7 | 1.04 ± 0.18 |
| mattcl | input-mikofo | 2.1 ± 0.2 | 1.7 | 4.0 | 1.11 ± 0.19 |
| lanjian | input-mattcl | 41.4 ± 1.2 | 39.4 | 44.8 | 21.47 ± 2.71 |
| lanjian | input-lanjian | 45.4 ± 1.2 | 43.5 | 48.7 | 23.51 ± 2.96 |
| lanjian | input-kcen | 48.9 ± 1.3 | 46.8 | 52.5 | 25.34 ± 3.18 |
| lanjian | input-mikofo | 68.7 ± 1.2 | 66.4 | 71.2 | 35.63 ± 4.42 |
| mattcl-py | input-mattcl | 95.4 ± 1.2 | 93.4 | 97.9 | 49.43 ± 6.10 |
| mattcl-py | input-lanjian | 102.6 ± 1.2 | 99.8 | 104.8 | 53.18 ± 6.56 |
| mattcl-py | input-kcen | 109.3 ± 1.2 | 107.1 | 112.4 | 56.66 ± 6.98 |
| mattcl-py | input-mikofo | 146.9 ± 4.1 | 142.2 | 154.1 | 76.16 ± 9.59 |
| kcen | input-mattcl | 199.2 ± 2.3 | 194.0 | 203.6 | 103.27 ± 12.74 |
| kcen | input-lanjian | 209.0 ± 3.9 | 202.6 | 218.2 | 108.33 ± 13.46 |
| kcen | input-kcen | 239.3 ± 3.1 | 232.7 | 243.5 | 124.06 ± 15.32 |
| kcen | input-mikofo | 292.3 ± 3.9 | 286.5 | 300.4 | 151.50 ± 18.71 |
| mikofo | input-mattcl | 1417.6 ± 45.8 | 1364.8 | 1447.0 | 734.85 ± 93.29 |
| mikofo | input-lanjian | 1508.7 ± 48.8 | 1454.4 | 1548.9 | 782.09 ± 99.30 |
| mikofo | input-kcen | 1735.5 ± 39.8 | 1704.8 | 1780.5 | 899.67 ± 112.37 |
| mikofo | input-mikofo | 2124.2 ± 15.2 | 2111.8 | 2141.2 | 1101.14 ± 135.42 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|