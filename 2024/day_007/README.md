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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.5 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.6 | 1.01 ± 0.21 |
| mattcl | input-lanjian | 1.4 ± 0.3 | 1.0 | 5.4 | 1.02 ± 0.27 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.1 | 2.4 | 1.02 ± 0.19 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.5 | 4.7 | 2.79 ± 0.41 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 4.0 | 5.7 | 3.30 ± 0.50 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.3 | 6.1 | 3.54 ± 0.49 |
| lanjian | input-lanjian | 6.5 ± 0.7 | 5.8 | 11.3 | 4.57 ± 0.76 |
| mattcl-py | input-kcen | 48.1 ± 0.6 | 47.1 | 50.9 | 33.93 ± 4.49 |
| mattcl-py | input-mikofo | 48.4 ± 0.6 | 46.8 | 49.8 | 34.14 ± 4.52 |
| mattcl-py | input-mattcl | 48.4 ± 0.7 | 46.9 | 50.6 | 34.17 ± 4.53 |
| mattcl-py | input-lanjian | 48.5 ± 0.9 | 47.1 | 52.3 | 34.24 ± 4.55 |
| kcen | input-mattcl | 175.7 ± 1.4 | 174.2 | 178.7 | 123.90 ± 16.35 |
| kcen | input-mikofo | 215.0 ± 1.9 | 212.6 | 217.3 | 151.67 ± 20.02 |
| kcen | input-kcen | 227.2 ± 2.0 | 222.3 | 230.8 | 160.23 ± 21.15 |
| kcen | input-lanjian | 365.2 ± 5.0 | 356.5 | 371.8 | 257.59 ± 34.11 |
| mikofo | input-mattcl | 524.7 ± 11.0 | 510.7 | 536.7 | 370.12 ± 49.36 |
| mikofo | input-mikofo | 585.5 ± 8.5 | 575.3 | 593.4 | 413.00 ± 54.73 |
| mikofo | input-kcen | 682.4 ± 11.0 | 672.7 | 695.6 | 481.32 ± 63.87 |
| mikofo | input-lanjian | 1007.4 ± 8.1 | 998.8 | 1014.8 | 710.55 ± 93.76 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|