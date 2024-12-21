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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 1.8 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.3 | 1.00 ± 0.16 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.1 | 2.5 | 1.00 ± 0.18 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.4 | 1.00 ± 0.16 |
| lanjian | input-mattcl | 3.9 ± 0.2 | 3.5 | 4.5 | 2.73 ± 0.33 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 3.8 | 5.5 | 3.35 ± 0.41 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.6 | 5.6 | 3.55 ± 0.40 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.9 | 6.9 | 4.48 ± 0.51 |
| mattcl-py | input-kcen | 47.2 ± 0.7 | 45.7 | 50.3 | 33.47 ± 3.66 |
| mattcl-py | input-mattcl | 47.6 ± 0.9 | 46.1 | 51.7 | 33.75 ± 3.72 |
| mattcl-py | input-lanjian | 47.7 ± 0.6 | 46.2 | 49.6 | 33.80 ± 3.70 |
| mattcl-py | input-mikofo | 47.8 ± 0.9 | 45.8 | 51.4 | 33.90 ± 3.73 |
| kcen | input-mattcl | 174.7 ± 2.4 | 171.4 | 179.5 | 123.88 ± 13.55 |
| kcen | input-mikofo | 214.8 ± 2.5 | 210.7 | 219.9 | 152.31 ± 16.63 |
| kcen | input-kcen | 225.7 ± 2.0 | 221.3 | 228.6 | 160.02 ± 17.43 |
| kcen | input-lanjian | 366.4 ± 4.3 | 358.6 | 372.8 | 259.76 ± 28.37 |
| mikofo | input-mattcl | 510.7 ± 15.4 | 496.6 | 532.3 | 362.05 ± 40.79 |
| mikofo | input-mikofo | 563.3 ± 10.9 | 550.9 | 580.3 | 399.35 ± 44.04 |
| mikofo | input-kcen | 685.0 ± 9.2 | 672.3 | 693.9 | 485.66 ± 53.13 |
| mikofo | input-lanjian | 980.0 ± 7.9 | 971.7 | 987.5 | 694.82 ± 75.65 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|