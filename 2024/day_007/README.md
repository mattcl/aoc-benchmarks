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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 1.9 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.4 | 1.01 ± 0.17 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.1 | 2.4 | 1.02 ± 0.19 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.1 | 2.3 | 1.05 ± 0.19 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.5 | 5.2 | 2.85 ± 0.41 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 3.8 | 6.3 | 3.38 ± 0.46 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.5 | 5.4 | 3.58 ± 0.44 |
| lanjian | input-lanjian | 6.5 ± 0.5 | 5.8 | 10.9 | 4.64 ± 0.65 |
| mattcl-py | input-kcen | 48.1 ± 0.5 | 46.6 | 49.3 | 34.46 ± 4.07 |
| mattcl-py | input-mikofo | 48.6 ± 0.5 | 47.6 | 49.7 | 34.80 ± 4.10 |
| mattcl-py | input-lanjian | 48.7 ± 0.7 | 47.2 | 51.4 | 34.86 ± 4.12 |
| mattcl-py | input-mattcl | 48.7 ± 0.8 | 47.2 | 51.7 | 34.88 ± 4.13 |
| kcen | input-mattcl | 175.7 ± 1.5 | 172.6 | 178.1 | 125.92 ± 14.82 |
| kcen | input-mikofo | 215.7 ± 1.8 | 213.2 | 219.1 | 154.55 ± 18.19 |
| kcen | input-kcen | 228.4 ± 1.6 | 224.6 | 230.4 | 163.66 ± 19.25 |
| kcen | input-lanjian | 363.3 ± 3.3 | 359.5 | 368.5 | 260.30 ± 30.66 |
| mikofo | input-mattcl | 527.4 ± 7.8 | 516.6 | 538.2 | 377.88 ± 44.72 |
| mikofo | input-mikofo | 582.6 ± 7.8 | 570.9 | 590.1 | 417.45 ± 49.33 |
| mikofo | input-kcen | 687.4 ± 9.6 | 679.6 | 700.0 | 492.50 ± 58.23 |
| mikofo | input-lanjian | 993.8 ± 1.8 | 992.6 | 995.9 | 712.07 ± 83.62 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|