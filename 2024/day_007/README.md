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
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.4 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.7 | 1.00 ± 0.20 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.3 | 1.01 ± 0.18 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.9 | 2.6 | 1.01 ± 0.21 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.5 | 5.2 | 2.87 ± 0.46 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 3.8 | 5.6 | 3.35 ± 0.50 |
| lanjian | input-kcen | 5.1 ± 0.4 | 4.2 | 9.2 | 3.61 ± 0.57 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 7.0 | 4.47 ± 0.63 |
| mattcl-py | input-kcen | 47.4 ± 0.6 | 46.3 | 48.7 | 33.82 ± 4.66 |
| mattcl-py | input-mikofo | 47.6 ± 0.7 | 46.3 | 50.2 | 33.98 ± 4.69 |
| mattcl-py | input-lanjian | 47.7 ± 0.6 | 46.5 | 49.3 | 34.04 ± 4.69 |
| mattcl-py | input-mattcl | 47.8 ± 0.6 | 46.2 | 49.1 | 34.08 ± 4.69 |
| kcen | input-mattcl | 175.8 ± 1.4 | 173.1 | 178.3 | 125.47 ± 17.24 |
| kcen | input-mikofo | 214.1 ± 3.5 | 209.1 | 220.7 | 152.75 ± 21.11 |
| kcen | input-kcen | 224.2 ± 3.2 | 219.2 | 231.4 | 159.98 ± 22.07 |
| kcen | input-lanjian | 364.5 ± 3.4 | 360.4 | 369.8 | 260.10 ± 35.77 |
| mikofo | input-mattcl | 520.1 ± 23.3 | 493.4 | 545.8 | 371.09 ± 53.57 |
| mikofo | input-mikofo | 574.9 ± 10.7 | 561.9 | 587.2 | 410.17 ± 56.80 |
| mikofo | input-kcen | 692.3 ± 9.7 | 678.4 | 700.8 | 493.99 ± 68.14 |
| mikofo | input-lanjian | 990.8 ± 3.8 | 986.6 | 994.1 | 706.93 ± 97.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|