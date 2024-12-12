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
| mattcl | input-mikofo | 1.4 ± 0.1 | 1.1 | 2.1 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.1 | 1.1 | 1.9 | 1.00 ± 0.14 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.2 | 1.00 ± 0.16 |
| mattcl | input-kcen | 1.5 ± 0.2 | 1.0 | 2.5 | 1.01 ± 0.16 |
| lanjian | input-mattcl | 3.9 ± 0.2 | 3.5 | 4.6 | 2.74 ± 0.31 |
| lanjian | input-mikofo | 4.6 ± 0.3 | 3.9 | 5.4 | 3.24 ± 0.40 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.6 | 5.7 | 3.52 ± 0.38 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 7.1 | 4.40 ± 0.48 |
| mattcl-py | input-kcen | 47.7 ± 0.7 | 46.6 | 50.1 | 33.26 ± 3.44 |
| mattcl-py | input-mattcl | 47.8 ± 0.4 | 46.9 | 48.9 | 33.37 ± 3.43 |
| mattcl-py | input-lanjian | 47.9 ± 0.7 | 46.6 | 50.8 | 33.41 ± 3.46 |
| mattcl-py | input-mikofo | 47.9 ± 0.5 | 46.7 | 49.4 | 33.45 ± 3.45 |
| kcen | input-mattcl | 176.8 ± 1.8 | 173.5 | 180.1 | 123.38 ± 12.71 |
| kcen | input-mikofo | 214.7 ± 2.4 | 210.5 | 218.6 | 149.82 ± 15.44 |
| kcen | input-kcen | 226.3 ± 3.0 | 220.6 | 229.9 | 157.91 ± 16.32 |
| kcen | input-lanjian | 368.5 ± 5.1 | 361.3 | 375.5 | 257.10 ± 26.59 |
| mikofo | input-mattcl | 533.4 ± 16.4 | 508.4 | 547.5 | 372.15 ± 39.82 |
| mikofo | input-mikofo | 571.3 ± 7.6 | 558.9 | 578.2 | 398.60 ± 41.19 |
| mikofo | input-kcen | 689.3 ± 8.7 | 678.1 | 698.2 | 480.96 ± 49.66 |
| mikofo | input-lanjian | 996.3 ± 29.7 | 970.3 | 1028.7 | 695.13 ± 74.20 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|