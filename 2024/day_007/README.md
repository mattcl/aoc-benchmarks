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
| mattcl | input-kcen | 1.4 ± 0.3 | 1.1 | 2.7 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.1 | 2.7 | 1.00 ± 0.24 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.1 | 2.7 | 1.01 ± 0.24 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.1 | 2.5 | 1.01 ± 0.23 |
| lanjian | input-mattcl | 4.3 ± 0.4 | 3.6 | 5.4 | 2.99 ± 0.61 |
| lanjian | input-mikofo | 4.8 ± 0.3 | 4.0 | 5.7 | 3.32 ± 0.62 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.5 | 5.9 | 3.50 ± 0.64 |
| lanjian | input-lanjian | 6.4 ± 0.2 | 5.9 | 7.2 | 4.41 ± 0.80 |
| mattcl-py | input-kcen | 47.9 ± 0.6 | 46.3 | 48.8 | 33.19 ± 5.87 |
| mattcl-py | input-mikofo | 48.1 ± 0.7 | 46.9 | 51.0 | 33.39 ± 5.91 |
| mattcl-py | input-mattcl | 48.1 ± 0.6 | 46.5 | 50.1 | 33.40 ± 5.91 |
| mattcl-py | input-lanjian | 48.2 ± 0.9 | 46.9 | 52.8 | 33.45 ± 5.93 |
| kcen | input-mattcl | 175.7 ± 2.9 | 171.8 | 184.9 | 121.85 ± 21.60 |
| kcen | input-mikofo | 214.5 ± 1.3 | 212.6 | 217.0 | 148.80 ± 26.28 |
| kcen | input-kcen | 225.5 ± 2.5 | 221.5 | 228.9 | 156.43 ± 27.67 |
| kcen | input-lanjian | 365.3 ± 4.3 | 356.5 | 369.8 | 253.38 ± 44.83 |
| mikofo | input-mattcl | 521.8 ± 13.9 | 510.8 | 546.2 | 361.91 ± 64.61 |
| mikofo | input-mikofo | 582.9 ± 6.2 | 577.5 | 592.7 | 404.29 ± 71.49 |
| mikofo | input-kcen | 680.0 ± 13.6 | 667.5 | 699.0 | 471.63 ± 83.79 |
| mikofo | input-lanjian | 987.7 ± 7.3 | 979.3 | 992.9 | 685.06 ± 121.03 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|