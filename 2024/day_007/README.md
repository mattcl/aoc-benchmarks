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
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.1 | 2.7 | 1.00 |
| mattcl | input-kcen | 1.5 ± 0.2 | 1.1 | 2.7 | 1.00 ± 0.19 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.1 | 2.4 | 1.02 ± 0.19 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.1 | 2.5 | 1.02 ± 0.20 |
| lanjian | input-mattcl | 4.1 ± 0.3 | 3.5 | 5.3 | 2.81 ± 0.42 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 4.1 | 5.7 | 3.26 ± 0.45 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.5 | 5.6 | 3.46 ± 0.46 |
| lanjian | input-lanjian | 6.4 ± 0.2 | 5.9 | 7.3 | 4.39 ± 0.57 |
| mattcl-py | input-kcen | 47.6 ± 0.6 | 46.2 | 49.7 | 32.74 ± 4.10 |
| mattcl-py | input-lanjian | 47.9 ± 0.7 | 46.4 | 49.9 | 32.96 ± 4.13 |
| mattcl-py | input-mikofo | 48.1 ± 0.7 | 46.5 | 50.1 | 33.04 ± 4.15 |
| mattcl-py | input-mattcl | 48.2 ± 0.8 | 46.9 | 51.0 | 33.16 ± 4.17 |
| kcen | input-mattcl | 175.3 ± 1.4 | 171.7 | 177.5 | 120.54 ± 15.06 |
| kcen | input-mikofo | 214.7 ± 2.0 | 210.1 | 218.0 | 147.65 ± 18.46 |
| kcen | input-kcen | 227.2 ± 2.1 | 223.2 | 231.5 | 156.26 ± 19.53 |
| kcen | input-lanjian | 366.6 ± 1.7 | 363.4 | 369.2 | 252.11 ± 31.45 |
| mikofo | input-mattcl | 518.6 ± 13.8 | 509.8 | 543.0 | 356.63 ± 45.46 |
| mikofo | input-mikofo | 590.5 ± 16.4 | 576.8 | 618.5 | 406.03 ± 51.86 |
| mikofo | input-kcen | 694.1 ± 11.2 | 679.8 | 705.2 | 477.27 ± 59.99 |
| mikofo | input-lanjian | 993.8 ± 10.8 | 985.8 | 1006.0 | 683.35 ± 85.50 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|