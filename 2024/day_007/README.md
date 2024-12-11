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
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 1.9 | 1.00 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.4 | 1.01 ± 0.17 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.4 | 1.01 ± 0.16 |
| mattcl | input-kcen | 1.4 ± 0.1 | 1.0 | 2.0 | 1.01 ± 0.16 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.5 | 5.1 | 2.83 ± 0.39 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 4.0 | 5.5 | 3.31 ± 0.45 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.3 | 5.6 | 3.56 ± 0.44 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 7.2 | 4.45 ± 0.54 |
| mattcl-py | input-kcen | 47.4 ± 0.6 | 46.3 | 49.1 | 33.65 ± 3.94 |
| mattcl-py | input-lanjian | 47.6 ± 0.5 | 46.4 | 48.9 | 33.82 ± 3.96 |
| mattcl-py | input-mikofo | 47.7 ± 0.6 | 46.6 | 50.2 | 33.91 ± 3.97 |
| mattcl-py | input-mattcl | 47.9 ± 0.8 | 46.6 | 51.7 | 34.00 ± 4.00 |
| kcen | input-mattcl | 173.6 ± 3.1 | 170.8 | 181.7 | 123.36 ± 14.53 |
| kcen | input-mikofo | 211.8 ± 2.7 | 209.4 | 218.0 | 150.52 ± 17.63 |
| kcen | input-kcen | 223.8 ± 2.8 | 218.3 | 229.4 | 159.04 ± 18.62 |
| kcen | input-lanjian | 364.7 ± 4.4 | 359.3 | 371.1 | 259.15 ± 30.33 |
| mikofo | input-mattcl | 511.8 ± 7.2 | 502.2 | 522.4 | 363.66 ± 42.64 |
| mikofo | input-mikofo | 571.9 ± 6.6 | 562.6 | 577.1 | 406.33 ± 47.53 |
| mikofo | input-kcen | 682.8 ± 5.6 | 674.9 | 686.8 | 485.16 ± 56.62 |
| mikofo | input-lanjian | 985.2 ± 5.6 | 980.2 | 991.3 | 700.03 ± 81.59 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|