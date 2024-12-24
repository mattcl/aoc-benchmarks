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
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.1 | 2.5 | 1.00 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.1 | 2.7 | 1.00 ± 0.22 |
| mattcl | input-kcen | 1.5 ± 0.2 | 1.1 | 2.4 | 1.02 ± 0.22 |
| mattcl | input-lanjian | 1.5 ± 0.3 | 1.0 | 2.7 | 1.02 ± 0.24 |
| lanjian | input-mattcl | 4.1 ± 0.3 | 3.6 | 5.2 | 2.79 ± 0.48 |
| lanjian | input-mikofo | 4.8 ± 0.2 | 4.2 | 5.8 | 3.26 ± 0.52 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.5 | 5.9 | 3.41 ± 0.54 |
| lanjian | input-lanjian | 6.3 ± 0.3 | 5.9 | 7.5 | 4.30 ± 0.68 |
| mattcl-py | input-kcen | 48.6 ± 0.8 | 47.1 | 52.4 | 32.97 ± 5.03 |
| mattcl-py | input-lanjian | 48.7 ± 0.6 | 47.2 | 49.9 | 33.06 ± 5.03 |
| mattcl-py | input-mikofo | 48.7 ± 0.5 | 47.3 | 50.4 | 33.09 ± 5.03 |
| mattcl-py | input-mattcl | 48.9 ± 0.8 | 47.3 | 52.0 | 33.21 ± 5.07 |
| kcen | input-mattcl | 177.2 ± 1.6 | 174.7 | 180.1 | 120.35 ± 18.28 |
| kcen | input-mikofo | 216.9 ± 2.0 | 213.5 | 219.9 | 147.26 ± 22.37 |
| kcen | input-kcen | 232.2 ± 3.5 | 227.6 | 238.8 | 157.70 ± 24.03 |
| kcen | input-lanjian | 370.7 ± 2.9 | 367.4 | 375.3 | 251.75 ± 38.22 |
| mikofo | input-mattcl | 530.2 ± 22.2 | 497.5 | 555.2 | 360.04 ± 56.64 |
| mikofo | input-mikofo | 580.8 ± 8.6 | 569.2 | 592.0 | 394.39 ± 60.08 |
| mikofo | input-kcen | 702.0 ± 7.5 | 694.5 | 708.7 | 476.74 ± 72.47 |
| mikofo | input-lanjian | 997.7 ± 6.8 | 990.3 | 1003.8 | 677.51 ± 102.83 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|