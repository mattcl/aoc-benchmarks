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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.2 | 1.00 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.1 | 2.2 | 1.01 ± 0.16 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.3 | 1.02 ± 0.18 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.4 | 1.02 ± 0.17 |
| lanjian | input-mattcl | 3.9 ± 0.2 | 3.5 | 5.0 | 2.79 ± 0.38 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 3.9 | 5.5 | 3.35 ± 0.45 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.2 | 6.1 | 3.56 ± 0.46 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.7 | 7.0 | 4.49 ± 0.56 |
| mattcl-py | input-kcen | 47.9 ± 0.7 | 46.6 | 50.3 | 34.19 ± 4.11 |
| mattcl-py | input-lanjian | 48.5 ± 0.6 | 47.3 | 50.0 | 34.61 ± 4.15 |
| mattcl-py | input-mikofo | 48.5 ± 0.6 | 47.1 | 49.7 | 34.64 ± 4.15 |
| mattcl-py | input-mattcl | 48.6 ± 0.7 | 47.2 | 50.8 | 34.69 ± 4.17 |
| kcen | input-mattcl | 172.0 ± 1.5 | 169.3 | 174.6 | 122.73 ± 14.69 |
| kcen | input-mikofo | 212.5 ± 2.7 | 210.0 | 220.5 | 151.66 ± 18.21 |
| kcen | input-kcen | 224.5 ± 2.6 | 220.2 | 229.5 | 160.21 ± 19.22 |
| kcen | input-lanjian | 361.4 ± 1.3 | 360.1 | 364.0 | 257.95 ± 30.81 |
| mikofo | input-mattcl | 515.7 ± 9.2 | 503.1 | 526.3 | 368.00 ± 44.42 |
| mikofo | input-mikofo | 581.5 ± 10.5 | 565.0 | 593.7 | 414.98 ± 50.11 |
| mikofo | input-kcen | 690.2 ± 11.3 | 680.1 | 700.9 | 492.57 ± 59.35 |
| mikofo | input-lanjian | 992.5 ± 11.5 | 983.0 | 1005.3 | 708.29 ± 84.95 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|