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
| mattcl | input-kcen | 1.5 ± 0.2 | 1.1 | 2.6 | 1.00 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.1 | 2.4 | 1.01 ± 0.19 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.2 | 2.8 | 1.02 ± 0.21 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.1 | 2.7 | 1.03 ± 0.22 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.6 | 5.4 | 2.73 ± 0.43 |
| lanjian | input-mikofo | 4.8 ± 0.3 | 4.0 | 5.6 | 3.26 ± 0.49 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.3 | 5.8 | 3.45 ± 0.50 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.9 | 7.6 | 4.34 ± 0.63 |
| mattcl-py | input-kcen | 48.2 ± 0.7 | 46.5 | 49.5 | 32.98 ± 4.61 |
| mattcl-py | input-lanjian | 48.6 ± 0.6 | 47.2 | 50.5 | 33.25 ± 4.64 |
| mattcl-py | input-mattcl | 48.6 ± 0.7 | 46.7 | 50.6 | 33.31 ± 4.65 |
| mattcl-py | input-mikofo | 48.8 ± 0.7 | 47.4 | 50.6 | 33.39 ± 4.66 |
| kcen | input-mattcl | 177.7 ± 2.0 | 174.9 | 181.8 | 121.68 ± 16.96 |
| kcen | input-mikofo | 216.5 ± 1.9 | 211.2 | 218.7 | 148.21 ± 20.64 |
| kcen | input-kcen | 228.5 ± 2.2 | 223.6 | 231.2 | 156.44 ± 21.79 |
| kcen | input-lanjian | 365.7 ± 3.3 | 361.6 | 369.7 | 250.39 ± 34.87 |
| mikofo | input-mattcl | 522.3 ± 10.1 | 507.3 | 535.2 | 357.63 ± 50.18 |
| mikofo | input-mikofo | 572.5 ± 8.5 | 561.4 | 585.3 | 392.03 ± 54.79 |
| mikofo | input-kcen | 692.6 ± 5.1 | 689.0 | 700.0 | 474.25 ± 66.00 |
| mikofo | input-lanjian | 996.8 ± 9.7 | 985.9 | 1004.1 | 682.55 ± 95.08 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|