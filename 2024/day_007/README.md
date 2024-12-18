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
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.1 | 2.0 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.1 | 2.5 | 1.01 ± 0.17 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.1 | 2.5 | 1.01 ± 0.17 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.7 | 1.01 ± 0.19 |
| lanjian | input-mattcl | 3.9 ± 0.3 | 3.5 | 5.2 | 2.76 ± 0.35 |
| lanjian | input-mikofo | 4.8 ± 0.3 | 3.9 | 5.6 | 3.35 ± 0.41 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.4 | 5.8 | 3.53 ± 0.42 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 7.0 | 4.42 ± 0.51 |
| mattcl-py | input-kcen | 48.0 ± 0.7 | 46.6 | 49.8 | 33.57 ± 3.67 |
| mattcl-py | input-mikofo | 48.4 ± 0.7 | 47.1 | 51.5 | 33.90 ± 3.70 |
| mattcl-py | input-mattcl | 48.5 ± 0.7 | 47.1 | 50.9 | 33.93 ± 3.71 |
| mattcl-py | input-lanjian | 48.5 ± 0.6 | 47.4 | 50.1 | 33.96 ± 3.70 |
| kcen | input-mattcl | 175.2 ± 1.7 | 172.0 | 178.6 | 122.65 ± 13.35 |
| kcen | input-mikofo | 214.9 ± 1.9 | 212.0 | 219.2 | 150.45 ± 16.37 |
| kcen | input-kcen | 227.8 ± 3.9 | 221.2 | 233.9 | 159.45 ± 17.50 |
| kcen | input-lanjian | 366.2 ± 0.8 | 364.6 | 367.0 | 256.35 ± 27.80 |
| mikofo | input-mattcl | 535.1 ± 13.6 | 515.1 | 548.2 | 374.59 ± 41.70 |
| mikofo | input-mikofo | 583.4 ± 14.0 | 567.1 | 597.6 | 408.39 ± 45.35 |
| mikofo | input-kcen | 685.7 ± 9.9 | 679.3 | 700.4 | 479.96 ± 52.49 |
| mikofo | input-lanjian | 991.9 ± 14.4 | 979.7 | 1007.7 | 694.33 ± 75.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|