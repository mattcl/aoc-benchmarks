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
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.1 | 2.3 | 1.00 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.3 | 1.00 ± 0.17 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.1 | 2.6 | 1.00 ± 0.17 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.2 | 1.01 ± 0.16 |
| lanjian | input-mattcl | 3.9 ± 0.2 | 3.5 | 4.9 | 2.73 ± 0.33 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 4.0 | 5.7 | 3.32 ± 0.42 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.5 | 6.7 | 3.54 ± 0.42 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 7.1 | 4.39 ± 0.51 |
| mattcl-py | input-kcen | 47.3 ± 0.6 | 46.1 | 49.8 | 33.21 ± 3.64 |
| mattcl-py | input-mikofo | 47.5 ± 0.7 | 46.2 | 50.7 | 33.33 ± 3.66 |
| mattcl-py | input-mattcl | 47.6 ± 0.5 | 46.5 | 48.5 | 33.45 ± 3.66 |
| mattcl-py | input-lanjian | 48.0 ± 0.8 | 46.4 | 51.6 | 33.69 ± 3.71 |
| kcen | input-mattcl | 176.6 ± 2.6 | 172.3 | 182.0 | 123.99 ± 13.63 |
| kcen | input-mikofo | 214.8 ± 4.2 | 209.5 | 221.5 | 150.82 ± 16.68 |
| kcen | input-kcen | 228.1 ± 2.2 | 224.1 | 231.5 | 160.12 ± 17.51 |
| kcen | input-lanjian | 365.7 ± 2.4 | 363.5 | 371.0 | 256.78 ± 28.01 |
| mikofo | input-mattcl | 523.9 ± 17.5 | 502.8 | 543.4 | 367.82 ± 41.89 |
| mikofo | input-mikofo | 571.6 ± 11.6 | 555.5 | 583.1 | 401.31 ± 44.46 |
| mikofo | input-kcen | 680.4 ± 10.5 | 670.9 | 693.9 | 477.70 ± 52.54 |
| mikofo | input-lanjian | 977.4 ± 11.3 | 967.0 | 989.4 | 686.22 ± 75.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|