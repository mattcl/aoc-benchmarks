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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 1.8 | 1.00 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.3 | 1.00 ± 0.18 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.1 | 1.01 ± 0.17 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.7 | 1.01 ± 0.19 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.4 | 5.1 | 2.78 ± 0.36 |
| lanjian | input-mikofo | 4.6 ± 0.3 | 3.9 | 5.4 | 3.20 ± 0.43 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.7 | 5.7 | 3.53 ± 0.41 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 6.9 | 4.40 ± 0.52 |
| mattcl-py | input-kcen | 47.7 ± 0.5 | 46.8 | 49.4 | 33.41 ± 3.74 |
| mattcl-py | input-mattcl | 48.0 ± 0.7 | 47.0 | 51.4 | 33.64 ± 3.79 |
| mattcl-py | input-lanjian | 48.0 ± 0.7 | 46.4 | 50.7 | 33.65 ± 3.78 |
| mattcl-py | input-mikofo | 48.0 ± 0.6 | 46.7 | 50.5 | 33.65 ± 3.78 |
| kcen | input-mattcl | 176.3 ± 1.8 | 173.0 | 179.5 | 123.58 ± 13.84 |
| kcen | input-mikofo | 214.5 ± 2.4 | 210.7 | 218.1 | 150.35 ± 16.86 |
| kcen | input-kcen | 226.9 ± 2.7 | 222.4 | 232.6 | 159.05 ± 17.84 |
| kcen | input-lanjian | 371.7 ± 9.6 | 362.1 | 393.5 | 260.54 ± 29.84 |
| mikofo | input-mattcl | 523.9 ± 25.3 | 489.3 | 556.3 | 367.18 ± 44.62 |
| mikofo | input-mikofo | 573.1 ± 9.3 | 560.4 | 585.6 | 401.70 ± 45.29 |
| mikofo | input-kcen | 698.0 ± 6.8 | 691.9 | 705.5 | 489.27 ± 54.79 |
| mikofo | input-lanjian | 982.2 ± 17.7 | 962.7 | 997.0 | 688.44 ± 77.79 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|