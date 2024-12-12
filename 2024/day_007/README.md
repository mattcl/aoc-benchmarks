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
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.6 | 1.00 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.0 | 2.1 | 1.00 ± 0.18 |
| mattcl | input-kcen | 1.5 ± 0.2 | 1.0 | 2.5 | 1.01 ± 0.19 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.0 | 2.2 | 1.02 ± 0.18 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.5 | 5.3 | 2.76 ± 0.41 |
| lanjian | input-mikofo | 4.8 ± 0.3 | 4.0 | 5.5 | 3.31 ± 0.48 |
| lanjian | input-kcen | 5.1 ± 0.2 | 4.5 | 5.9 | 3.50 ± 0.48 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.7 | 7.1 | 4.39 ± 0.60 |
| mattcl-py | input-kcen | 47.4 ± 0.6 | 46.4 | 49.2 | 32.84 ± 4.33 |
| mattcl-py | input-mikofo | 47.8 ± 0.6 | 46.7 | 50.4 | 33.07 ± 4.36 |
| mattcl-py | input-mattcl | 47.8 ± 0.4 | 46.9 | 49.2 | 33.07 ± 4.35 |
| mattcl-py | input-lanjian | 48.1 ± 0.7 | 46.8 | 50.7 | 33.29 ± 4.40 |
| kcen | input-mattcl | 175.4 ± 3.9 | 170.4 | 186.4 | 121.40 ± 16.17 |
| kcen | input-mikofo | 214.4 ± 2.4 | 210.3 | 218.6 | 148.39 ± 19.56 |
| kcen | input-kcen | 223.5 ± 2.1 | 220.8 | 226.6 | 154.72 ± 20.37 |
| kcen | input-lanjian | 358.4 ± 1.5 | 355.6 | 359.9 | 248.08 ± 32.60 |
| mikofo | input-mattcl | 530.0 ± 9.6 | 523.1 | 546.7 | 366.87 ± 48.65 |
| mikofo | input-mikofo | 568.2 ± 7.4 | 557.4 | 575.6 | 393.31 ± 51.91 |
| mikofo | input-kcen | 691.7 ± 9.3 | 679.5 | 699.2 | 478.84 ± 63.22 |
| mikofo | input-lanjian | 984.9 ± 7.1 | 977.8 | 992.0 | 681.77 ± 89.68 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|