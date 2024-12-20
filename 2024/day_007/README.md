# Day 7 benchmarks

[link to problem](https://adventofcode.com/2024/day/7)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 7)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)
- [mikofo](https://github.com/mikofo/aoc2024) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.1 | 2.5 | 1.00 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.1 | 2.5 | 1.00 ± 0.18 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.1 | 2.6 | 1.01 ± 0.20 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.1 | 2.3 | 1.01 ± 0.18 |
| lanjian | input-mattcl | 4.1 ± 0.4 | 3.6 | 5.4 | 2.84 ± 0.43 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 4.0 | 5.5 | 3.30 ± 0.45 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.4 | 5.8 | 3.51 ± 0.45 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.7 | 6.9 | 4.35 ± 0.54 |
| mattcl-py | input-kcen | 47.3 ± 0.6 | 46.0 | 49.4 | 32.92 ± 4.01 |
| mattcl-py | input-mikofo | 47.7 ± 0.6 | 46.5 | 48.7 | 33.18 ± 4.04 |
| mattcl-py | input-mattcl | 47.8 ± 0.7 | 46.7 | 50.7 | 33.27 ± 4.06 |
| mattcl-py | input-lanjian | 48.0 ± 0.8 | 46.6 | 50.2 | 33.40 ± 4.08 |
| kcen | input-mattcl | 176.4 ± 2.2 | 173.0 | 180.5 | 122.76 ± 14.94 |
| kcen | input-mikofo | 216.5 ± 2.1 | 212.1 | 220.2 | 150.66 ± 18.30 |
| kcen | input-kcen | 227.8 ± 3.0 | 223.9 | 234.8 | 158.50 ± 19.30 |
| kcen | input-lanjian | 371.4 ± 5.4 | 363.1 | 382.8 | 258.39 ± 31.50 |
| mikofo | input-mattcl | 518.7 ± 14.4 | 497.4 | 533.4 | 360.86 ± 44.81 |
| mikofo | input-mikofo | 570.9 ± 11.5 | 554.9 | 586.0 | 397.19 ± 48.74 |
| mikofo | input-kcen | 695.8 ± 3.4 | 692.1 | 699.9 | 484.09 ± 58.65 |
| mikofo | input-lanjian | 985.5 ± 10.5 | 973.8 | 994.2 | 685.65 ± 83.32 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|