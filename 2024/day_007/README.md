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
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.1 | 2.6 | 1.00 ± 0.22 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.5 | 1.00 ± 0.22 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.0 | 2.4 | 1.02 ± 0.23 |
| lanjian | input-mattcl | 4.1 ± 0.3 | 3.5 | 5.1 | 2.86 ± 0.51 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 4.0 | 5.6 | 3.25 ± 0.57 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.4 | 5.7 | 3.48 ± 0.58 |
| lanjian | input-lanjian | 6.4 ± 0.2 | 5.8 | 7.0 | 4.42 ± 0.73 |
| mattcl-py | input-kcen | 48.3 ± 0.7 | 47.2 | 50.6 | 33.56 ± 5.41 |
| mattcl-py | input-mattcl | 48.6 ± 0.7 | 46.5 | 50.1 | 33.74 ± 5.44 |
| mattcl-py | input-mikofo | 48.6 ± 0.7 | 47.1 | 51.7 | 33.77 ± 5.44 |
| mattcl-py | input-lanjian | 48.6 ± 0.8 | 47.1 | 51.8 | 33.79 ± 5.46 |
| kcen | input-mattcl | 178.5 ± 6.4 | 174.8 | 201.9 | 124.01 ± 20.41 |
| kcen | input-mikofo | 218.3 ± 2.3 | 215.6 | 223.8 | 151.72 ± 24.42 |
| kcen | input-kcen | 228.4 ± 2.2 | 224.0 | 232.1 | 158.73 ± 25.54 |
| kcen | input-lanjian | 370.6 ± 7.6 | 361.0 | 384.8 | 257.56 ± 41.70 |
| mikofo | input-mattcl | 522.8 ± 9.3 | 514.2 | 534.7 | 363.30 ± 58.71 |
| mikofo | input-mikofo | 576.1 ± 9.8 | 564.6 | 586.3 | 400.36 ± 64.67 |
| mikofo | input-kcen | 677.8 ± 4.7 | 673.3 | 683.3 | 471.00 ± 75.72 |
| mikofo | input-lanjian | 1001.0 ± 21.4 | 977.6 | 1019.6 | 695.64 ± 112.72 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|