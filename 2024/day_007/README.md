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
| mattcl | input-kcen | 1.5 ± 0.2 | 1.0 | 2.6 | 1.00 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.1 | 2.6 | 1.01 ± 0.22 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.1 | 2.7 | 1.01 ± 0.23 |
| mattcl | input-lanjian | 1.5 ± 0.3 | 1.1 | 2.8 | 1.02 ± 0.23 |
| lanjian | input-mattcl | 4.1 ± 0.3 | 3.6 | 5.2 | 2.79 ± 0.48 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 4.0 | 5.8 | 3.19 ± 0.54 |
| lanjian | input-kcen | 5.1 ± 0.2 | 4.5 | 6.2 | 3.45 ± 0.56 |
| lanjian | input-lanjian | 6.4 ± 0.2 | 5.9 | 7.0 | 4.33 ± 0.68 |
| mattcl-py | input-kcen | 47.8 ± 0.6 | 46.6 | 49.3 | 32.56 ± 5.03 |
| mattcl-py | input-mattcl | 48.2 ± 0.6 | 46.5 | 49.7 | 32.84 ± 5.07 |
| mattcl-py | input-lanjian | 48.2 ± 0.6 | 46.7 | 50.1 | 32.89 ± 5.08 |
| mattcl-py | input-mikofo | 48.4 ± 0.8 | 47.0 | 51.8 | 32.97 ± 5.10 |
| kcen | input-mattcl | 174.2 ± 1.1 | 171.9 | 176.0 | 118.77 ± 18.29 |
| kcen | input-mikofo | 213.4 ± 1.6 | 211.4 | 216.5 | 145.48 ± 22.41 |
| kcen | input-kcen | 225.2 ± 2.3 | 222.6 | 228.5 | 153.56 ± 23.68 |
| kcen | input-lanjian | 364.0 ± 5.0 | 358.1 | 370.7 | 248.15 ± 38.34 |
| mikofo | input-mattcl | 519.9 ± 10.2 | 509.9 | 531.1 | 354.49 ± 54.99 |
| mikofo | input-mikofo | 577.3 ± 9.1 | 564.4 | 587.4 | 393.63 ± 60.89 |
| mikofo | input-kcen | 694.3 ± 7.2 | 686.8 | 704.0 | 473.39 ± 73.01 |
| mikofo | input-lanjian | 993.7 ± 3.7 | 989.5 | 996.1 | 677.51 ± 104.29 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|