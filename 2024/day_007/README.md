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
| mattcl | input-kcen | 1.5 ± 0.2 | 1.1 | 2.5 | 1.00 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.2 | 2.5 | 1.00 ± 0.19 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.1 | 2.7 | 1.03 ± 0.22 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.2 | 2.7 | 1.03 ± 0.22 |
| lanjian | input-mattcl | 4.1 ± 0.3 | 3.6 | 5.4 | 2.76 ± 0.45 |
| lanjian | input-mikofo | 4.8 ± 0.3 | 4.0 | 5.7 | 3.22 ± 0.51 |
| lanjian | input-kcen | 5.1 ± 0.2 | 4.5 | 5.6 | 3.37 ± 0.50 |
| lanjian | input-lanjian | 6.4 ± 0.2 | 5.8 | 7.2 | 4.24 ± 0.63 |
| mattcl-py | input-kcen | 47.9 ± 0.7 | 46.4 | 50.3 | 31.87 ± 4.61 |
| mattcl-py | input-mikofo | 48.2 ± 0.7 | 47.0 | 50.2 | 32.07 ± 4.63 |
| mattcl-py | input-mattcl | 48.3 ± 0.6 | 46.5 | 49.5 | 32.14 ± 4.64 |
| mattcl-py | input-lanjian | 48.4 ± 0.7 | 47.0 | 50.3 | 32.22 ± 4.65 |
| kcen | input-mattcl | 175.3 ± 1.3 | 172.4 | 177.2 | 116.57 ± 16.78 |
| kcen | input-mikofo | 215.6 ± 1.6 | 213.3 | 218.5 | 143.33 ± 20.63 |
| kcen | input-kcen | 227.2 ± 1.2 | 224.2 | 228.6 | 151.05 ± 21.73 |
| kcen | input-lanjian | 365.4 ± 1.8 | 362.8 | 368.2 | 243.00 ± 34.95 |
| mikofo | input-mattcl | 522.9 ± 15.8 | 500.5 | 541.6 | 347.71 ± 51.06 |
| mikofo | input-mikofo | 570.4 ± 12.3 | 558.5 | 591.2 | 379.27 ± 55.12 |
| mikofo | input-kcen | 695.7 ± 11.4 | 684.9 | 711.2 | 462.58 ± 66.92 |
| mikofo | input-lanjian | 997.8 ± 17.6 | 977.7 | 1010.2 | 663.51 ± 96.08 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|