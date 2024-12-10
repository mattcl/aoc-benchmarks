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
| mattcl | input-mikofo | 1.4 ± 0.2 | 0.9 | 2.2 | 1.00 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 1.9 | 1.00 ± 0.18 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.9 | 2.3 | 1.00 ± 0.18 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.9 | 2.1 | 1.00 ± 0.18 |
| lanjian | input-mattcl | 3.9 ± 0.2 | 3.5 | 5.2 | 2.77 ± 0.40 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 3.8 | 5.7 | 3.34 ± 0.49 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.4 | 5.6 | 3.57 ± 0.49 |
| lanjian | input-lanjian | 6.2 ± 0.2 | 5.8 | 7.0 | 4.46 ± 0.60 |
| mattcl-py | input-kcen | 47.2 ± 0.6 | 46.1 | 48.7 | 33.73 ± 4.43 |
| mattcl-py | input-mattcl | 47.5 ± 0.6 | 46.7 | 49.9 | 33.99 ± 4.47 |
| mattcl-py | input-lanjian | 47.5 ± 0.5 | 46.2 | 48.5 | 34.00 ± 4.47 |
| mattcl-py | input-mikofo | 47.6 ± 0.5 | 46.6 | 49.4 | 34.07 ± 4.48 |
| kcen | input-mattcl | 171.5 ± 1.7 | 168.3 | 174.7 | 122.66 ± 16.11 |
| kcen | input-mikofo | 211.4 ± 2.8 | 208.0 | 216.2 | 151.22 ± 19.90 |
| kcen | input-kcen | 221.8 ± 1.1 | 219.7 | 223.6 | 158.65 ± 20.78 |
| kcen | input-lanjian | 357.4 ± 3.4 | 353.2 | 363.9 | 255.58 ± 33.55 |
| mikofo | input-mattcl | 532.7 ± 11.7 | 512.3 | 541.7 | 380.94 ± 50.57 |
| mikofo | input-mikofo | 570.1 ± 12.3 | 555.6 | 579.7 | 407.73 ± 54.10 |
| mikofo | input-kcen | 697.5 ± 12.5 | 686.7 | 715.5 | 498.85 ± 65.92 |
| mikofo | input-lanjian | 971.9 ± 25.8 | 942.3 | 988.7 | 695.10 ± 92.85 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|