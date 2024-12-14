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
| mattcl | input-kcen | 1.4 ± 0.2 | 0.9 | 2.3 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.4 | 1.02 ± 0.20 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.4 | 1.02 ± 0.20 |
| mattcl | input-lanjian | 1.5 ± 0.3 | 1.0 | 3.4 | 1.05 ± 0.24 |
| lanjian | input-mattcl | 4.1 ± 0.4 | 3.5 | 5.3 | 2.99 ± 0.49 |
| lanjian | input-mikofo | 4.8 ± 0.3 | 3.9 | 5.6 | 3.42 ± 0.50 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.2 | 5.5 | 3.58 ± 0.51 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 7.3 | 4.56 ± 0.64 |
| mattcl-py | input-kcen | 47.8 ± 0.6 | 46.6 | 51.4 | 34.41 ± 4.70 |
| mattcl-py | input-mattcl | 48.2 ± 0.6 | 47.0 | 49.3 | 34.71 ± 4.74 |
| mattcl-py | input-lanjian | 48.2 ± 0.6 | 46.5 | 49.5 | 34.71 ± 4.74 |
| mattcl-py | input-mikofo | 48.4 ± 0.7 | 47.0 | 50.8 | 34.85 ± 4.77 |
| kcen | input-mattcl | 174.8 ± 0.8 | 173.3 | 176.5 | 125.79 ± 17.12 |
| kcen | input-mikofo | 214.4 ± 2.4 | 210.7 | 217.6 | 154.33 ± 21.06 |
| kcen | input-kcen | 226.2 ± 1.7 | 222.4 | 228.2 | 162.84 ± 22.18 |
| kcen | input-lanjian | 366.4 ± 2.9 | 363.2 | 371.2 | 263.74 ± 35.94 |
| mikofo | input-mattcl | 523.1 ± 22.0 | 496.7 | 549.5 | 376.50 ± 53.60 |
| mikofo | input-mikofo | 580.1 ± 8.7 | 572.0 | 591.3 | 417.52 ± 57.13 |
| mikofo | input-kcen | 682.7 ± 15.2 | 663.7 | 700.4 | 491.42 ± 67.73 |
| mikofo | input-lanjian | 987.3 ± 16.7 | 969.5 | 1002.6 | 710.64 ± 97.40 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|