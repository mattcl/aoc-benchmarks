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
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.1 | 2.3 | 1.01 ± 0.19 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.1 | 2.5 | 1.01 ± 0.21 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.1 | 2.5 | 1.02 ± 0.22 |
| lanjian | input-mattcl | 4.2 ± 0.3 | 3.6 | 5.0 | 2.81 ± 0.48 |
| lanjian | input-mikofo | 4.8 ± 0.3 | 4.1 | 5.6 | 3.21 ± 0.53 |
| lanjian | input-kcen | 5.1 ± 0.2 | 4.5 | 6.0 | 3.39 ± 0.54 |
| lanjian | input-lanjian | 6.4 ± 0.3 | 5.8 | 7.3 | 4.27 ± 0.67 |
| mattcl-py | input-kcen | 48.5 ± 0.7 | 47.4 | 52.2 | 32.54 ± 4.99 |
| mattcl-py | input-mattcl | 48.7 ± 0.6 | 47.1 | 50.3 | 32.72 ± 5.01 |
| mattcl-py | input-mikofo | 48.8 ± 0.7 | 47.5 | 52.2 | 32.80 ± 5.03 |
| mattcl-py | input-lanjian | 48.9 ± 0.8 | 47.8 | 52.6 | 32.85 ± 5.04 |
| kcen | input-mattcl | 176.7 ± 1.6 | 174.8 | 181.1 | 118.63 ± 18.14 |
| kcen | input-mikofo | 216.5 ± 2.2 | 213.5 | 220.3 | 145.38 ± 22.23 |
| kcen | input-kcen | 228.6 ± 2.2 | 224.8 | 231.6 | 153.48 ± 23.47 |
| kcen | input-lanjian | 367.3 ± 3.2 | 363.7 | 372.6 | 246.66 ± 37.70 |
| mikofo | input-mattcl | 528.3 ± 12.5 | 513.3 | 546.9 | 354.73 ± 54.79 |
| mikofo | input-mikofo | 601.8 ± 20.6 | 574.0 | 623.8 | 404.09 ± 63.20 |
| mikofo | input-kcen | 693.8 ± 13.3 | 680.5 | 708.3 | 465.87 ± 71.66 |
| mikofo | input-lanjian | 980.9 ± 19.1 | 967.0 | 1002.7 | 658.68 ± 101.34 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|