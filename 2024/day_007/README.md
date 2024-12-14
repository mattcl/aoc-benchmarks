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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.1 | 2.5 | 1.00 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.0 | 2.2 | 1.01 ± 0.17 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.0 | 2.4 | 1.01 ± 0.18 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.1 | 2.5 | 1.01 ± 0.19 |
| lanjian | input-mattcl | 4.2 ± 0.4 | 3.6 | 5.4 | 2.87 ± 0.44 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 3.9 | 5.5 | 3.26 ± 0.46 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.5 | 5.7 | 3.49 ± 0.46 |
| lanjian | input-lanjian | 6.4 ± 0.4 | 5.8 | 9.9 | 4.43 ± 0.62 |
| mattcl-py | input-kcen | 48.2 ± 0.6 | 46.7 | 49.9 | 33.28 ± 4.23 |
| mattcl-py | input-lanjian | 48.6 ± 0.6 | 47.4 | 49.8 | 33.59 ± 4.27 |
| mattcl-py | input-mattcl | 48.7 ± 0.8 | 47.1 | 51.9 | 33.62 ± 4.29 |
| mattcl-py | input-mikofo | 48.8 ± 0.8 | 47.1 | 51.7 | 33.71 ± 4.30 |
| kcen | input-mattcl | 176.8 ± 2.1 | 174.5 | 180.7 | 122.13 ± 15.51 |
| kcen | input-mikofo | 216.7 ± 2.0 | 214.2 | 219.9 | 149.71 ± 18.99 |
| kcen | input-kcen | 228.4 ± 1.7 | 226.0 | 231.3 | 157.81 ± 20.00 |
| kcen | input-lanjian | 368.8 ± 2.1 | 366.1 | 372.8 | 254.87 ± 32.27 |
| mikofo | input-mattcl | 528.4 ± 11.9 | 515.3 | 541.4 | 365.11 ± 46.90 |
| mikofo | input-mikofo | 588.5 ± 6.8 | 577.1 | 594.0 | 406.62 ± 51.64 |
| mikofo | input-kcen | 699.6 ± 15.5 | 676.8 | 711.1 | 483.41 ± 62.08 |
| mikofo | input-lanjian | 1028.5 ± 7.8 | 1021.3 | 1036.8 | 710.64 ± 90.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|