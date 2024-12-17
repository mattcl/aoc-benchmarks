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
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.0 | 1.00 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.1 | 2.2 | 1.01 ± 0.16 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 1.8 | 1.01 ± 0.17 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.3 | 1.02 ± 0.17 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.5 | 5.1 | 2.83 ± 0.39 |
| lanjian | input-mikofo | 4.6 ± 0.3 | 3.9 | 5.6 | 3.28 ± 0.45 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.5 | 5.9 | 3.56 ± 0.45 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 7.1 | 4.46 ± 0.56 |
| mattcl-py | input-kcen | 47.5 ± 0.6 | 46.3 | 49.9 | 33.56 ± 4.07 |
| mattcl-py | input-mikofo | 47.6 ± 0.7 | 46.5 | 50.4 | 33.69 ± 4.09 |
| mattcl-py | input-mattcl | 47.6 ± 0.5 | 46.4 | 48.9 | 33.69 ± 4.08 |
| mattcl-py | input-lanjian | 48.1 ± 0.9 | 46.7 | 52.5 | 34.01 ± 4.15 |
| kcen | input-mattcl | 176.3 ± 2.7 | 173.0 | 180.8 | 124.64 ± 15.15 |
| kcen | input-mikofo | 215.4 ± 3.5 | 210.8 | 221.1 | 152.35 ± 18.54 |
| kcen | input-kcen | 227.9 ± 2.3 | 224.3 | 231.6 | 161.13 ± 19.50 |
| kcen | input-lanjian | 366.9 ± 4.0 | 361.1 | 374.4 | 259.45 ± 31.42 |
| mikofo | input-mattcl | 534.5 ± 16.1 | 509.7 | 552.6 | 377.99 ± 46.98 |
| mikofo | input-mikofo | 578.5 ± 8.3 | 568.3 | 589.4 | 409.05 ± 49.67 |
| mikofo | input-kcen | 688.8 ± 6.2 | 681.3 | 695.6 | 487.05 ± 58.89 |
| mikofo | input-lanjian | 983.9 ± 13.7 | 968.4 | 994.4 | 695.78 ± 84.46 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|