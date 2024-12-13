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
| mattcl | input-lanjian | 1.9 ± 0.2 | 1.4 | 2.4 | 1.00 |
| mattcl | input-mattcl | 1.9 ± 0.3 | 1.4 | 3.2 | 1.01 ± 0.19 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.5 | 2.6 | 1.05 ± 0.18 |
| mattcl | input-mikofo | 2.1 ± 0.2 | 1.7 | 2.9 | 1.11 ± 0.16 |
| lanjian | input-mattcl | 38.2 ± 0.9 | 36.9 | 41.1 | 20.39 ± 2.56 |
| lanjian | input-lanjian | 42.4 ± 1.0 | 40.7 | 44.6 | 22.64 ± 2.84 |
| lanjian | input-kcen | 45.7 ± 1.2 | 44.0 | 48.7 | 24.39 ± 3.07 |
| lanjian | input-mikofo | 63.6 ± 1.0 | 62.1 | 66.6 | 33.94 ± 4.21 |
| mattcl-py | input-mattcl | 94.7 ± 1.2 | 92.1 | 97.8 | 50.53 ± 6.25 |
| mattcl-py | input-lanjian | 101.0 ± 1.3 | 97.6 | 103.1 | 53.84 ± 6.67 |
| mattcl-py | input-kcen | 108.2 ± 1.7 | 105.0 | 112.1 | 57.69 ± 7.16 |
| mattcl-py | input-mikofo | 143.9 ± 3.6 | 138.0 | 153.0 | 76.75 ± 9.65 |
| kcen | input-mattcl | 201.3 ± 2.6 | 196.9 | 206.5 | 107.38 ± 13.29 |
| kcen | input-lanjian | 209.1 ± 3.7 | 202.0 | 213.7 | 111.51 ± 13.87 |
| kcen | input-kcen | 242.6 ± 5.4 | 234.1 | 252.3 | 129.39 ± 16.18 |
| kcen | input-mikofo | 293.1 ± 3.8 | 287.1 | 298.4 | 156.35 ± 19.35 |
| mikofo | input-mattcl | 1391.7 ± 33.8 | 1357.2 | 1424.6 | 742.27 ± 93.12 |
| mikofo | input-lanjian | 1484.5 ± 41.2 | 1437.3 | 1513.2 | 791.76 ± 99.90 |
| mikofo | input-kcen | 1679.7 ± 32.7 | 1642.5 | 1704.0 | 895.88 ± 111.64 |
| mikofo | input-mikofo | 2104.7 ± 24.9 | 2077.8 | 2126.9 | 1122.60 ± 138.81 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|