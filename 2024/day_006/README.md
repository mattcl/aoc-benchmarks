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
| mattcl | input-mattcl | 2.0 ± 0.2 | 1.5 | 2.8 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 3.0 | 1.01 ± 0.17 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.5 | 2.6 | 1.01 ± 0.17 |
| mattcl | input-mikofo | 2.2 ± 0.2 | 1.8 | 2.7 | 1.10 ± 0.15 |
| lanjian | input-mattcl | 38.7 ± 0.9 | 37.3 | 41.4 | 19.29 ± 2.32 |
| lanjian | input-lanjian | 42.5 ± 0.9 | 40.9 | 45.1 | 21.20 ± 2.55 |
| lanjian | input-kcen | 45.9 ± 1.0 | 44.2 | 47.9 | 22.91 ± 2.76 |
| lanjian | input-mikofo | 64.2 ± 1.0 | 62.3 | 66.8 | 32.04 ± 3.82 |
| mattcl-py | input-mattcl | 95.8 ± 0.9 | 93.9 | 97.6 | 47.82 ± 5.67 |
| mattcl-py | input-lanjian | 102.7 ± 1.7 | 99.7 | 105.4 | 51.24 ± 6.11 |
| mattcl-py | input-kcen | 110.2 ± 1.6 | 107.6 | 113.8 | 54.97 ± 6.55 |
| mattcl-py | input-mikofo | 146.2 ± 4.0 | 140.9 | 155.6 | 72.93 ± 8.85 |
| kcen | input-mattcl | 200.0 ± 2.6 | 193.4 | 203.5 | 99.81 ± 11.87 |
| kcen | input-lanjian | 210.3 ± 4.0 | 202.8 | 216.3 | 104.95 ± 12.57 |
| kcen | input-kcen | 239.7 ± 2.4 | 234.8 | 242.7 | 119.59 ± 14.19 |
| kcen | input-mikofo | 293.1 ± 5.4 | 284.2 | 304.7 | 146.27 ± 17.51 |
| mikofo | input-mattcl | 1406.1 ± 49.5 | 1355.0 | 1453.8 | 701.62 ± 86.55 |
| mikofo | input-lanjian | 1509.5 ± 35.4 | 1468.7 | 1530.1 | 753.22 ± 90.78 |
| mikofo | input-kcen | 1740.9 ± 15.6 | 1723.1 | 1752.3 | 868.69 ± 103.00 |
| mikofo | input-mikofo | 2124.5 ± 48.8 | 2071.3 | 2167.0 | 1060.06 ± 127.67 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|