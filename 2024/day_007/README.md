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
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.1 | 2.2 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.4 | 1.00 ± 0.19 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.5 | 1.00 ± 0.19 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.0 | 2.5 | 1.02 ± 0.18 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.4 | 4.9 | 2.81 ± 0.38 |
| lanjian | input-mikofo | 4.8 ± 0.3 | 3.9 | 5.5 | 3.31 ± 0.42 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.5 | 5.8 | 3.49 ± 0.42 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.9 | 7.1 | 4.38 ± 0.52 |
| mattcl-py | input-kcen | 47.4 ± 0.5 | 46.0 | 48.6 | 32.87 ± 3.75 |
| mattcl-py | input-mattcl | 47.6 ± 0.5 | 46.3 | 49.5 | 33.05 ± 3.77 |
| mattcl-py | input-mikofo | 47.6 ± 0.6 | 46.4 | 49.0 | 33.06 ± 3.77 |
| mattcl-py | input-lanjian | 47.8 ± 0.5 | 46.9 | 50.2 | 33.18 ± 3.79 |
| kcen | input-mattcl | 176.5 ± 2.1 | 173.8 | 180.6 | 122.52 ± 13.99 |
| kcen | input-mikofo | 215.6 ± 3.2 | 211.0 | 219.7 | 149.66 ± 17.14 |
| kcen | input-kcen | 227.6 ± 4.0 | 222.2 | 238.9 | 157.98 ± 18.15 |
| kcen | input-lanjian | 369.9 ± 3.0 | 363.4 | 373.1 | 256.74 ± 29.22 |
| mikofo | input-mattcl | 516.5 ± 14.7 | 500.3 | 535.1 | 358.49 ± 41.95 |
| mikofo | input-mikofo | 572.0 ± 11.9 | 556.7 | 585.5 | 397.04 ± 45.82 |
| mikofo | input-kcen | 688.3 ± 9.5 | 674.3 | 694.3 | 477.80 ± 54.65 |
| mikofo | input-lanjian | 989.0 ± 2.5 | 986.1 | 990.8 | 686.48 ± 77.96 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|