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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.7 | 1.00 ± 0.18 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.1 | 2.5 | 1.02 ± 0.18 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.1 | 2.5 | 1.03 ± 0.21 |
| lanjian | input-mattcl | 4.1 ± 0.3 | 3.6 | 5.1 | 2.81 ± 0.41 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 3.9 | 5.7 | 3.27 ± 0.46 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.4 | 6.0 | 3.48 ± 0.46 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 6.9 | 4.34 ± 0.57 |
| mattcl-py | input-kcen | 47.6 ± 0.5 | 46.4 | 48.7 | 32.96 ± 4.17 |
| mattcl-py | input-mikofo | 47.6 ± 0.6 | 46.7 | 49.5 | 32.98 ± 4.18 |
| mattcl-py | input-mattcl | 47.6 ± 0.6 | 46.4 | 48.9 | 33.00 ± 4.18 |
| mattcl-py | input-lanjian | 48.0 ± 0.5 | 46.9 | 50.1 | 33.24 ± 4.21 |
| kcen | input-mattcl | 177.7 ± 2.0 | 174.3 | 182.8 | 123.09 ± 15.60 |
| kcen | input-mikofo | 217.2 ± 2.1 | 212.7 | 220.9 | 150.43 ± 19.04 |
| kcen | input-kcen | 228.5 ± 2.8 | 224.7 | 232.7 | 158.26 ± 20.07 |
| kcen | input-lanjian | 374.6 ± 2.1 | 371.6 | 377.7 | 259.46 ± 32.78 |
| mikofo | input-mattcl | 519.7 ± 10.5 | 508.6 | 534.2 | 360.02 ± 46.01 |
| mikofo | input-mikofo | 569.9 ± 10.1 | 557.0 | 579.7 | 394.78 ± 50.31 |
| mikofo | input-kcen | 689.1 ± 9.1 | 678.1 | 697.2 | 477.31 ± 60.57 |
| mikofo | input-lanjian | 988.0 ± 22.8 | 967.2 | 1012.4 | 684.39 ± 87.81 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|