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
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.3 | 1.01 ± 0.19 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.1 | 2.1 | 1.02 ± 0.19 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.1 | 2.4 | 1.02 ± 0.19 |
| lanjian | input-mattcl | 4.1 ± 0.4 | 3.5 | 5.7 | 2.94 ± 0.50 |
| lanjian | input-mikofo | 4.8 ± 0.3 | 3.8 | 5.5 | 3.40 ± 0.54 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.6 | 5.7 | 3.58 ± 0.54 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.9 | 7.2 | 4.51 ± 0.68 |
| mattcl-py | input-kcen | 48.0 ± 0.7 | 46.7 | 52.4 | 34.31 ± 5.00 |
| mattcl-py | input-mattcl | 48.5 ± 0.6 | 47.3 | 49.8 | 34.62 ± 5.03 |
| mattcl-py | input-mikofo | 48.6 ± 0.7 | 47.0 | 50.0 | 34.69 ± 5.05 |
| mattcl-py | input-lanjian | 48.6 ± 0.9 | 47.4 | 53.2 | 34.72 ± 5.07 |
| kcen | input-mattcl | 172.5 ± 0.9 | 170.8 | 174.3 | 123.24 ± 17.87 |
| kcen | input-mikofo | 213.4 ± 2.7 | 211.3 | 222.2 | 152.45 ± 22.17 |
| kcen | input-kcen | 224.8 ± 2.9 | 219.9 | 230.9 | 160.58 ± 23.35 |
| kcen | input-lanjian | 361.2 ± 4.4 | 355.3 | 367.2 | 258.07 ± 37.52 |
| mikofo | input-mattcl | 522.1 ± 8.7 | 512.7 | 532.0 | 373.00 ± 54.39 |
| mikofo | input-mikofo | 583.3 ± 7.2 | 571.5 | 590.9 | 416.71 ± 60.59 |
| mikofo | input-kcen | 708.0 ± 15.1 | 695.2 | 729.1 | 505.79 ± 74.06 |
| mikofo | input-lanjian | 997.0 ± 16.2 | 980.2 | 1012.6 | 712.27 ± 103.84 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|