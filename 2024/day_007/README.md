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
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.2 | 2.6 | 1.00 |
| mattcl | input-kcen | 1.5 ± 0.2 | 1.1 | 2.4 | 1.01 ± 0.17 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.1 | 2.5 | 1.02 ± 0.18 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.1 | 2.6 | 1.04 ± 0.19 |
| lanjian | input-mattcl | 4.1 ± 0.3 | 3.6 | 5.3 | 2.80 ± 0.38 |
| lanjian | input-mikofo | 4.7 ± 0.4 | 4.0 | 5.6 | 3.21 ± 0.44 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.4 | 6.0 | 3.45 ± 0.43 |
| lanjian | input-lanjian | 6.3 ± 0.3 | 5.7 | 7.3 | 4.32 ± 0.52 |
| mattcl-py | input-kcen | 47.9 ± 0.7 | 46.9 | 51.5 | 32.75 ± 3.74 |
| mattcl-py | input-mikofo | 47.9 ± 0.6 | 46.4 | 49.8 | 32.76 ± 3.74 |
| mattcl-py | input-mattcl | 48.0 ± 0.5 | 46.8 | 49.3 | 32.80 ± 3.73 |
| mattcl-py | input-lanjian | 48.0 ± 0.5 | 46.4 | 49.3 | 32.86 ± 3.74 |
| kcen | input-mattcl | 178.1 ± 2.8 | 172.9 | 183.1 | 121.86 ± 13.94 |
| kcen | input-mikofo | 218.4 ± 3.5 | 213.2 | 223.8 | 149.43 ± 17.11 |
| kcen | input-kcen | 229.0 ± 2.8 | 225.2 | 233.4 | 156.67 ± 17.87 |
| kcen | input-lanjian | 374.8 ± 3.1 | 369.8 | 378.1 | 256.42 ± 29.15 |
| mikofo | input-mattcl | 527.8 ± 19.6 | 497.9 | 548.9 | 361.06 ± 43.06 |
| mikofo | input-mikofo | 601.6 ± 17.6 | 586.4 | 618.6 | 411.57 ± 48.18 |
| mikofo | input-kcen | 697.8 ± 13.4 | 678.2 | 708.1 | 477.35 ± 54.89 |
| mikofo | input-lanjian | 999.4 ± 12.0 | 986.4 | 1010.0 | 683.68 ± 77.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|