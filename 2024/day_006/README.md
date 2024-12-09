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
| mattcl | input-mattcl | 2.1 ± 0.2 | 1.7 | 3.3 | 1.00 |
| mattcl | input-lanjian | 2.1 ± 0.1 | 1.8 | 2.9 | 1.01 ± 0.12 |
| mattcl | input-kcen | 2.3 ± 0.4 | 1.8 | 6.2 | 1.09 ± 0.20 |
| mattcl | input-mikofo | 2.5 ± 0.2 | 2.1 | 3.7 | 1.19 ± 0.15 |
| lanjian | input-mattcl | 38.5 ± 1.6 | 36.8 | 48.6 | 18.44 ± 1.87 |
| lanjian | input-lanjian | 42.1 ± 1.0 | 40.3 | 44.9 | 20.12 ± 1.92 |
| lanjian | input-kcen | 45.3 ± 0.9 | 43.5 | 47.6 | 21.67 ± 2.04 |
| lanjian | input-mikofo | 63.3 ± 1.0 | 61.5 | 66.0 | 30.28 ± 2.84 |
| mattcl-py | input-mattcl | 94.5 ± 1.1 | 92.3 | 96.5 | 45.21 ± 4.21 |
| mattcl-py | input-lanjian | 102.1 ± 1.8 | 98.9 | 106.7 | 48.83 ± 4.58 |
| mattcl-py | input-kcen | 108.0 ± 1.6 | 104.8 | 111.3 | 51.67 ± 4.83 |
| mattcl-py | input-mikofo | 144.0 ± 3.3 | 139.6 | 151.9 | 68.91 ± 6.55 |
| kcen | input-mattcl | 350.9 ± 5.2 | 340.8 | 356.7 | 167.91 ± 15.69 |
| kcen | input-lanjian | 361.4 ± 6.1 | 353.6 | 372.6 | 172.91 ± 16.22 |
| kcen | input-kcen | 413.4 ± 4.2 | 408.8 | 418.3 | 197.81 ± 18.37 |
| kcen | input-mikofo | 535.9 ± 8.3 | 529.1 | 549.8 | 256.39 ± 23.99 |
| mikofo | input-mattcl | 1388.6 ± 25.2 | 1372.1 | 1417.7 | 664.40 ± 62.49 |
| mikofo | input-lanjian | 1441.5 ± 29.1 | 1414.7 | 1472.4 | 689.69 ± 65.15 |
| mikofo | input-kcen | 1689.3 ± 52.9 | 1629.8 | 1731.1 | 808.24 ± 78.77 |
| mikofo | input-mikofo | 2059.6 ± 10.7 | 2048.2 | 2069.3 | 985.42 ± 91.08 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|