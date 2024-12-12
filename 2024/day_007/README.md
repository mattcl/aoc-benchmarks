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
| mattcl | input-mattcl | 1.9 ± 0.1 | 1.6 | 2.4 | 1.00 |
| mattcl | input-kcen | 1.9 ± 0.2 | 1.5 | 2.9 | 1.00 ± 0.12 |
| mattcl | input-lanjian | 1.9 ± 0.2 | 1.5 | 2.7 | 1.01 ± 0.12 |
| mattcl | input-mikofo | 1.9 ± 0.2 | 1.5 | 2.8 | 1.01 ± 0.13 |
| lanjian | input-mattcl | 4.6 ± 0.4 | 4.0 | 5.7 | 2.41 ± 0.26 |
| lanjian | input-mikofo | 5.2 ± 0.3 | 4.5 | 6.2 | 2.77 ± 0.26 |
| lanjian | input-kcen | 5.6 ± 0.2 | 5.0 | 6.4 | 2.95 ± 0.26 |
| lanjian | input-lanjian | 6.8 ± 0.2 | 6.3 | 7.7 | 3.61 ± 0.31 |
| mattcl-py | input-kcen | 48.7 ± 0.8 | 46.9 | 51.5 | 25.77 ± 2.05 |
| mattcl-py | input-mikofo | 49.0 ± 0.6 | 47.9 | 50.7 | 25.92 ± 2.05 |
| mattcl-py | input-mattcl | 49.1 ± 0.6 | 47.8 | 50.4 | 25.98 ± 2.05 |
| mattcl-py | input-lanjian | 49.2 ± 0.6 | 47.9 | 51.9 | 25.99 ± 2.05 |
| kcen | input-mattcl | 175.5 ± 1.3 | 174.0 | 177.9 | 92.76 ± 7.27 |
| kcen | input-mikofo | 216.6 ± 2.8 | 212.8 | 221.4 | 114.51 ± 9.05 |
| kcen | input-kcen | 227.4 ± 2.1 | 223.5 | 230.3 | 120.24 ± 9.45 |
| kcen | input-lanjian | 368.1 ± 2.9 | 363.6 | 371.8 | 194.62 ± 15.26 |
| mikofo | input-mattcl | 524.6 ± 15.9 | 508.6 | 548.1 | 277.35 ± 23.22 |
| mikofo | input-mikofo | 583.2 ± 5.6 | 577.4 | 589.5 | 308.32 ± 24.24 |
| mikofo | input-kcen | 713.0 ± 22.2 | 688.4 | 741.6 | 376.95 ± 31.66 |
| mikofo | input-lanjian | 995.9 ± 5.9 | 990.3 | 1002.0 | 526.56 ± 41.20 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|