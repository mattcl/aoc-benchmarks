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
| mattcl | input-mattcl | 1.4 ± 0.1 | 1.1 | 1.8 | 1.00 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.3 | 1.00 ± 0.15 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.1 | 2.3 | 1.01 ± 0.16 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.0 | 2.5 | 1.02 ± 0.18 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.5 | 5.1 | 2.76 ± 0.34 |
| lanjian | input-mikofo | 4.8 ± 0.3 | 4.0 | 5.7 | 3.33 ± 0.39 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.3 | 6.0 | 3.52 ± 0.40 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.7 | 7.0 | 4.40 ± 0.48 |
| mattcl-py | input-mikofo | 47.5 ± 0.6 | 46.3 | 49.4 | 33.15 ± 3.46 |
| mattcl-py | input-mattcl | 47.7 ± 0.6 | 46.3 | 49.4 | 33.26 ± 3.48 |
| mattcl-py | input-lanjian | 48.0 ± 0.9 | 46.5 | 51.7 | 33.48 ± 3.53 |
| mattcl-py | input-kcen | 48.0 ± 1.5 | 46.3 | 54.2 | 33.50 ± 3.62 |
| kcen | input-mattcl | 174.1 ± 1.8 | 169.9 | 177.8 | 121.43 ± 12.66 |
| kcen | input-mikofo | 216.6 ± 2.8 | 211.9 | 219.9 | 151.04 ± 15.79 |
| kcen | input-kcen | 226.8 ± 2.0 | 223.8 | 232.2 | 158.18 ± 16.47 |
| kcen | input-lanjian | 366.5 ± 3.8 | 362.7 | 372.5 | 255.59 ± 26.64 |
| mikofo | input-mattcl | 510.3 ± 17.5 | 492.9 | 530.5 | 355.94 ± 38.88 |
| mikofo | input-mikofo | 576.5 ± 7.1 | 564.4 | 582.0 | 402.10 ± 42.00 |
| mikofo | input-kcen | 688.6 ± 10.0 | 681.1 | 702.7 | 480.28 ± 50.31 |
| mikofo | input-lanjian | 983.7 ± 5.9 | 977.3 | 988.8 | 686.09 ± 71.29 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|