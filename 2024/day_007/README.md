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
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 1.9 | 1.00 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.4 | 1.00 ± 0.17 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.6 | 1.02 ± 0.18 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.4 | 1.02 ± 0.18 |
| lanjian | input-mattcl | 4.1 ± 0.4 | 3.5 | 5.2 | 2.94 ± 0.42 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 4.0 | 5.5 | 3.41 ± 0.42 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.3 | 5.7 | 3.62 ± 0.42 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 7.0 | 4.59 ± 0.53 |
| mattcl-py | input-kcen | 47.9 ± 0.6 | 46.6 | 50.4 | 34.78 ± 3.83 |
| mattcl-py | input-lanjian | 48.3 ± 0.6 | 47.3 | 51.0 | 35.06 ± 3.86 |
| mattcl-py | input-mikofo | 48.3 ± 0.6 | 47.1 | 49.6 | 35.07 ± 3.86 |
| mattcl-py | input-mattcl | 48.6 ± 0.8 | 47.2 | 51.6 | 35.30 ± 3.90 |
| kcen | input-mattcl | 174.2 ± 1.5 | 172.2 | 177.7 | 126.47 ± 13.88 |
| kcen | input-mikofo | 213.5 ± 1.6 | 210.9 | 216.8 | 155.03 ± 17.00 |
| kcen | input-kcen | 225.3 ± 2.6 | 220.8 | 228.6 | 163.57 ± 17.99 |
| kcen | input-lanjian | 362.9 ± 7.1 | 356.1 | 377.8 | 263.46 ± 29.27 |
| mikofo | input-mattcl | 515.1 ± 3.5 | 510.9 | 519.7 | 373.98 ± 40.99 |
| mikofo | input-mikofo | 572.6 ± 10.4 | 558.0 | 581.7 | 415.72 ± 46.11 |
| mikofo | input-kcen | 689.2 ± 9.2 | 678.7 | 700.2 | 500.36 ± 55.15 |
| mikofo | input-lanjian | 1001.1 ± 5.3 | 997.3 | 1007.1 | 726.78 ± 79.61 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|