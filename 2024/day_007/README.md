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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.2 | 1.00 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.1 | 2.8 | 1.01 ± 0.19 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.0 | 2.3 | 1.01 ± 0.18 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.0 | 2.7 | 1.02 ± 0.20 |
| lanjian | input-mattcl | 4.1 ± 0.3 | 3.6 | 5.4 | 2.83 ± 0.43 |
| lanjian | input-mikofo | 4.8 ± 0.3 | 4.0 | 5.6 | 3.33 ± 0.48 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.4 | 6.0 | 3.51 ± 0.49 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.7 | 7.1 | 4.38 ± 0.60 |
| mattcl-py | input-kcen | 47.8 ± 0.9 | 46.2 | 51.9 | 33.36 ± 4.44 |
| mattcl-py | input-mattcl | 48.1 ± 0.7 | 46.6 | 49.7 | 33.54 ± 4.45 |
| mattcl-py | input-lanjian | 48.1 ± 0.8 | 46.1 | 50.3 | 33.57 ± 4.46 |
| mattcl-py | input-mikofo | 48.1 ± 0.8 | 46.5 | 51.3 | 33.58 ± 4.47 |
| kcen | input-mattcl | 174.5 ± 1.8 | 171.9 | 178.5 | 121.80 ± 16.11 |
| kcen | input-mikofo | 214.9 ± 2.1 | 211.5 | 218.1 | 149.97 ± 19.84 |
| kcen | input-kcen | 223.3 ± 2.7 | 220.3 | 227.5 | 155.84 ± 20.64 |
| kcen | input-lanjian | 368.2 ± 3.8 | 360.9 | 373.1 | 256.96 ± 34.00 |
| mikofo | input-mattcl | 530.6 ± 14.0 | 509.5 | 546.9 | 370.28 ± 49.81 |
| mikofo | input-mikofo | 578.2 ± 8.6 | 569.5 | 590.4 | 403.54 ± 53.57 |
| mikofo | input-kcen | 693.3 ± 9.4 | 684.4 | 706.5 | 483.86 ± 64.16 |
| mikofo | input-lanjian | 978.7 ± 14.9 | 964.2 | 994.0 | 682.99 ± 90.70 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|