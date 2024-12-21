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
| mattcl | input-lanjian | 1.9 ± 0.2 | 1.4 | 2.7 | 1.02 ± 0.17 |
| mattcl | input-kcen | 2.0 ± 0.3 | 1.6 | 4.3 | 1.06 ± 0.20 |
| mattcl | input-mikofo | 2.1 ± 0.2 | 1.7 | 3.1 | 1.12 ± 0.16 |
| lanjian | input-mattcl | 38.8 ± 1.5 | 37.1 | 48.8 | 20.41 ± 2.51 |
| lanjian | input-lanjian | 42.6 ± 1.1 | 40.7 | 45.3 | 22.39 ± 2.67 |
| lanjian | input-kcen | 46.4 ± 1.2 | 44.0 | 49.4 | 24.38 ± 2.91 |
| lanjian | input-mikofo | 64.3 ± 1.2 | 61.9 | 67.3 | 33.83 ± 3.99 |
| mattcl-py | input-mattcl | 93.9 ± 1.4 | 90.9 | 97.5 | 49.39 ± 5.80 |
| mattcl-py | input-lanjian | 101.1 ± 1.6 | 98.3 | 104.3 | 53.17 ± 6.25 |
| mattcl-py | input-kcen | 107.4 ± 1.8 | 104.8 | 113.1 | 56.47 ± 6.65 |
| mattcl-py | input-mikofo | 143.3 ± 3.5 | 139.2 | 150.0 | 75.34 ± 8.97 |
| kcen | input-mattcl | 199.9 ± 2.9 | 196.1 | 207.6 | 105.10 ± 12.34 |
| kcen | input-lanjian | 206.1 ± 4.1 | 198.5 | 210.5 | 108.36 ± 12.81 |
| kcen | input-kcen | 273.7 ± 111.2 | 235.0 | 626.4 | 143.87 ± 60.84 |
| kcen | input-mikofo | 289.6 ± 4.1 | 282.9 | 295.2 | 152.25 ± 17.87 |
| mikofo | input-mattcl | 1387.0 ± 24.5 | 1359.0 | 1404.3 | 729.17 ± 85.93 |
| mikofo | input-lanjian | 1457.5 ± 27.1 | 1428.7 | 1482.5 | 766.25 ± 90.41 |
| mikofo | input-kcen | 1684.3 ± 37.3 | 1642.2 | 1713.2 | 885.47 ± 105.02 |
| mikofo | input-mikofo | 2058.8 ± 33.7 | 2037.2 | 2097.6 | 1082.34 ± 127.35 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|