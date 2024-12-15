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
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 1.8 | 1.00 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.4 | 1.00 ± 0.16 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.4 | 1.01 ± 0.19 |
| mattcl | input-mattcl | 1.4 ± 0.1 | 1.1 | 1.8 | 1.01 ± 0.15 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.5 | 5.0 | 2.87 ± 0.37 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 3.9 | 5.6 | 3.39 ± 0.43 |
| lanjian | input-kcen | 5.0 ± 0.3 | 4.3 | 5.9 | 3.57 ± 0.44 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.7 | 7.2 | 4.53 ± 0.52 |
| mattcl-py | input-kcen | 47.2 ± 0.4 | 46.1 | 48.2 | 33.86 ± 3.73 |
| mattcl-py | input-mattcl | 47.4 ± 0.5 | 46.2 | 48.6 | 34.01 ± 3.76 |
| mattcl-py | input-mikofo | 47.5 ± 0.7 | 46.2 | 49.7 | 34.07 ± 3.78 |
| mattcl-py | input-lanjian | 47.8 ± 0.7 | 46.8 | 50.6 | 34.27 ± 3.80 |
| kcen | input-mattcl | 176.5 ± 2.0 | 173.6 | 179.8 | 126.53 ± 13.99 |
| kcen | input-mikofo | 216.3 ± 2.6 | 212.5 | 220.6 | 155.08 ± 17.15 |
| kcen | input-kcen | 227.4 ± 2.1 | 224.7 | 232.2 | 163.04 ± 17.99 |
| kcen | input-lanjian | 371.5 ± 2.8 | 368.1 | 375.5 | 266.36 ± 29.35 |
| mikofo | input-mattcl | 520.3 ± 21.2 | 489.6 | 539.2 | 373.01 ± 43.73 |
| mikofo | input-mikofo | 576.4 ± 15.4 | 553.9 | 589.0 | 413.21 ± 46.75 |
| mikofo | input-kcen | 686.6 ± 7.7 | 676.3 | 693.6 | 492.24 ± 54.40 |
| mikofo | input-lanjian | 983.0 ± 6.1 | 976.0 | 986.9 | 704.74 ± 77.59 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|