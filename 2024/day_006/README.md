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
| mattcl | input-mattcl | 2.0 ± 0.2 | 1.5 | 3.1 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 2.6 | 1.01 ± 0.17 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.6 | 2.6 | 1.04 ± 0.16 |
| mattcl | input-mikofo | 2.2 ± 0.3 | 1.8 | 4.7 | 1.12 ± 0.19 |
| lanjian | input-mattcl | 37.6 ± 1.1 | 36.0 | 41.0 | 19.21 ± 2.43 |
| lanjian | input-lanjian | 41.4 ± 1.0 | 39.8 | 44.5 | 21.16 ± 2.66 |
| lanjian | input-kcen | 45.6 ± 1.1 | 44.2 | 49.6 | 23.30 ± 2.93 |
| mattcl-py | input-mattcl | 57.6 ± 0.7 | 56.1 | 59.3 | 29.42 ± 3.64 |
| mattcl-py | input-lanjian | 58.5 ± 0.7 | 57.4 | 61.4 | 29.90 ± 3.70 |
| mattcl-py | input-kcen | 60.4 ± 0.8 | 59.0 | 62.9 | 30.85 ± 3.82 |
| lanjian | input-mikofo | 63.0 ± 1.2 | 61.0 | 65.8 | 32.19 ± 4.01 |
| mattcl-py | input-mikofo | 64.8 ± 0.6 | 63.3 | 66.3 | 33.11 ± 4.09 |
| kcen | input-mattcl | 197.3 ± 3.4 | 192.7 | 203.6 | 100.81 ± 12.54 |
| kcen | input-lanjian | 204.8 ± 4.8 | 199.2 | 213.8 | 104.64 ± 13.12 |
| kcen | input-kcen | 250.0 ± 8.9 | 239.5 | 270.1 | 127.76 ± 16.39 |
| kcen | input-mikofo | 289.1 ± 4.0 | 283.2 | 296.2 | 147.71 ± 18.31 |
| mikofo | input-mattcl | 1371.9 ± 25.4 | 1352.2 | 1400.6 | 701.08 ± 87.35 |
| mikofo | input-lanjian | 1481.9 ± 37.0 | 1448.8 | 1521.9 | 757.29 ± 95.20 |
| mikofo | input-kcen | 1677.7 ± 46.5 | 1624.5 | 1710.4 | 857.36 ± 108.27 |
| mikofo | input-mikofo | 2060.5 ± 48.0 | 2012.5 | 2108.6 | 1052.97 ± 132.03 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|