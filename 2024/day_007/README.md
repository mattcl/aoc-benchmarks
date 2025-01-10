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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.1 | 1.9 | 1.00 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.1 | 2.6 | 1.02 ± 0.19 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.1 | 2.7 | 1.03 ± 0.19 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.1 | 2.4 | 1.03 ± 0.18 |
| lanjian | input-mattcl | 4.1 ± 0.3 | 3.6 | 5.2 | 2.87 ± 0.40 |
| lanjian | input-mikofo | 4.8 ± 0.3 | 3.9 | 5.7 | 3.33 ± 0.43 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.4 | 5.9 | 3.54 ± 0.42 |
| lanjian | input-lanjian | 6.3 ± 0.3 | 5.9 | 7.3 | 4.41 ± 0.52 |
| mattcl-py | input-mikofo | 47.6 ± 0.5 | 46.3 | 49.2 | 33.33 ± 3.74 |
| mattcl-py | input-kcen | 47.7 ± 0.8 | 46.0 | 50.5 | 33.37 ± 3.76 |
| mattcl-py | input-mattcl | 47.9 ± 0.7 | 46.8 | 50.8 | 33.53 ± 3.77 |
| mattcl-py | input-lanjian | 47.9 ± 0.5 | 46.6 | 49.2 | 33.54 ± 3.76 |
| kcen | input-mattcl | 178.0 ± 3.6 | 173.2 | 188.3 | 124.63 ± 14.13 |
| kcen | input-mikofo | 217.5 ± 2.5 | 212.9 | 220.7 | 152.31 ± 17.08 |
| kcen | input-kcen | 230.3 ± 2.1 | 226.3 | 234.4 | 161.25 ± 18.05 |
| kcen | input-lanjian | 371.2 ± 4.0 | 366.9 | 376.6 | 259.92 ± 29.13 |
| mikofo | input-mattcl | 526.8 ± 37.5 | 489.7 | 589.3 | 368.84 ± 48.81 |
| mikofo | input-mikofo | 565.2 ± 10.9 | 554.0 | 580.5 | 395.77 ± 44.80 |
| mikofo | input-kcen | 691.3 ± 14.2 | 671.0 | 704.1 | 484.04 ± 54.90 |
| mikofo | input-lanjian | 981.3 ± 6.5 | 975.4 | 988.3 | 687.12 ± 76.78 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|