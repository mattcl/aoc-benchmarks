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
| mattcl | input-lanjian | 1.4 ± 0.1 | 1.1 | 2.0 | 1.00 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.1 | 2.2 | 1.02 ± 0.16 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.6 | 1.02 ± 0.17 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.4 | 1.03 ± 0.18 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.5 | 4.7 | 2.84 ± 0.35 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 4.0 | 5.4 | 3.35 ± 0.41 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.6 | 5.9 | 3.60 ± 0.40 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.9 | 7.2 | 4.54 ± 0.50 |
| mattcl-py | input-kcen | 48.1 ± 0.5 | 46.7 | 49.8 | 34.46 ± 3.58 |
| mattcl-py | input-lanjian | 48.2 ± 0.6 | 47.0 | 49.8 | 34.59 ± 3.60 |
| mattcl-py | input-mattcl | 48.6 ± 0.6 | 47.5 | 49.7 | 34.82 ± 3.62 |
| mattcl-py | input-mikofo | 48.8 ± 0.7 | 46.8 | 50.5 | 34.96 ± 3.64 |
| kcen | input-mattcl | 175.1 ± 1.3 | 173.4 | 177.5 | 125.58 ± 13.00 |
| kcen | input-mikofo | 216.1 ± 2.2 | 213.9 | 220.7 | 154.95 ± 16.07 |
| kcen | input-kcen | 226.1 ± 2.4 | 223.1 | 229.0 | 162.14 ± 16.83 |
| kcen | input-lanjian | 366.7 ± 3.3 | 362.4 | 371.0 | 262.91 ± 27.25 |
| mikofo | input-mattcl | 527.4 ± 14.5 | 507.1 | 539.4 | 378.16 ± 40.41 |
| mikofo | input-mikofo | 569.9 ± 6.7 | 563.1 | 579.8 | 408.61 ± 42.46 |
| mikofo | input-kcen | 688.8 ± 8.3 | 681.9 | 700.9 | 493.85 ± 51.34 |
| mikofo | input-lanjian | 997.7 ± 9.0 | 991.7 | 1008.1 | 715.32 ± 74.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|