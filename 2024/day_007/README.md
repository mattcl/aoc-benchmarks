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
| mattcl | input-kcen | 1.5 ± 0.2 | 1.1 | 2.3 | 1.00 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.2 | 2.7 | 1.01 ± 0.18 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.2 | 2.7 | 1.01 ± 0.19 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.2 | 2.4 | 1.02 ± 0.17 |
| lanjian | input-mattcl | 4.1 ± 0.3 | 3.6 | 5.5 | 2.73 ± 0.38 |
| lanjian | input-mikofo | 4.8 ± 0.3 | 3.9 | 5.7 | 3.23 ± 0.43 |
| lanjian | input-kcen | 5.1 ± 0.2 | 4.5 | 5.8 | 3.39 ± 0.43 |
| lanjian | input-lanjian | 6.4 ± 0.2 | 5.9 | 7.2 | 4.29 ± 0.54 |
| mattcl-py | input-kcen | 47.8 ± 0.5 | 46.7 | 49.2 | 32.06 ± 3.88 |
| mattcl-py | input-lanjian | 48.1 ± 0.6 | 46.8 | 49.5 | 32.23 ± 3.91 |
| mattcl-py | input-mattcl | 48.4 ± 0.7 | 47.2 | 50.3 | 32.42 ± 3.94 |
| mattcl-py | input-mikofo | 48.4 ± 0.6 | 47.0 | 49.9 | 32.42 ± 3.93 |
| kcen | input-mattcl | 174.5 ± 2.6 | 171.1 | 180.5 | 116.93 ± 14.22 |
| kcen | input-mikofo | 213.1 ± 2.0 | 210.7 | 217.1 | 142.84 ± 17.29 |
| kcen | input-kcen | 226.6 ± 1.8 | 223.2 | 229.0 | 151.88 ± 18.37 |
| kcen | input-lanjian | 366.0 ± 2.1 | 362.7 | 368.6 | 245.26 ± 29.63 |
| mikofo | input-mattcl | 525.6 ± 17.1 | 506.5 | 545.6 | 352.23 ± 44.03 |
| mikofo | input-mikofo | 574.5 ± 12.0 | 563.5 | 594.5 | 385.01 ± 47.15 |
| mikofo | input-kcen | 695.5 ± 8.8 | 689.0 | 708.5 | 466.13 ± 56.57 |
| mikofo | input-lanjian | 1018.1 ± 12.7 | 1004.8 | 1030.0 | 682.27 ± 82.78 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|