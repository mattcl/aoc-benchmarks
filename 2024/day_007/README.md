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
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.0 | 2.7 | 1.00 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.1 | 2.6 | 1.01 ± 0.23 |
| mattcl | input-kcen | 1.5 ± 0.2 | 1.1 | 2.6 | 1.01 ± 0.23 |
| mattcl | input-mattcl | 1.5 ± 0.3 | 1.1 | 2.7 | 1.03 ± 0.25 |
| lanjian | input-mattcl | 4.1 ± 0.4 | 3.6 | 5.4 | 2.79 ± 0.53 |
| lanjian | input-mikofo | 4.8 ± 0.3 | 3.9 | 5.7 | 3.29 ± 0.59 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.5 | 5.9 | 3.43 ± 0.60 |
| lanjian | input-lanjian | 6.4 ± 0.3 | 5.8 | 7.8 | 4.36 ± 0.77 |
| mattcl-py | input-kcen | 48.4 ± 0.8 | 47.3 | 51.9 | 32.95 ± 5.59 |
| mattcl-py | input-lanjian | 48.6 ± 0.7 | 47.1 | 50.4 | 33.07 ± 5.60 |
| mattcl-py | input-mikofo | 48.7 ± 0.6 | 47.2 | 49.7 | 33.12 ± 5.60 |
| mattcl-py | input-mattcl | 48.7 ± 0.6 | 47.6 | 50.4 | 33.12 ± 5.60 |
| kcen | input-mattcl | 176.6 ± 1.4 | 174.1 | 180.0 | 120.22 ± 20.31 |
| kcen | input-mikofo | 217.5 ± 2.1 | 214.2 | 221.1 | 148.06 ± 25.03 |
| kcen | input-kcen | 227.9 ± 2.5 | 224.0 | 230.8 | 155.13 ± 26.24 |
| kcen | input-lanjian | 370.2 ± 2.7 | 366.6 | 373.7 | 251.99 ± 42.57 |
| mikofo | input-mattcl | 536.8 ± 16.2 | 513.1 | 558.7 | 365.39 ± 62.64 |
| mikofo | input-mikofo | 582.5 ± 11.8 | 566.2 | 595.3 | 396.46 ± 67.38 |
| mikofo | input-kcen | 710.4 ± 8.7 | 700.6 | 721.4 | 483.55 ± 81.82 |
| mikofo | input-lanjian | 996.0 ± 23.9 | 969.4 | 1015.8 | 677.90 ± 115.55 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|