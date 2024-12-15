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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.1 | 1.9 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.7 | 1.02 ± 0.19 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.0 | 2.7 | 1.04 ± 0.20 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.1 | 2.7 | 1.05 ± 0.20 |
| lanjian | input-mattcl | 4.1 ± 0.3 | 3.5 | 5.1 | 2.89 ± 0.40 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 4.0 | 5.6 | 3.33 ± 0.43 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.4 | 5.8 | 3.52 ± 0.42 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 7.0 | 4.42 ± 0.52 |
| mattcl-py | input-kcen | 47.9 ± 0.7 | 46.8 | 51.2 | 33.58 ± 3.78 |
| mattcl-py | input-mikofo | 48.3 ± 0.6 | 46.6 | 49.7 | 33.87 ± 3.80 |
| mattcl-py | input-lanjian | 48.3 ± 0.5 | 47.4 | 50.0 | 33.89 ± 3.80 |
| mattcl-py | input-mattcl | 48.4 ± 0.5 | 47.4 | 49.3 | 33.92 ± 3.80 |
| kcen | input-mattcl | 175.3 ± 1.3 | 172.0 | 177.6 | 122.97 ± 13.75 |
| kcen | input-mikofo | 214.3 ± 1.9 | 210.7 | 217.2 | 150.31 ± 16.82 |
| kcen | input-kcen | 226.7 ± 1.3 | 223.0 | 227.8 | 159.06 ± 17.77 |
| kcen | input-lanjian | 360.8 ± 3.0 | 358.3 | 367.3 | 253.11 ± 28.32 |
| mikofo | input-mattcl | 524.9 ± 11.5 | 511.8 | 541.1 | 368.21 ± 41.87 |
| mikofo | input-mikofo | 572.9 ± 9.0 | 558.6 | 583.4 | 401.89 ± 45.28 |
| mikofo | input-kcen | 687.0 ± 9.7 | 675.1 | 696.6 | 481.96 ± 54.20 |
| mikofo | input-lanjian | 997.2 ± 4.8 | 991.6 | 1000.0 | 699.57 ± 78.12 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|