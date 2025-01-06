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
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.1 | 1.9 | 1.00 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.1 | 2.5 | 1.01 ± 0.17 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.1 | 2.7 | 1.02 ± 0.19 |
| mattcl | input-kcen | 1.5 ± 0.2 | 1.1 | 2.4 | 1.02 ± 0.20 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.6 | 5.2 | 2.78 ± 0.38 |
| lanjian | input-mikofo | 4.7 ± 0.4 | 3.8 | 5.6 | 3.26 ± 0.46 |
| lanjian | input-kcen | 5.2 ± 0.3 | 4.6 | 6.1 | 3.58 ± 0.47 |
| lanjian | input-lanjian | 6.4 ± 0.3 | 5.9 | 7.3 | 4.40 ± 0.55 |
| mattcl-py | input-kcen | 47.5 ± 0.7 | 46.3 | 50.7 | 32.80 ± 3.90 |
| mattcl-py | input-mikofo | 47.7 ± 0.6 | 46.4 | 50.0 | 32.92 ± 3.90 |
| mattcl-py | input-mattcl | 47.8 ± 0.5 | 46.4 | 49.6 | 33.01 ± 3.91 |
| mattcl-py | input-lanjian | 47.9 ± 0.8 | 46.3 | 51.5 | 33.07 ± 3.94 |
| kcen | input-mattcl | 175.0 ± 1.9 | 172.3 | 178.0 | 120.82 ± 14.30 |
| kcen | input-mikofo | 216.5 ± 2.4 | 212.3 | 219.8 | 149.50 ± 17.70 |
| kcen | input-kcen | 227.0 ± 2.2 | 223.5 | 230.6 | 156.77 ± 18.55 |
| kcen | input-lanjian | 365.4 ± 6.3 | 357.9 | 376.8 | 252.29 ± 30.06 |
| mikofo | input-mattcl | 523.8 ± 18.7 | 501.3 | 544.0 | 361.68 ± 44.56 |
| mikofo | input-mikofo | 566.1 ± 6.1 | 557.4 | 570.9 | 390.88 ± 46.28 |
| mikofo | input-kcen | 689.2 ± 17.8 | 673.0 | 711.7 | 475.86 ± 57.44 |
| mikofo | input-lanjian | 987.3 ± 4.4 | 982.3 | 990.4 | 681.73 ± 80.44 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|