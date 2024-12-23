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
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.1 | 2.3 | 1.00 |
| mattcl | input-kcen | 1.5 ± 0.2 | 1.1 | 2.6 | 1.00 ± 0.18 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.0 | 2.5 | 1.01 ± 0.19 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.1 | 2.2 | 1.02 ± 0.17 |
| lanjian | input-mattcl | 4.1 ± 0.3 | 3.6 | 5.3 | 2.81 ± 0.40 |
| lanjian | input-mikofo | 4.7 ± 0.4 | 4.0 | 8.5 | 3.22 ± 0.48 |
| lanjian | input-kcen | 5.1 ± 0.2 | 4.5 | 5.9 | 3.49 ± 0.45 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.7 | 7.0 | 4.35 ± 0.55 |
| mattcl-py | input-kcen | 47.7 ± 0.5 | 46.5 | 48.6 | 32.92 ± 3.99 |
| mattcl-py | input-mikofo | 47.9 ± 0.6 | 46.8 | 50.1 | 33.03 ± 4.01 |
| mattcl-py | input-mattcl | 47.9 ± 0.6 | 46.3 | 50.0 | 33.03 ± 4.01 |
| mattcl-py | input-lanjian | 48.0 ± 0.7 | 46.7 | 50.5 | 33.14 ± 4.03 |
| kcen | input-mattcl | 177.7 ± 2.7 | 174.5 | 182.5 | 122.62 ± 14.92 |
| kcen | input-mikofo | 216.7 ± 3.5 | 211.6 | 222.1 | 149.60 ± 18.22 |
| kcen | input-kcen | 230.3 ± 3.1 | 225.2 | 233.5 | 158.92 ± 19.30 |
| kcen | input-lanjian | 372.4 ± 4.2 | 368.4 | 378.7 | 257.02 ± 31.17 |
| mikofo | input-mattcl | 522.5 ± 9.1 | 515.1 | 534.9 | 360.64 ± 43.99 |
| mikofo | input-mikofo | 583.7 ± 12.1 | 564.9 | 595.1 | 402.85 ± 49.35 |
| mikofo | input-kcen | 691.4 ± 20.0 | 672.5 | 713.8 | 477.20 ± 59.24 |
| mikofo | input-lanjian | 1020.9 ± 41.4 | 995.0 | 1068.7 | 704.61 ± 89.74 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|