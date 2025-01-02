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
| mattcl | input-kcen | 1.5 ± 0.2 | 1.1 | 2.4 | 1.00 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.1 | 2.4 | 1.00 ± 0.17 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.1 | 2.6 | 1.01 ± 0.19 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.0 | 2.5 | 1.02 ± 0.19 |
| lanjian | input-mattcl | 4.1 ± 0.3 | 3.6 | 5.4 | 2.77 ± 0.40 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 4.0 | 5.6 | 3.24 ± 0.47 |
| lanjian | input-kcen | 5.1 ± 0.2 | 4.4 | 5.8 | 3.47 ± 0.46 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.9 | 7.3 | 4.31 ± 0.57 |
| mattcl-py | input-kcen | 47.6 ± 0.6 | 46.4 | 49.6 | 32.55 ± 4.17 |
| mattcl-py | input-mikofo | 47.7 ± 0.6 | 46.4 | 49.4 | 32.63 ± 4.18 |
| mattcl-py | input-mattcl | 47.9 ± 0.7 | 46.3 | 51.7 | 32.79 ± 4.21 |
| mattcl-py | input-lanjian | 48.1 ± 0.6 | 47.1 | 50.8 | 32.90 ± 4.22 |
| kcen | input-mattcl | 178.1 ± 2.2 | 173.9 | 180.9 | 121.86 ± 15.62 |
| kcen | input-mikofo | 216.8 ± 3.6 | 211.4 | 221.8 | 148.39 ± 19.09 |
| kcen | input-kcen | 228.0 ± 2.6 | 224.5 | 233.2 | 155.99 ± 19.98 |
| kcen | input-lanjian | 368.3 ± 3.6 | 363.3 | 375.2 | 252.00 ± 32.24 |
| mikofo | input-mattcl | 527.0 ± 7.2 | 517.7 | 535.4 | 360.61 ± 46.26 |
| mikofo | input-mikofo | 571.7 ± 10.0 | 557.4 | 582.4 | 391.23 ± 50.37 |
| mikofo | input-kcen | 705.7 ± 24.7 | 677.3 | 734.3 | 482.95 ± 63.87 |
| mikofo | input-lanjian | 989.2 ± 13.3 | 974.6 | 1000.6 | 676.94 ± 86.82 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|