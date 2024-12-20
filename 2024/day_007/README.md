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
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.1 | 2.4 | 1.00 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.4 | 1.01 ± 0.19 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.2 | 1.01 ± 0.18 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.0 | 2.6 | 1.03 ± 0.21 |
| lanjian | input-mattcl | 4.1 ± 0.4 | 3.6 | 5.6 | 2.89 ± 0.48 |
| lanjian | input-mikofo | 4.8 ± 0.3 | 4.1 | 5.6 | 3.37 ± 0.49 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.4 | 6.0 | 3.54 ± 0.50 |
| lanjian | input-lanjian | 6.4 ± 0.2 | 5.8 | 7.3 | 4.51 ± 0.64 |
| mattcl-py | input-kcen | 48.0 ± 0.8 | 46.6 | 52.3 | 33.93 ± 4.64 |
| mattcl-py | input-lanjian | 48.2 ± 0.6 | 47.0 | 49.3 | 34.10 ± 4.65 |
| mattcl-py | input-mattcl | 48.3 ± 0.6 | 47.4 | 50.5 | 34.13 ± 4.65 |
| mattcl-py | input-mikofo | 48.3 ± 0.5 | 47.3 | 49.7 | 34.15 ± 4.65 |
| kcen | input-mattcl | 175.5 ± 1.5 | 171.7 | 177.6 | 124.01 ± 16.87 |
| kcen | input-mikofo | 216.1 ± 2.3 | 213.0 | 222.6 | 152.77 ± 20.81 |
| kcen | input-kcen | 226.3 ± 2.6 | 222.8 | 231.2 | 159.94 ± 21.79 |
| kcen | input-lanjian | 366.1 ± 1.0 | 364.4 | 367.3 | 258.79 ± 35.15 |
| mikofo | input-mattcl | 511.6 ± 11.6 | 493.5 | 525.6 | 361.58 ± 49.78 |
| mikofo | input-mikofo | 584.9 ± 10.4 | 568.2 | 594.1 | 413.41 ± 56.61 |
| mikofo | input-kcen | 692.6 ± 13.4 | 673.2 | 703.4 | 489.50 ± 67.14 |
| mikofo | input-lanjian | 1005.1 ± 10.5 | 993.8 | 1014.7 | 710.39 ± 96.74 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|