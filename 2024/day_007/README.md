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
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.5 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.1 | 1.9 | 1.00 ± 0.18 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.4 | 1.00 ± 0.19 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.4 | 1.01 ± 0.19 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.5 | 5.2 | 2.79 ± 0.45 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 3.8 | 5.5 | 3.31 ± 0.50 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.4 | 5.8 | 3.54 ± 0.52 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 7.0 | 4.42 ± 0.64 |
| mattcl-py | input-kcen | 47.3 ± 0.5 | 46.2 | 48.6 | 33.24 ± 4.70 |
| mattcl-py | input-mattcl | 47.7 ± 0.6 | 46.6 | 49.0 | 33.52 ± 4.74 |
| mattcl-py | input-mikofo | 47.7 ± 0.6 | 46.4 | 50.8 | 33.53 ± 4.75 |
| mattcl-py | input-lanjian | 47.8 ± 0.6 | 46.2 | 49.6 | 33.58 ± 4.75 |
| kcen | input-mattcl | 176.1 ± 2.2 | 172.1 | 179.0 | 123.84 ± 17.53 |
| kcen | input-mikofo | 215.1 ± 2.4 | 210.6 | 219.0 | 151.20 ± 21.39 |
| kcen | input-kcen | 226.8 ± 2.9 | 222.0 | 233.5 | 159.46 ± 22.58 |
| kcen | input-lanjian | 366.4 ± 4.7 | 361.1 | 374.3 | 257.61 ± 36.47 |
| mikofo | input-mattcl | 526.9 ± 13.9 | 509.1 | 542.6 | 370.48 ± 53.15 |
| mikofo | input-mikofo | 574.0 ± 7.4 | 566.7 | 583.1 | 403.57 ± 57.14 |
| mikofo | input-kcen | 684.9 ± 14.2 | 666.0 | 699.3 | 481.53 ± 68.63 |
| mikofo | input-lanjian | 990.2 ± 19.4 | 971.3 | 1010.1 | 696.20 ± 99.11 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|