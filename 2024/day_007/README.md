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
| mattcl | input-kcen | 1.5 ± 0.2 | 1.0 | 2.4 | 1.00 |
| mattcl | input-lanjian | 1.5 ± 0.3 | 1.1 | 2.7 | 1.00 ± 0.22 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.1 | 2.6 | 1.01 ± 0.20 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.1 | 2.8 | 1.02 ± 0.21 |
| lanjian | input-mattcl | 4.2 ± 0.4 | 3.6 | 6.2 | 2.84 ± 0.46 |
| lanjian | input-mikofo | 4.8 ± 0.3 | 4.0 | 5.8 | 3.23 ± 0.49 |
| lanjian | input-kcen | 5.1 ± 0.2 | 4.4 | 5.9 | 3.43 ± 0.49 |
| lanjian | input-lanjian | 6.3 ± 0.3 | 5.9 | 7.3 | 4.28 ± 0.60 |
| mattcl-py | input-kcen | 48.1 ± 0.5 | 46.8 | 49.2 | 32.54 ± 4.35 |
| mattcl-py | input-lanjian | 48.2 ± 0.7 | 46.4 | 50.1 | 32.65 ± 4.38 |
| mattcl-py | input-mikofo | 48.3 ± 0.6 | 46.9 | 49.4 | 32.68 ± 4.37 |
| mattcl-py | input-mattcl | 48.5 ± 0.7 | 47.1 | 50.8 | 32.83 ± 4.40 |
| kcen | input-mattcl | 176.2 ± 2.7 | 172.8 | 182.4 | 119.28 ± 16.00 |
| kcen | input-mikofo | 216.8 ± 1.5 | 214.5 | 219.3 | 146.74 ± 19.59 |
| kcen | input-kcen | 227.4 ± 2.1 | 222.9 | 230.1 | 153.93 ± 20.57 |
| kcen | input-lanjian | 366.3 ± 3.4 | 360.1 | 372.1 | 247.97 ± 33.14 |
| mikofo | input-mattcl | 520.1 ± 20.7 | 489.4 | 547.9 | 352.06 ± 48.99 |
| mikofo | input-mikofo | 578.9 ± 8.3 | 564.9 | 586.4 | 391.92 ± 52.56 |
| mikofo | input-kcen | 696.2 ± 2.4 | 693.7 | 699.5 | 471.33 ± 62.86 |
| mikofo | input-lanjian | 992.5 ± 14.6 | 975.8 | 1002.7 | 671.88 ± 90.12 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|