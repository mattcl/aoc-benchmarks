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
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.1 | 2.1 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.4 | 1.00 ± 0.17 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.6 | 1.01 ± 0.18 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.5 | 1.01 ± 0.17 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.5 | 5.3 | 2.80 ± 0.37 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 3.7 | 5.5 | 3.32 ± 0.43 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.3 | 5.7 | 3.53 ± 0.42 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 7.2 | 4.45 ± 0.52 |
| mattcl-py | input-kcen | 47.9 ± 0.6 | 46.1 | 49.4 | 33.89 ± 3.79 |
| mattcl-py | input-mikofo | 48.4 ± 0.7 | 46.9 | 50.8 | 34.24 ± 3.84 |
| mattcl-py | input-lanjian | 48.4 ± 0.7 | 47.0 | 50.5 | 34.29 ± 3.84 |
| mattcl-py | input-mattcl | 48.5 ± 0.7 | 47.2 | 50.9 | 34.34 ± 3.84 |
| kcen | input-mattcl | 172.4 ± 2.1 | 168.6 | 175.4 | 122.09 ± 13.63 |
| kcen | input-mikofo | 211.7 ± 1.2 | 210.0 | 213.8 | 149.88 ± 16.66 |
| kcen | input-kcen | 223.0 ± 1.6 | 219.1 | 225.6 | 157.87 ± 17.57 |
| kcen | input-lanjian | 359.6 ± 3.0 | 353.5 | 362.9 | 254.65 ± 28.35 |
| mikofo | input-mattcl | 536.9 ± 15.2 | 518.4 | 553.0 | 380.14 ± 43.55 |
| mikofo | input-mikofo | 584.0 ± 14.8 | 572.7 | 607.2 | 413.50 ± 47.09 |
| mikofo | input-kcen | 688.7 ± 14.7 | 673.4 | 708.8 | 487.66 ± 55.14 |
| mikofo | input-lanjian | 988.4 ± 10.2 | 979.1 | 999.4 | 699.86 ± 78.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|