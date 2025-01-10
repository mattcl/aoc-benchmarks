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
| mattcl | input-kcen | 1.5 ± 0.2 | 1.1 | 2.5 | 1.00 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.1 | 2.6 | 1.01 ± 0.20 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.1 | 2.5 | 1.02 ± 0.20 |
| mattcl | input-mikofo | 1.6 ± 0.3 | 1.1 | 2.7 | 1.04 ± 0.23 |
| lanjian | input-mattcl | 4.2 ± 0.3 | 3.7 | 5.3 | 2.77 ± 0.43 |
| lanjian | input-mikofo | 4.9 ± 0.3 | 4.2 | 5.7 | 3.28 ± 0.48 |
| lanjian | input-kcen | 5.1 ± 0.2 | 4.7 | 5.9 | 3.40 ± 0.48 |
| lanjian | input-lanjian | 6.4 ± 0.2 | 5.9 | 7.3 | 4.28 ± 0.60 |
| mattcl-py | input-kcen | 48.2 ± 0.6 | 46.9 | 50.4 | 32.17 ± 4.39 |
| mattcl-py | input-mattcl | 48.6 ± 0.6 | 47.4 | 50.0 | 32.46 ± 4.43 |
| mattcl-py | input-lanjian | 48.6 ± 0.6 | 47.4 | 49.7 | 32.48 ± 4.43 |
| mattcl-py | input-mikofo | 48.7 ± 0.6 | 47.8 | 50.6 | 32.53 ± 4.44 |
| kcen | input-mattcl | 176.0 ± 1.7 | 174.0 | 179.1 | 117.55 ± 16.02 |
| kcen | input-mikofo | 215.5 ± 1.4 | 212.9 | 217.7 | 143.92 ± 19.58 |
| kcen | input-kcen | 228.5 ± 2.6 | 224.0 | 233.6 | 152.63 ± 20.82 |
| kcen | input-lanjian | 366.2 ± 2.9 | 361.6 | 370.4 | 244.59 ± 33.30 |
| mikofo | input-mattcl | 519.8 ± 13.3 | 504.4 | 539.7 | 347.18 ± 48.03 |
| mikofo | input-mikofo | 585.7 ± 11.9 | 569.3 | 595.7 | 391.20 ± 53.77 |
| mikofo | input-kcen | 693.3 ± 11.1 | 681.7 | 705.7 | 463.12 ± 63.39 |
| mikofo | input-lanjian | 990.7 ± 8.8 | 980.5 | 995.9 | 661.75 ± 90.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|