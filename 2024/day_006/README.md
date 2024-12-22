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
| mattcl | input-mattcl | 1.9 ± 0.2 | 1.5 | 2.6 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 2.7 | 1.02 ± 0.17 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.6 | 3.1 | 1.04 ± 0.17 |
| mattcl | input-mikofo | 2.1 ± 0.2 | 1.7 | 4.0 | 1.12 ± 0.18 |
| lanjian | input-mattcl | 39.6 ± 1.0 | 37.9 | 42.2 | 20.53 ± 2.52 |
| lanjian | input-lanjian | 43.2 ± 1.0 | 41.8 | 46.0 | 22.44 ± 2.75 |
| lanjian | input-kcen | 46.9 ± 0.9 | 45.5 | 49.5 | 24.35 ± 2.96 |
| lanjian | input-mikofo | 65.7 ± 0.9 | 64.3 | 68.0 | 34.11 ± 4.13 |
| mattcl-py | input-mattcl | 93.9 ± 1.1 | 92.1 | 97.0 | 48.73 ± 5.88 |
| mattcl-py | input-lanjian | 100.5 ± 1.4 | 97.4 | 103.6 | 52.19 ± 6.31 |
| mattcl-py | input-kcen | 108.3 ± 1.7 | 105.7 | 111.8 | 56.20 ± 6.81 |
| mattcl-py | input-mikofo | 143.9 ± 3.6 | 138.9 | 152.9 | 74.69 ± 9.17 |
| kcen | input-mattcl | 198.3 ± 4.4 | 190.8 | 206.8 | 102.94 ± 12.58 |
| kcen | input-lanjian | 208.1 ± 3.3 | 203.8 | 215.2 | 108.00 ± 13.09 |
| kcen | input-kcen | 242.7 ± 4.2 | 236.7 | 249.2 | 125.97 ± 15.29 |
| kcen | input-mikofo | 288.9 ± 4.3 | 281.6 | 296.2 | 149.95 ± 18.16 |
| mikofo | input-mattcl | 1399.1 ± 46.1 | 1347.6 | 1436.5 | 726.16 ± 90.47 |
| mikofo | input-lanjian | 1476.7 ± 34.3 | 1438.6 | 1504.9 | 766.47 ± 93.80 |
| mikofo | input-kcen | 1698.4 ± 42.3 | 1653.2 | 1737.1 | 881.50 ± 108.17 |
| mikofo | input-mikofo | 2092.7 ± 6.4 | 2086.0 | 2098.8 | 1086.16 ± 130.56 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|