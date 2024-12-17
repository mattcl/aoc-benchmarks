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
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.1 | 2.4 | 1.00 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.2 | 2.0 | 1.00 ± 0.16 |
| mattcl | input-kcen | 1.5 ± 0.2 | 1.0 | 2.4 | 1.01 ± 0.19 |
| mattcl | input-lanjian | 1.5 ± 0.3 | 1.1 | 3.2 | 1.03 ± 0.23 |
| lanjian | input-mattcl | 4.1 ± 0.3 | 3.5 | 5.3 | 2.75 ± 0.39 |
| lanjian | input-mikofo | 4.8 ± 0.3 | 4.0 | 5.7 | 3.25 ± 0.42 |
| lanjian | input-kcen | 5.1 ± 0.2 | 4.5 | 6.3 | 3.46 ± 0.43 |
| lanjian | input-lanjian | 6.4 ± 0.2 | 6.0 | 7.3 | 4.35 ± 0.53 |
| mattcl-py | input-kcen | 48.1 ± 0.6 | 46.8 | 49.9 | 32.59 ± 3.82 |
| mattcl-py | input-mattcl | 48.4 ± 0.6 | 47.4 | 49.8 | 32.85 ± 3.85 |
| mattcl-py | input-mikofo | 48.6 ± 0.7 | 47.4 | 51.3 | 32.98 ± 3.87 |
| mattcl-py | input-lanjian | 48.7 ± 0.9 | 47.5 | 51.5 | 33.01 ± 3.89 |
| kcen | input-mattcl | 175.1 ± 1.4 | 172.4 | 177.5 | 118.80 ± 13.87 |
| kcen | input-mikofo | 214.5 ± 2.4 | 210.9 | 217.5 | 145.48 ± 17.02 |
| kcen | input-kcen | 227.9 ± 2.2 | 222.9 | 230.7 | 154.56 ± 18.06 |
| kcen | input-lanjian | 364.8 ± 4.3 | 358.2 | 370.2 | 247.43 ± 28.96 |
| mikofo | input-mattcl | 533.5 ± 22.3 | 494.1 | 547.6 | 361.90 ± 44.77 |
| mikofo | input-mikofo | 588.0 ± 13.8 | 569.2 | 602.7 | 398.81 ± 47.38 |
| mikofo | input-kcen | 697.1 ± 11.7 | 682.4 | 711.0 | 472.83 ± 55.63 |
| mikofo | input-lanjian | 991.6 ± 5.2 | 986.7 | 997.0 | 672.60 ± 78.41 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|