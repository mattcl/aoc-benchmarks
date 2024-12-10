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
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.1 | 2.0 | 1.00 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.4 | 1.00 ± 0.16 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.1 | 1.00 ± 0.15 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.2 | 1.02 ± 0.16 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.5 | 5.0 | 2.81 ± 0.37 |
| lanjian | input-mikofo | 4.5 ± 0.3 | 4.0 | 5.6 | 3.19 ± 0.41 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.4 | 5.9 | 3.53 ± 0.40 |
| lanjian | input-lanjian | 6.2 ± 0.2 | 5.7 | 7.0 | 4.40 ± 0.49 |
| mattcl-py | input-kcen | 47.2 ± 0.6 | 45.8 | 49.2 | 33.27 ± 3.57 |
| mattcl-py | input-lanjian | 47.7 ± 0.6 | 46.5 | 50.6 | 33.60 ± 3.61 |
| mattcl-py | input-mattcl | 47.8 ± 0.6 | 46.6 | 50.3 | 33.63 ± 3.62 |
| mattcl-py | input-mikofo | 47.8 ± 0.7 | 46.9 | 50.6 | 33.70 ± 3.63 |
| kcen | input-mattcl | 172.5 ± 2.4 | 168.8 | 177.1 | 121.47 ± 13.08 |
| kcen | input-mikofo | 211.1 ± 2.3 | 208.1 | 215.8 | 148.67 ± 15.96 |
| kcen | input-kcen | 221.0 ± 1.2 | 219.0 | 222.7 | 155.65 ± 16.64 |
| kcen | input-lanjian | 359.6 ± 2.8 | 355.8 | 364.3 | 253.25 ± 27.11 |
| mikofo | input-mattcl | 519.5 ± 10.4 | 509.0 | 535.1 | 365.80 ± 39.74 |
| mikofo | input-mikofo | 580.3 ± 9.2 | 572.5 | 594.4 | 408.65 ± 44.11 |
| mikofo | input-kcen | 681.5 ± 10.6 | 674.9 | 697.0 | 479.90 ± 51.78 |
| mikofo | input-lanjian | 981.1 ± 13.5 | 965.5 | 989.5 | 690.88 ± 74.38 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|