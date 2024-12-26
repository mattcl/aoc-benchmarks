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
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.1 | 2.3 | 1.00 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.0 | 2.5 | 1.00 ± 0.18 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.1 | 2.6 | 1.01 ± 0.18 |
| mattcl | input-kcen | 1.5 ± 0.2 | 1.1 | 2.7 | 1.01 ± 0.20 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.6 | 5.1 | 2.77 ± 0.39 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 4.0 | 5.5 | 3.26 ± 0.43 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.4 | 5.6 | 3.46 ± 0.43 |
| lanjian | input-lanjian | 6.4 ± 0.2 | 5.9 | 7.4 | 4.40 ± 0.54 |
| mattcl-py | input-kcen | 47.6 ± 0.6 | 46.6 | 49.3 | 32.81 ± 3.89 |
| mattcl-py | input-mattcl | 47.9 ± 0.7 | 46.5 | 51.0 | 32.98 ± 3.92 |
| mattcl-py | input-lanjian | 47.9 ± 0.6 | 46.8 | 49.5 | 33.00 ± 3.91 |
| mattcl-py | input-mikofo | 47.9 ± 0.7 | 46.4 | 49.9 | 33.03 ± 3.92 |
| kcen | input-mattcl | 176.7 ± 1.9 | 173.2 | 179.7 | 121.74 ± 14.40 |
| kcen | input-mikofo | 215.5 ± 2.9 | 209.9 | 220.0 | 148.50 ± 17.61 |
| kcen | input-kcen | 228.2 ± 2.6 | 224.2 | 233.1 | 157.24 ± 18.61 |
| kcen | input-lanjian | 368.1 ± 4.5 | 363.2 | 373.8 | 253.64 ± 30.04 |
| mikofo | input-mattcl | 526.0 ± 12.8 | 505.4 | 536.6 | 362.47 ± 43.60 |
| mikofo | input-mikofo | 583.8 ± 7.0 | 573.8 | 592.5 | 402.28 ± 47.64 |
| mikofo | input-kcen | 692.7 ± 12.7 | 675.4 | 705.2 | 477.29 ± 56.91 |
| mikofo | input-lanjian | 976.6 ± 12.6 | 962.1 | 984.1 | 672.92 ± 79.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|