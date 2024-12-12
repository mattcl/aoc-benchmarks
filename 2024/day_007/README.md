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
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 1.8 | 1.00 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.3 | 1.00 ± 0.17 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.0 | 1.01 ± 0.17 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.6 | 1.01 ± 0.19 |
| lanjian | input-mattcl | 4.0 ± 0.4 | 3.5 | 5.4 | 2.92 ± 0.42 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 3.9 | 5.7 | 3.38 ± 0.45 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.3 | 5.9 | 3.61 ± 0.44 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.7 | 7.1 | 4.57 ± 0.55 |
| mattcl-py | input-kcen | 48.2 ± 0.7 | 46.8 | 50.9 | 34.83 ± 3.98 |
| mattcl-py | input-lanjian | 48.5 ± 0.8 | 46.6 | 51.0 | 35.06 ± 4.02 |
| mattcl-py | input-mikofo | 48.5 ± 0.7 | 47.1 | 50.2 | 35.07 ± 4.01 |
| mattcl-py | input-mattcl | 48.5 ± 0.7 | 46.9 | 51.5 | 35.10 ± 4.01 |
| kcen | input-mattcl | 174.5 ± 1.6 | 171.3 | 177.4 | 126.16 ± 14.37 |
| kcen | input-mikofo | 216.1 ± 7.2 | 211.9 | 238.9 | 156.30 ± 18.48 |
| kcen | input-kcen | 227.1 ± 1.5 | 223.6 | 229.0 | 164.24 ± 18.68 |
| kcen | input-lanjian | 364.5 ± 2.9 | 358.8 | 367.4 | 263.60 ± 29.99 |
| mikofo | input-mattcl | 519.1 ± 15.2 | 502.8 | 538.6 | 375.36 ± 44.01 |
| mikofo | input-mikofo | 579.0 ± 8.6 | 569.0 | 588.4 | 418.73 ± 47.94 |
| mikofo | input-kcen | 698.3 ± 6.3 | 689.7 | 703.4 | 504.97 ± 57.50 |
| mikofo | input-lanjian | 995.3 ± 18.6 | 973.9 | 1007.0 | 719.71 ± 82.79 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|