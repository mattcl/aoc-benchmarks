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
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.4 | 1.00 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.1 | 1.00 ± 0.16 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.2 | 1.01 ± 0.17 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.5 | 1.01 ± 0.17 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.5 | 5.1 | 2.81 ± 0.38 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 3.9 | 5.5 | 3.27 ± 0.44 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.3 | 5.5 | 3.53 ± 0.42 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.9 | 7.1 | 4.43 ± 0.53 |
| mattcl-py | input-mikofo | 47.6 ± 0.6 | 46.5 | 49.4 | 33.50 ± 3.85 |
| mattcl-py | input-kcen | 47.6 ± 0.5 | 46.7 | 49.0 | 33.52 ± 3.85 |
| mattcl-py | input-mattcl | 47.7 ± 0.6 | 46.5 | 50.1 | 33.60 ± 3.86 |
| mattcl-py | input-lanjian | 47.8 ± 0.7 | 46.5 | 49.7 | 33.64 ± 3.87 |
| kcen | input-mattcl | 176.8 ± 1.6 | 173.5 | 179.4 | 124.39 ± 14.25 |
| kcen | input-mikofo | 215.8 ± 1.8 | 213.3 | 218.9 | 151.84 ± 17.38 |
| kcen | input-kcen | 225.3 ± 2.9 | 220.9 | 228.6 | 158.56 ± 18.22 |
| kcen | input-lanjian | 365.2 ± 5.3 | 358.0 | 373.6 | 256.97 ± 29.58 |
| mikofo | input-mattcl | 535.4 ± 15.1 | 518.4 | 557.7 | 376.78 ± 44.32 |
| mikofo | input-mikofo | 573.9 ± 16.6 | 552.1 | 587.6 | 403.87 ± 47.57 |
| mikofo | input-kcen | 693.9 ± 11.0 | 680.0 | 706.7 | 488.29 ± 56.29 |
| mikofo | input-lanjian | 987.8 ± 2.7 | 985.9 | 990.8 | 695.07 ± 79.39 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|