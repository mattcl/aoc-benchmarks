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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.0 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.5 | 1.00 ± 0.18 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.4 | 1.01 ± 0.19 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.3 | 1.02 ± 0.18 |
| lanjian | input-mattcl | 3.9 ± 0.3 | 3.5 | 4.9 | 2.79 ± 0.39 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 3.9 | 5.5 | 3.37 ± 0.48 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.4 | 5.9 | 3.57 ± 0.47 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.7 | 7.1 | 4.49 ± 0.58 |
| mattcl-py | input-lanjian | 48.2 ± 0.5 | 47.2 | 49.6 | 34.40 ± 4.30 |
| mattcl-py | input-mikofo | 48.4 ± 0.7 | 47.2 | 51.0 | 34.48 ± 4.32 |
| mattcl-py | input-mattcl | 48.4 ± 0.8 | 46.8 | 50.8 | 34.50 ± 4.33 |
| mattcl-py | input-kcen | 48.4 ± 1.2 | 46.7 | 52.6 | 34.51 ± 4.39 |
| kcen | input-mattcl | 173.4 ± 2.2 | 170.0 | 176.3 | 123.64 ± 15.47 |
| kcen | input-mikofo | 214.8 ± 1.2 | 212.9 | 217.0 | 153.20 ± 19.09 |
| kcen | input-kcen | 227.7 ± 4.3 | 223.6 | 240.7 | 162.41 ± 20.45 |
| kcen | input-lanjian | 366.7 ± 2.0 | 364.0 | 370.7 | 261.54 ± 32.58 |
| mikofo | input-mattcl | 517.4 ± 15.9 | 490.6 | 530.8 | 369.02 ± 47.30 |
| mikofo | input-mikofo | 581.4 ± 5.6 | 574.7 | 590.0 | 414.65 ± 51.77 |
| mikofo | input-kcen | 693.0 ± 14.3 | 680.7 | 708.1 | 494.20 ± 62.36 |
| mikofo | input-lanjian | 992.2 ± 11.2 | 979.3 | 999.6 | 707.57 ± 88.43 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|