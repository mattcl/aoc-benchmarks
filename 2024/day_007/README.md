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
| mattcl | input-kcen | 1.5 ± 0.1 | 1.1 | 2.0 | 1.00 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.0 | 2.4 | 1.00 ± 0.16 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.1 | 2.2 | 1.00 ± 0.14 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.1 | 2.6 | 1.01 ± 0.18 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.5 | 5.3 | 2.76 ± 0.34 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 3.9 | 5.7 | 3.24 ± 0.38 |
| lanjian | input-kcen | 5.1 ± 0.3 | 4.5 | 7.2 | 3.49 ± 0.38 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.9 | 7.2 | 4.34 ± 0.45 |
| mattcl-py | input-kcen | 47.4 ± 0.5 | 46.3 | 48.4 | 32.58 ± 3.20 |
| mattcl-py | input-lanjian | 47.7 ± 0.6 | 46.4 | 49.4 | 32.76 ± 3.23 |
| mattcl-py | input-mattcl | 47.8 ± 0.6 | 46.4 | 49.2 | 32.82 ± 3.23 |
| mattcl-py | input-mikofo | 47.9 ± 0.6 | 47.0 | 49.6 | 32.85 ± 3.23 |
| kcen | input-mattcl | 175.4 ± 2.0 | 172.6 | 179.6 | 120.43 ± 11.83 |
| kcen | input-mikofo | 215.2 ± 2.4 | 210.6 | 218.6 | 147.73 ± 14.51 |
| kcen | input-kcen | 224.4 ± 2.0 | 221.8 | 227.7 | 154.06 ± 15.09 |
| kcen | input-lanjian | 366.7 ± 6.1 | 359.3 | 373.2 | 251.75 ± 24.92 |
| mikofo | input-mattcl | 529.8 ± 11.9 | 510.7 | 542.0 | 363.71 ± 36.41 |
| mikofo | input-mikofo | 580.1 ± 9.2 | 568.9 | 587.8 | 398.30 ± 39.37 |
| mikofo | input-kcen | 681.8 ± 19.5 | 657.8 | 698.6 | 468.13 ± 47.60 |
| mikofo | input-lanjian | 988.4 ± 4.7 | 984.0 | 993.4 | 678.63 ± 66.30 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|