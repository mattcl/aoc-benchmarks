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
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.1 | 2.7 | 1.00 |
| mattcl | input-kcen | 1.5 ± 0.2 | 1.0 | 2.7 | 1.01 ± 0.21 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.1 | 2.6 | 1.01 ± 0.20 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.1 | 2.7 | 1.01 ± 0.21 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.6 | 4.9 | 2.77 ± 0.44 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 4.0 | 5.7 | 3.25 ± 0.50 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.5 | 5.7 | 3.46 ± 0.50 |
| lanjian | input-lanjian | 6.4 ± 0.2 | 5.9 | 7.2 | 4.38 ± 0.64 |
| mattcl-py | input-kcen | 48.5 ± 0.8 | 47.4 | 53.0 | 33.43 ± 4.74 |
| mattcl-py | input-mikofo | 48.6 ± 0.6 | 47.2 | 49.7 | 33.48 ± 4.74 |
| mattcl-py | input-lanjian | 48.6 ± 0.9 | 47.1 | 52.3 | 33.52 ± 4.76 |
| mattcl-py | input-mattcl | 48.6 ± 0.6 | 46.6 | 50.8 | 33.53 ± 4.74 |
| kcen | input-mattcl | 175.9 ± 1.1 | 173.7 | 178.3 | 121.28 ± 17.10 |
| kcen | input-mikofo | 217.8 ± 1.9 | 215.3 | 221.5 | 150.16 ± 21.19 |
| kcen | input-kcen | 226.3 ± 3.0 | 222.3 | 231.2 | 156.06 ± 22.08 |
| kcen | input-lanjian | 369.0 ± 1.9 | 366.8 | 372.6 | 254.44 ± 35.86 |
| mikofo | input-mattcl | 526.8 ± 18.6 | 496.1 | 544.8 | 363.29 ± 52.75 |
| mikofo | input-mikofo | 578.7 ± 6.9 | 571.6 | 588.6 | 399.03 ± 56.41 |
| mikofo | input-kcen | 697.5 ± 16.5 | 686.7 | 722.0 | 480.98 ± 68.69 |
| mikofo | input-lanjian | 997.1 ± 11.6 | 984.1 | 1006.5 | 687.55 ± 97.18 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|