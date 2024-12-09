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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.4 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.3 | 1.00 ± 0.17 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.8 | 1.01 ± 0.18 |
| mattcl | input-mikofo | 1.4 ± 0.4 | 0.9 | 7.1 | 1.02 ± 0.34 |
| lanjian | input-mattcl | 3.9 ± 0.2 | 3.5 | 5.0 | 2.77 ± 0.37 |
| lanjian | input-mikofo | 4.7 ± 0.4 | 3.8 | 7.8 | 3.32 ± 0.48 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.4 | 5.7 | 3.55 ± 0.44 |
| lanjian | input-lanjian | 6.2 ± 0.2 | 5.7 | 7.1 | 4.43 ± 0.55 |
| mattcl-py | input-kcen | 47.6 ± 0.7 | 46.2 | 50.1 | 33.81 ± 4.06 |
| mattcl-py | input-lanjian | 48.0 ± 0.8 | 46.4 | 51.0 | 34.07 ± 4.10 |
| mattcl-py | input-mikofo | 48.2 ± 0.8 | 46.6 | 50.4 | 34.23 ± 4.12 |
| mattcl-py | input-mattcl | 48.2 ± 0.8 | 46.7 | 51.5 | 34.26 ± 4.12 |
| kcen | input-mattcl | 172.8 ± 2.0 | 169.4 | 175.9 | 122.75 ± 14.69 |
| kcen | input-mikofo | 213.1 ± 2.7 | 209.1 | 216.2 | 151.34 ± 18.12 |
| kcen | input-kcen | 222.4 ± 1.8 | 219.2 | 225.2 | 157.93 ± 18.85 |
| kcen | input-lanjian | 360.4 ± 5.2 | 354.9 | 366.8 | 256.01 ± 30.72 |
| mikofo | input-mattcl | 519.3 ± 16.0 | 504.1 | 546.0 | 368.82 ± 45.37 |
| mikofo | input-mikofo | 577.6 ± 12.4 | 560.5 | 590.3 | 410.23 ± 49.65 |
| mikofo | input-kcen | 698.2 ± 6.5 | 691.7 | 706.8 | 495.89 ± 59.24 |
| mikofo | input-lanjian | 974.0 ± 19.2 | 952.4 | 989.3 | 691.79 ± 83.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|