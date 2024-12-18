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
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.1 | 1.9 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.2 | 1.00 ± 0.17 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.8 | 1.01 ± 0.18 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.1 | 2.5 | 1.03 ± 0.19 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.5 | 6.1 | 2.85 ± 0.40 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 3.8 | 6.2 | 3.38 ± 0.44 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.5 | 5.6 | 3.57 ± 0.42 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 7.1 | 4.51 ± 0.53 |
| mattcl-py | input-kcen | 48.1 ± 0.5 | 46.4 | 48.8 | 34.30 ± 3.84 |
| mattcl-py | input-mattcl | 48.4 ± 0.7 | 47.2 | 51.4 | 34.53 ± 3.88 |
| mattcl-py | input-mikofo | 48.4 ± 0.6 | 47.6 | 50.1 | 34.58 ± 3.88 |
| mattcl-py | input-lanjian | 48.5 ± 0.8 | 46.9 | 50.9 | 34.61 ± 3.90 |
| kcen | input-mattcl | 174.3 ± 1.7 | 171.5 | 178.0 | 124.43 ± 13.92 |
| kcen | input-mikofo | 213.9 ± 1.7 | 211.3 | 216.4 | 152.72 ± 17.07 |
| kcen | input-kcen | 227.4 ± 2.4 | 222.3 | 230.5 | 162.33 ± 18.18 |
| kcen | input-lanjian | 365.8 ± 3.3 | 360.8 | 369.4 | 261.16 ± 29.21 |
| mikofo | input-mattcl | 531.1 ± 7.9 | 518.4 | 537.9 | 379.15 ± 42.64 |
| mikofo | input-mikofo | 580.8 ± 17.0 | 567.3 | 601.4 | 414.62 ± 47.79 |
| mikofo | input-kcen | 692.8 ± 11.5 | 678.5 | 703.4 | 494.53 ± 55.73 |
| mikofo | input-lanjian | 990.7 ± 3.7 | 987.0 | 994.3 | 707.20 ± 78.88 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|