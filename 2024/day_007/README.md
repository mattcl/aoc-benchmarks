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
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.1 | 2.5 | 1.00 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.1 | 2.3 | 1.00 ± 0.17 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.4 | 1.01 ± 0.19 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.5 | 1.03 ± 0.21 |
| lanjian | input-mattcl | 3.9 ± 0.2 | 3.5 | 4.8 | 2.81 ± 0.37 |
| lanjian | input-mikofo | 4.8 ± 0.5 | 3.9 | 9.0 | 3.47 ± 0.52 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.3 | 6.1 | 3.59 ± 0.45 |
| lanjian | input-lanjian | 6.3 ± 0.3 | 5.8 | 7.3 | 4.53 ± 0.56 |
| mattcl-py | input-kcen | 48.3 ± 0.8 | 46.9 | 51.8 | 34.59 ± 4.07 |
| mattcl-py | input-mattcl | 48.6 ± 0.6 | 47.0 | 50.1 | 34.76 ± 4.08 |
| mattcl-py | input-lanjian | 48.6 ± 0.6 | 47.4 | 50.5 | 34.77 ± 4.08 |
| mattcl-py | input-mikofo | 48.7 ± 0.7 | 47.0 | 51.5 | 34.85 ± 4.10 |
| kcen | input-mattcl | 176.1 ± 1.6 | 173.0 | 179.2 | 126.06 ± 14.75 |
| kcen | input-mikofo | 214.2 ± 1.4 | 211.6 | 217.1 | 153.36 ± 17.91 |
| kcen | input-kcen | 224.3 ± 1.9 | 221.3 | 227.6 | 160.57 ± 18.78 |
| kcen | input-lanjian | 365.3 ± 1.9 | 362.2 | 367.3 | 261.52 ± 30.53 |
| mikofo | input-mattcl | 520.8 ± 11.1 | 512.6 | 540.0 | 372.82 ± 44.20 |
| mikofo | input-mikofo | 578.0 ± 16.5 | 561.2 | 600.3 | 413.74 ± 49.68 |
| mikofo | input-kcen | 707.9 ± 16.5 | 687.7 | 725.0 | 506.71 ± 60.26 |
| mikofo | input-lanjian | 990.2 ± 27.9 | 968.8 | 1021.7 | 708.83 ± 85.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|