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
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.1 | 2.6 | 1.00 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.1 | 2.7 | 1.00 ± 0.17 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.0 | 1.01 ± 0.16 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.3 | 1.01 ± 0.17 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.6 | 5.2 | 2.80 ± 0.37 |
| lanjian | input-mikofo | 4.6 ± 0.3 | 3.8 | 5.4 | 3.19 ± 0.42 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.4 | 5.8 | 3.53 ± 0.43 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 7.3 | 4.39 ± 0.51 |
| mattcl-py | input-kcen | 47.6 ± 0.8 | 45.6 | 50.9 | 33.36 ± 3.80 |
| mattcl-py | input-lanjian | 48.0 ± 0.7 | 46.9 | 49.7 | 33.63 ± 3.82 |
| mattcl-py | input-mattcl | 48.3 ± 0.7 | 46.5 | 49.9 | 33.82 ± 3.84 |
| mattcl-py | input-mikofo | 48.3 ± 0.8 | 46.6 | 50.4 | 33.84 ± 3.85 |
| kcen | input-mattcl | 174.1 ± 2.9 | 169.4 | 182.2 | 121.91 ± 13.89 |
| kcen | input-mikofo | 214.2 ± 3.1 | 209.4 | 218.3 | 149.97 ± 17.03 |
| kcen | input-kcen | 221.9 ± 2.0 | 218.7 | 225.1 | 155.38 ± 17.56 |
| kcen | input-lanjian | 363.1 ± 4.0 | 357.2 | 368.4 | 254.28 ± 28.79 |
| mikofo | input-mattcl | 519.0 ± 15.9 | 506.6 | 545.2 | 363.43 ± 42.42 |
| mikofo | input-mikofo | 580.0 ± 13.6 | 566.7 | 599.1 | 406.08 ± 46.73 |
| mikofo | input-kcen | 687.0 ± 17.2 | 666.1 | 707.9 | 481.01 ± 55.51 |
| mikofo | input-lanjian | 983.8 ± 6.7 | 977.3 | 990.6 | 688.86 ± 77.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|