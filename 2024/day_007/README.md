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
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.1 | 2.3 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.1 | 1.1 | 1.8 | 1.00 ± 0.15 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.6 | 1.01 ± 0.16 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.1 | 2.5 | 1.03 ± 0.19 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.6 | 5.0 | 2.86 ± 0.39 |
| lanjian | input-mikofo | 4.6 ± 0.3 | 3.9 | 5.7 | 3.28 ± 0.43 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.4 | 5.8 | 3.55 ± 0.42 |
| lanjian | input-lanjian | 6.2 ± 0.3 | 5.7 | 7.2 | 4.41 ± 0.52 |
| mattcl-py | input-kcen | 47.5 ± 0.6 | 46.4 | 48.9 | 33.59 ± 3.76 |
| mattcl-py | input-mikofo | 47.5 ± 0.5 | 46.2 | 48.6 | 33.63 ± 3.76 |
| mattcl-py | input-lanjian | 47.7 ± 0.5 | 46.3 | 48.9 | 33.76 ± 3.77 |
| mattcl-py | input-mattcl | 47.9 ± 0.8 | 46.3 | 51.0 | 33.85 ± 3.80 |
| kcen | input-mattcl | 177.4 ± 4.4 | 171.8 | 190.1 | 125.46 ± 14.30 |
| kcen | input-mikofo | 217.3 ± 1.8 | 214.5 | 220.9 | 153.68 ± 17.14 |
| kcen | input-kcen | 232.1 ± 14.0 | 225.2 | 275.8 | 164.19 ± 20.76 |
| kcen | input-lanjian | 366.8 ± 3.1 | 362.4 | 370.5 | 259.48 ± 28.94 |
| mikofo | input-mattcl | 528.2 ± 19.4 | 506.2 | 549.2 | 373.65 ± 43.77 |
| mikofo | input-mikofo | 570.8 ± 9.9 | 560.2 | 581.0 | 403.74 ± 45.45 |
| mikofo | input-kcen | 691.6 ± 9.0 | 684.8 | 704.8 | 489.20 ± 54.78 |
| mikofo | input-lanjian | 984.5 ± 6.2 | 980.2 | 991.7 | 696.42 ± 77.58 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|