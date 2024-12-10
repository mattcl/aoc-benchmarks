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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.5 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.4 | 1.00 ± 0.17 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.4 | 1.01 ± 0.17 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.3 | 1.03 ± 0.18 |
| lanjian | input-mattcl | 3.8 ± 0.2 | 3.5 | 4.6 | 2.77 ± 0.34 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 4.0 | 5.5 | 3.39 ± 0.44 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.4 | 5.5 | 3.61 ± 0.44 |
| lanjian | input-lanjian | 6.3 ± 0.3 | 5.7 | 9.3 | 4.53 ± 0.57 |
| mattcl-py | input-kcen | 47.9 ± 0.6 | 46.9 | 50.3 | 34.64 ± 4.00 |
| mattcl-py | input-lanjian | 48.2 ± 0.5 | 47.2 | 49.7 | 34.86 ± 4.02 |
| mattcl-py | input-mattcl | 48.2 ± 0.6 | 47.0 | 49.7 | 34.86 ± 4.02 |
| mattcl-py | input-mikofo | 48.4 ± 0.8 | 46.9 | 52.1 | 35.03 ± 4.06 |
| kcen | input-mattcl | 172.3 ± 1.5 | 168.8 | 174.4 | 124.63 ± 14.35 |
| kcen | input-mikofo | 210.5 ± 1.7 | 208.4 | 214.1 | 152.27 ± 17.53 |
| kcen | input-kcen | 221.9 ± 2.4 | 218.1 | 226.5 | 160.51 ± 18.51 |
| kcen | input-lanjian | 356.0 ± 4.0 | 350.5 | 360.7 | 257.50 ± 29.71 |
| mikofo | input-mattcl | 521.1 ± 8.4 | 508.9 | 531.7 | 376.86 ± 43.70 |
| mikofo | input-mikofo | 580.3 ± 11.6 | 564.9 | 593.1 | 419.71 ± 48.91 |
| mikofo | input-kcen | 694.0 ± 3.8 | 691.5 | 699.6 | 501.90 ± 57.70 |
| mikofo | input-lanjian | 983.4 ± 11.6 | 972.3 | 995.5 | 711.21 ± 82.10 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|