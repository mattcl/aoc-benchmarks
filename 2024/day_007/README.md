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
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.4 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.3 | 1.00 ± 0.18 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.4 | 1.01 ± 0.20 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.5 | 1.02 ± 0.21 |
| lanjian | input-mattcl | 3.9 ± 0.3 | 3.5 | 4.9 | 2.87 ± 0.43 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 3.9 | 5.6 | 3.43 ± 0.50 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.4 | 5.7 | 3.62 ± 0.49 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.7 | 7.0 | 4.56 ± 0.61 |
| mattcl-py | input-kcen | 47.8 ± 0.7 | 46.2 | 49.7 | 34.80 ± 4.52 |
| mattcl-py | input-mattcl | 48.4 ± 0.8 | 47.0 | 52.0 | 35.21 ± 4.59 |
| mattcl-py | input-lanjian | 48.4 ± 0.8 | 47.1 | 50.9 | 35.21 ± 4.59 |
| mattcl-py | input-mikofo | 48.5 ± 0.6 | 47.6 | 50.5 | 35.29 ± 4.58 |
| kcen | input-mattcl | 173.2 ± 0.9 | 171.8 | 175.3 | 126.00 ± 16.30 |
| kcen | input-mikofo | 212.8 ± 1.8 | 209.9 | 215.5 | 154.78 ± 20.05 |
| kcen | input-kcen | 223.9 ± 2.5 | 220.8 | 227.1 | 162.92 ± 21.13 |
| kcen | input-lanjian | 362.0 ± 3.4 | 357.7 | 365.2 | 263.39 ± 34.12 |
| mikofo | input-mattcl | 523.9 ± 17.9 | 510.7 | 554.5 | 381.15 ± 50.95 |
| mikofo | input-mikofo | 585.5 ± 9.6 | 573.6 | 598.0 | 426.00 ± 55.49 |
| mikofo | input-kcen | 700.8 ± 21.3 | 674.6 | 719.4 | 509.82 ± 67.67 |
| mikofo | input-lanjian | 997.8 ± 9.4 | 988.8 | 1007.5 | 725.92 ± 94.05 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|