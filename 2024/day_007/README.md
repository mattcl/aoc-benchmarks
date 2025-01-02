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
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.1 | 2.4 | 1.00 |
| mattcl | input-kcen | 1.5 ± 0.2 | 1.1 | 2.7 | 1.00 ± 0.20 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.1 | 2.5 | 1.01 ± 0.21 |
| mattcl | input-lanjian | 1.5 ± 0.3 | 1.1 | 2.7 | 1.02 ± 0.23 |
| lanjian | input-mattcl | 4.0 ± 0.2 | 3.6 | 5.3 | 2.70 ± 0.41 |
| lanjian | input-mikofo | 4.8 ± 0.3 | 4.1 | 5.6 | 3.26 ± 0.49 |
| lanjian | input-kcen | 5.1 ± 0.2 | 4.4 | 5.7 | 3.43 ± 0.50 |
| lanjian | input-lanjian | 6.3 ± 0.3 | 5.8 | 9.4 | 4.30 ± 0.64 |
| mattcl-py | input-kcen | 47.8 ± 0.6 | 46.5 | 50.2 | 32.40 ± 4.54 |
| mattcl-py | input-lanjian | 48.2 ± 0.5 | 47.1 | 49.3 | 32.68 ± 4.57 |
| mattcl-py | input-mikofo | 48.3 ± 0.6 | 47.0 | 49.6 | 32.74 ± 4.58 |
| mattcl-py | input-mattcl | 48.4 ± 0.8 | 46.7 | 51.2 | 32.81 ± 4.60 |
| kcen | input-mattcl | 173.6 ± 1.7 | 170.9 | 176.9 | 117.69 ± 16.45 |
| kcen | input-mikofo | 213.6 ± 2.3 | 210.3 | 217.6 | 144.82 ± 20.25 |
| kcen | input-kcen | 227.6 ± 1.7 | 222.6 | 229.9 | 154.32 ± 21.55 |
| kcen | input-lanjian | 366.7 ± 4.6 | 356.9 | 371.5 | 248.68 ± 34.81 |
| mikofo | input-mattcl | 522.7 ± 12.0 | 511.8 | 542.1 | 354.42 ± 50.08 |
| mikofo | input-mikofo | 576.8 ± 11.6 | 562.3 | 594.0 | 391.11 ± 55.09 |
| mikofo | input-kcen | 696.7 ± 5.8 | 691.8 | 704.4 | 472.46 ± 65.99 |
| mikofo | input-lanjian | 992.4 ± 12.8 | 981.2 | 1006.3 | 672.95 ± 94.22 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|