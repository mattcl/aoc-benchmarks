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
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.3 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.5 | 1.00 ± 0.17 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.4 | 1.01 ± 0.16 |
| mattcl | input-kcen | 1.4 ± 0.4 | 1.0 | 7.0 | 1.01 ± 0.32 |
| lanjian | input-mattcl | 3.9 ± 0.2 | 3.6 | 4.7 | 2.75 ± 0.34 |
| lanjian | input-mikofo | 4.5 ± 0.3 | 3.9 | 5.4 | 3.13 ± 0.41 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.5 | 5.6 | 3.52 ± 0.42 |
| lanjian | input-lanjian | 6.2 ± 0.2 | 5.9 | 6.9 | 4.37 ± 0.51 |
| mattcl-py | input-kcen | 47.4 ± 0.6 | 46.1 | 50.6 | 33.21 ± 3.75 |
| mattcl-py | input-mattcl | 47.6 ± 0.5 | 46.6 | 48.5 | 33.37 ± 3.76 |
| mattcl-py | input-mikofo | 47.7 ± 0.7 | 46.5 | 50.9 | 33.40 ± 3.77 |
| mattcl-py | input-lanjian | 47.7 ± 0.5 | 46.5 | 48.6 | 33.41 ± 3.76 |
| kcen | input-mattcl | 173.4 ± 2.1 | 171.0 | 178.7 | 121.51 ± 13.70 |
| kcen | input-mikofo | 213.3 ± 2.0 | 209.6 | 215.5 | 149.49 ± 16.81 |
| kcen | input-kcen | 222.2 ± 2.1 | 218.6 | 225.9 | 155.72 ± 17.51 |
| kcen | input-lanjian | 362.0 ± 3.7 | 358.4 | 368.9 | 253.73 ± 28.55 |
| mikofo | input-mattcl | 530.1 ± 28.6 | 493.0 | 555.7 | 371.50 ± 46.20 |
| mikofo | input-mikofo | 578.1 ± 5.1 | 573.1 | 586.0 | 405.17 ± 45.54 |
| mikofo | input-kcen | 691.8 ± 12.3 | 673.3 | 698.9 | 484.81 ± 55.01 |
| mikofo | input-lanjian | 996.9 ± 6.9 | 988.9 | 1001.0 | 698.64 ± 78.44 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|