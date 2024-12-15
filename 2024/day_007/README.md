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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.1 | 2.3 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.4 | 1.02 ± 0.19 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.1 | 2.7 | 1.02 ± 0.20 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.1 | 2.3 | 1.03 ± 0.18 |
| lanjian | input-mattcl | 3.9 ± 0.3 | 3.5 | 5.0 | 2.81 ± 0.38 |
| lanjian | input-mikofo | 4.7 ± 0.2 | 4.1 | 5.5 | 3.36 ± 0.44 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.4 | 5.8 | 3.59 ± 0.46 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.7 | 7.3 | 4.48 ± 0.56 |
| mattcl-py | input-kcen | 48.1 ± 0.7 | 47.0 | 51.3 | 34.22 ± 4.07 |
| mattcl-py | input-mattcl | 48.4 ± 0.7 | 46.6 | 50.0 | 34.41 ± 4.10 |
| mattcl-py | input-mikofo | 48.4 ± 0.6 | 47.2 | 50.6 | 34.44 ± 4.09 |
| mattcl-py | input-lanjian | 48.5 ± 0.6 | 47.2 | 50.1 | 34.49 ± 4.10 |
| kcen | input-mattcl | 175.7 ± 1.0 | 174.2 | 177.3 | 124.99 ± 14.79 |
| kcen | input-mikofo | 214.5 ± 1.6 | 211.5 | 216.9 | 152.56 ± 18.07 |
| kcen | input-kcen | 224.8 ± 2.7 | 221.6 | 229.7 | 159.89 ± 19.00 |
| kcen | input-lanjian | 364.4 ± 4.5 | 358.1 | 368.6 | 259.13 ± 30.80 |
| mikofo | input-mattcl | 512.6 ± 17.3 | 499.1 | 541.0 | 364.58 ± 44.83 |
| mikofo | input-mikofo | 581.0 ± 12.6 | 563.5 | 595.0 | 413.20 ± 49.67 |
| mikofo | input-kcen | 693.3 ± 17.1 | 681.1 | 718.1 | 493.10 ± 59.56 |
| mikofo | input-lanjian | 992.5 ± 25.0 | 966.5 | 1016.4 | 705.88 ± 85.34 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|