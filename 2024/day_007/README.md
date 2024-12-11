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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.5 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.1 | 1.1 | 1.9 | 1.00 ± 0.18 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.9 | 2.4 | 1.01 ± 0.19 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.2 | 1.01 ± 0.20 |
| lanjian | input-mattcl | 3.9 ± 0.2 | 3.5 | 4.9 | 2.81 ± 0.45 |
| lanjian | input-mikofo | 4.4 ± 0.3 | 3.8 | 5.5 | 3.14 ± 0.51 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.3 | 5.6 | 3.58 ± 0.54 |
| lanjian | input-lanjian | 6.2 ± 0.2 | 5.8 | 7.1 | 4.45 ± 0.67 |
| mattcl-py | input-kcen | 47.2 ± 0.6 | 45.7 | 48.5 | 33.67 ± 4.97 |
| mattcl-py | input-mikofo | 47.6 ± 0.7 | 46.5 | 50.5 | 33.95 ± 5.02 |
| mattcl-py | input-lanjian | 47.6 ± 0.6 | 46.0 | 48.9 | 33.98 ± 5.02 |
| mattcl-py | input-mattcl | 47.7 ± 0.6 | 46.5 | 50.2 | 34.04 ± 5.03 |
| kcen | input-mattcl | 173.0 ± 2.7 | 169.7 | 177.5 | 123.46 ± 18.27 |
| kcen | input-mikofo | 211.3 ± 2.4 | 208.9 | 215.9 | 150.80 ± 22.25 |
| kcen | input-kcen | 223.1 ± 1.1 | 220.3 | 224.9 | 159.24 ± 23.44 |
| kcen | input-lanjian | 363.1 ± 4.4 | 357.3 | 371.0 | 259.20 ± 38.26 |
| mikofo | input-mattcl | 522.2 ± 27.6 | 488.4 | 555.3 | 372.76 ± 58.28 |
| mikofo | input-mikofo | 578.7 ± 14.1 | 559.7 | 591.9 | 413.07 ± 61.60 |
| mikofo | input-kcen | 694.3 ± 19.0 | 666.2 | 707.8 | 495.58 ± 74.16 |
| mikofo | input-lanjian | 986.6 ± 23.5 | 970.1 | 1013.5 | 704.27 ± 104.97 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|