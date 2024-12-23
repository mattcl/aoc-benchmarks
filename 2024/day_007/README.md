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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.1 | 2.8 | 1.00 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.1 | 2.4 | 1.01 ± 0.18 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.1 | 2.4 | 1.01 ± 0.18 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.1 | 2.4 | 1.01 ± 0.18 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.6 | 5.1 | 2.84 ± 0.42 |
| lanjian | input-mikofo | 4.5 ± 0.3 | 4.0 | 5.7 | 3.18 ± 0.47 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.5 | 5.5 | 3.52 ± 0.47 |
| lanjian | input-lanjian | 6.4 ± 0.2 | 5.8 | 7.1 | 4.46 ± 0.60 |
| mattcl-py | input-kcen | 47.6 ± 0.8 | 46.2 | 51.2 | 33.39 ± 4.35 |
| mattcl-py | input-mikofo | 47.9 ± 0.6 | 46.8 | 50.8 | 33.58 ± 4.36 |
| mattcl-py | input-mattcl | 47.9 ± 0.6 | 46.8 | 49.6 | 33.61 ± 4.36 |
| mattcl-py | input-lanjian | 48.0 ± 0.6 | 46.6 | 50.6 | 33.66 ± 4.37 |
| kcen | input-mattcl | 176.8 ± 1.2 | 174.3 | 178.8 | 124.04 ± 16.04 |
| kcen | input-mikofo | 218.9 ± 2.2 | 216.1 | 223.2 | 153.60 ± 19.90 |
| kcen | input-kcen | 229.4 ± 3.3 | 224.0 | 233.3 | 160.96 ± 20.92 |
| kcen | input-lanjian | 369.8 ± 5.1 | 364.0 | 378.7 | 259.47 ± 33.70 |
| mikofo | input-mattcl | 524.1 ± 10.2 | 515.3 | 537.9 | 367.80 ± 48.05 |
| mikofo | input-mikofo | 577.4 ± 14.8 | 555.8 | 591.4 | 405.17 ± 53.35 |
| mikofo | input-kcen | 692.5 ± 14.2 | 672.2 | 704.3 | 485.97 ± 63.56 |
| mikofo | input-lanjian | 992.3 ± 1.7 | 990.9 | 994.3 | 696.35 ± 89.95 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|