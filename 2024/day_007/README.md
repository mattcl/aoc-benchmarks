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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.6 | 1.00 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.1 | 2.5 | 1.01 ± 0.20 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.0 | 2.3 | 1.01 ± 0.20 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.1 | 2.6 | 1.01 ± 0.21 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.6 | 5.1 | 2.77 ± 0.48 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 4.0 | 5.8 | 3.23 ± 0.54 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.4 | 5.7 | 3.47 ± 0.54 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 7.3 | 4.38 ± 0.68 |
| mattcl-py | input-kcen | 47.7 ± 0.4 | 46.7 | 48.5 | 32.95 ± 4.97 |
| mattcl-py | input-mattcl | 48.1 ± 0.7 | 46.7 | 50.2 | 33.22 ± 5.03 |
| mattcl-py | input-lanjian | 48.2 ± 0.6 | 47.3 | 50.8 | 33.29 ± 5.04 |
| mattcl-py | input-mikofo | 48.3 ± 0.6 | 47.2 | 50.3 | 33.30 ± 5.03 |
| kcen | input-mattcl | 175.0 ± 1.7 | 170.7 | 177.5 | 120.77 ± 18.24 |
| kcen | input-mikofo | 214.0 ± 1.0 | 212.8 | 215.3 | 147.65 ± 22.26 |
| kcen | input-kcen | 227.5 ± 1.8 | 223.6 | 230.0 | 156.97 ± 23.69 |
| kcen | input-lanjian | 366.5 ± 1.8 | 364.0 | 370.0 | 252.91 ± 38.13 |
| mikofo | input-mattcl | 529.7 ± 18.3 | 503.1 | 547.1 | 365.53 ± 56.50 |
| mikofo | input-mikofo | 579.3 ± 14.0 | 557.7 | 589.2 | 399.74 ± 61.01 |
| mikofo | input-kcen | 698.8 ± 8.9 | 686.5 | 707.6 | 482.21 ± 72.92 |
| mikofo | input-lanjian | 989.4 ± 12.3 | 979.7 | 1003.3 | 682.75 ± 103.23 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|