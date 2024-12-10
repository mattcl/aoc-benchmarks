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
| mattcl | input-mikofo | 1.4 ± 0.1 | 1.1 | 1.9 | 1.01 ± 0.18 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.7 | 1.01 ± 0.21 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.0 | 2.3 | 1.01 ± 0.19 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.6 | 4.8 | 2.78 ± 0.46 |
| lanjian | input-mikofo | 4.6 ± 0.3 | 3.9 | 5.7 | 3.19 ± 0.53 |
| lanjian | input-kcen | 5.1 ± 0.2 | 4.4 | 6.1 | 3.53 ± 0.56 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 7.1 | 4.38 ± 0.68 |
| mattcl-py | input-kcen | 47.5 ± 0.5 | 46.3 | 49.2 | 33.17 ± 5.04 |
| mattcl-py | input-mikofo | 47.8 ± 0.5 | 46.9 | 49.2 | 33.40 ± 5.07 |
| mattcl-py | input-mattcl | 48.0 ± 0.6 | 46.8 | 50.4 | 33.50 ± 5.10 |
| mattcl-py | input-lanjian | 48.0 ± 0.6 | 46.6 | 50.1 | 33.53 ± 5.10 |
| kcen | input-mattcl | 176.3 ± 1.6 | 172.2 | 178.2 | 123.08 ± 18.69 |
| kcen | input-mikofo | 214.8 ± 2.1 | 212.3 | 220.0 | 149.99 ± 22.78 |
| kcen | input-kcen | 224.7 ± 1.4 | 222.6 | 227.6 | 156.92 ± 23.80 |
| kcen | input-lanjian | 366.4 ± 5.8 | 358.1 | 373.9 | 255.87 ± 38.99 |
| mikofo | input-mattcl | 514.9 ± 22.6 | 482.0 | 540.5 | 359.54 ± 56.74 |
| mikofo | input-mikofo | 573.4 ± 5.0 | 569.1 | 580.4 | 400.41 ± 60.79 |
| mikofo | input-kcen | 704.1 ± 5.1 | 697.3 | 708.2 | 491.66 ± 74.61 |
| mikofo | input-lanjian | 997.8 ± 8.8 | 992.4 | 1008.0 | 696.75 ± 105.79 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|