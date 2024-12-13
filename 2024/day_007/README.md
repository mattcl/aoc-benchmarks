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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.7 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.1 | 2.4 | 1.00 ± 0.18 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.4 | 1.01 ± 0.18 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.3 | 1.01 ± 0.19 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.6 | 4.9 | 2.82 ± 0.42 |
| lanjian | input-mikofo | 4.6 ± 0.3 | 3.8 | 5.6 | 3.27 ± 0.48 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.4 | 5.4 | 3.54 ± 0.48 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.9 | 7.2 | 4.44 ± 0.59 |
| mattcl-py | input-kcen | 47.4 ± 0.8 | 45.7 | 50.5 | 33.45 ± 4.39 |
| mattcl-py | input-mikofo | 47.7 ± 0.6 | 46.4 | 49.8 | 33.66 ± 4.40 |
| mattcl-py | input-mattcl | 47.8 ± 0.7 | 46.2 | 50.2 | 33.73 ± 4.42 |
| mattcl-py | input-lanjian | 48.0 ± 0.7 | 46.5 | 50.9 | 33.91 ± 4.44 |
| kcen | input-mattcl | 175.8 ± 2.8 | 172.2 | 179.2 | 124.14 ± 16.29 |
| kcen | input-mikofo | 214.4 ± 2.1 | 211.9 | 218.0 | 151.39 ± 19.77 |
| kcen | input-kcen | 224.2 ± 2.2 | 222.1 | 228.5 | 158.33 ± 20.67 |
| kcen | input-lanjian | 371.6 ± 13.1 | 361.9 | 403.0 | 262.36 ± 35.38 |
| mikofo | input-mattcl | 524.7 ± 5.4 | 517.2 | 531.1 | 370.46 ± 48.39 |
| mikofo | input-mikofo | 569.4 ± 8.7 | 559.6 | 578.5 | 402.06 ± 52.71 |
| mikofo | input-kcen | 686.2 ± 2.6 | 683.9 | 689.9 | 484.50 ± 63.11 |
| mikofo | input-lanjian | 981.6 ± 6.1 | 975.1 | 987.3 | 693.11 ± 90.35 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|