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
| mattcl | input-kcen | 1.4 ± 0.2 | 0.9 | 2.3 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.5 | 1.01 ± 0.17 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.1 | 2.4 | 1.01 ± 0.17 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.0 | 3.2 | 1.03 ± 0.21 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.5 | 5.0 | 2.80 ± 0.39 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 4.0 | 5.4 | 3.33 ± 0.44 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.5 | 5.6 | 3.56 ± 0.45 |
| lanjian | input-lanjian | 6.4 ± 0.2 | 5.8 | 7.4 | 4.49 ± 0.56 |
| mattcl-py | input-kcen | 48.0 ± 0.7 | 46.7 | 50.3 | 33.94 ± 4.05 |
| mattcl-py | input-mikofo | 48.4 ± 0.6 | 47.0 | 49.7 | 34.22 ± 4.07 |
| mattcl-py | input-lanjian | 48.5 ± 0.7 | 47.0 | 50.3 | 34.27 ± 4.09 |
| mattcl-py | input-mattcl | 48.5 ± 0.6 | 47.5 | 50.1 | 34.29 ± 4.08 |
| kcen | input-mattcl | 175.2 ± 1.6 | 172.9 | 179.0 | 123.77 ± 14.70 |
| kcen | input-mikofo | 215.8 ± 2.1 | 212.5 | 218.9 | 152.48 ± 18.11 |
| kcen | input-kcen | 226.9 ± 2.0 | 222.8 | 228.9 | 160.31 ± 19.03 |
| kcen | input-lanjian | 367.4 ± 0.9 | 365.9 | 368.8 | 259.56 ± 30.74 |
| mikofo | input-mattcl | 521.8 ± 17.4 | 497.4 | 541.4 | 368.63 ± 45.34 |
| mikofo | input-mikofo | 579.7 ± 22.2 | 562.3 | 606.8 | 409.55 ± 50.97 |
| mikofo | input-kcen | 694.4 ± 14.8 | 682.7 | 713.9 | 490.57 ± 59.01 |
| mikofo | input-lanjian | 995.3 ± 14.3 | 986.3 | 1011.7 | 703.12 ± 83.86 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|