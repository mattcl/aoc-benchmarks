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
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.1 | 2.3 | 1.01 ± 0.19 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.0 | 2.7 | 1.01 ± 0.21 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.1 | 2.7 | 1.03 ± 0.22 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.5 | 5.3 | 2.76 ± 0.45 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 4.0 | 5.5 | 3.28 ± 0.51 |
| lanjian | input-kcen | 5.1 ± 0.4 | 4.4 | 8.1 | 3.54 ± 0.56 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 7.2 | 4.40 ± 0.64 |
| mattcl-py | input-kcen | 48.2 ± 0.6 | 46.9 | 49.9 | 33.46 ± 4.76 |
| mattcl-py | input-lanjian | 48.5 ± 0.6 | 47.3 | 51.1 | 33.66 ± 4.80 |
| mattcl-py | input-mattcl | 48.5 ± 0.7 | 47.0 | 49.7 | 33.68 ± 4.80 |
| mattcl-py | input-mikofo | 48.6 ± 0.9 | 47.0 | 52.2 | 33.77 ± 4.83 |
| kcen | input-mattcl | 175.9 ± 1.3 | 173.6 | 177.9 | 122.13 ± 17.35 |
| kcen | input-mikofo | 214.6 ± 1.4 | 212.8 | 216.8 | 149.06 ± 21.17 |
| kcen | input-kcen | 228.6 ± 1.1 | 226.5 | 230.4 | 158.76 ± 22.54 |
| kcen | input-lanjian | 369.5 ± 2.2 | 367.0 | 373.0 | 256.60 ± 36.44 |
| mikofo | input-mattcl | 522.6 ± 10.3 | 509.2 | 532.6 | 362.94 ± 52.00 |
| mikofo | input-mikofo | 580.1 ± 8.6 | 565.8 | 588.7 | 402.93 ± 57.48 |
| mikofo | input-kcen | 694.0 ± 10.0 | 682.9 | 702.5 | 481.98 ± 68.74 |
| mikofo | input-lanjian | 985.9 ± 10.0 | 977.7 | 997.1 | 684.76 ± 97.41 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|