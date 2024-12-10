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
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.9 | 1.9 | 1.00 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.2 | 1.00 ± 0.18 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 1.8 | 1.00 ± 0.17 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.5 | 1.02 ± 0.19 |
| lanjian | input-mattcl | 3.9 ± 0.2 | 3.5 | 5.1 | 2.79 ± 0.39 |
| lanjian | input-mikofo | 4.6 ± 0.3 | 3.8 | 5.5 | 3.31 ± 0.47 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.3 | 5.7 | 3.58 ± 0.46 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 7.4 | 4.50 ± 0.59 |
| mattcl-py | input-kcen | 48.1 ± 0.6 | 46.6 | 49.7 | 34.51 ± 4.32 |
| mattcl-py | input-lanjian | 48.4 ± 0.7 | 46.7 | 50.3 | 34.70 ± 4.35 |
| mattcl-py | input-mikofo | 48.5 ± 0.7 | 46.5 | 49.8 | 34.76 ± 4.36 |
| mattcl-py | input-mattcl | 48.5 ± 0.8 | 46.7 | 51.7 | 34.80 ± 4.37 |
| kcen | input-mattcl | 174.3 ± 3.1 | 169.9 | 184.6 | 125.05 ± 15.74 |
| kcen | input-mikofo | 210.6 ± 2.2 | 207.2 | 216.0 | 151.10 ± 18.89 |
| kcen | input-kcen | 224.6 ± 2.0 | 222.6 | 229.7 | 161.11 ± 20.13 |
| kcen | input-lanjian | 361.5 ± 1.0 | 360.4 | 363.0 | 259.31 ± 32.32 |
| mikofo | input-mattcl | 523.5 ± 9.6 | 508.5 | 531.5 | 375.57 ± 47.30 |
| mikofo | input-mikofo | 577.3 ± 15.8 | 556.4 | 599.1 | 414.12 ± 52.83 |
| mikofo | input-kcen | 702.7 ± 8.8 | 690.6 | 709.4 | 504.09 ± 63.13 |
| mikofo | input-lanjian | 999.0 ± 9.9 | 991.5 | 1010.3 | 716.67 ± 89.58 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|