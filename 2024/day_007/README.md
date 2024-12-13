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
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.1 | 2.0 | 1.00 |
| mattcl | input-kcen | 1.4 ± 0.1 | 1.1 | 1.9 | 1.00 ± 0.14 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.1 | 2.3 | 1.01 ± 0.16 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.0 | 2.4 | 1.01 ± 0.16 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.5 | 5.0 | 2.75 ± 0.34 |
| lanjian | input-mikofo | 4.8 ± 0.3 | 3.9 | 5.7 | 3.31 ± 0.40 |
| lanjian | input-kcen | 5.1 ± 0.2 | 4.4 | 5.9 | 3.50 ± 0.39 |
| lanjian | input-lanjian | 6.4 ± 0.3 | 5.9 | 7.5 | 4.45 ± 0.50 |
| mattcl-py | input-kcen | 47.9 ± 0.8 | 46.5 | 51.8 | 33.14 ± 3.49 |
| mattcl-py | input-lanjian | 48.3 ± 0.7 | 46.6 | 50.5 | 33.44 ± 3.52 |
| mattcl-py | input-mattcl | 48.4 ± 0.7 | 46.7 | 50.3 | 33.49 ± 3.52 |
| mattcl-py | input-mikofo | 48.4 ± 0.9 | 46.7 | 53.6 | 33.50 ± 3.54 |
| kcen | input-mattcl | 173.1 ± 1.8 | 169.8 | 175.4 | 119.85 ± 12.53 |
| kcen | input-mikofo | 213.4 ± 1.1 | 211.7 | 215.6 | 147.74 ± 15.39 |
| kcen | input-kcen | 225.1 ± 2.2 | 221.6 | 228.5 | 155.82 ± 16.28 |
| kcen | input-lanjian | 365.2 ± 3.2 | 359.2 | 368.6 | 252.82 ± 26.39 |
| mikofo | input-mattcl | 530.5 ± 13.2 | 519.3 | 552.2 | 367.19 ± 39.28 |
| mikofo | input-mikofo | 588.6 ± 4.1 | 585.5 | 595.8 | 407.48 ± 42.49 |
| mikofo | input-kcen | 705.8 ± 11.3 | 696.6 | 719.9 | 488.58 ± 51.42 |
| mikofo | input-lanjian | 987.2 ± 11.5 | 974.2 | 996.2 | 683.35 ± 71.53 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|