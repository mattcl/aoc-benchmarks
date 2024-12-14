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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.1 | 2.1 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.6 | 1.01 ± 0.18 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.1 | 2.5 | 1.01 ± 0.17 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.1 | 2.2 | 1.02 ± 0.17 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.5 | 5.2 | 2.82 ± 0.39 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 3.9 | 5.5 | 3.31 ± 0.43 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.6 | 5.6 | 3.54 ± 0.43 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 7.3 | 4.43 ± 0.54 |
| mattcl-py | input-mikofo | 47.4 ± 0.6 | 45.9 | 48.5 | 33.25 ± 3.88 |
| mattcl-py | input-kcen | 47.4 ± 0.7 | 46.2 | 50.4 | 33.26 ± 3.89 |
| mattcl-py | input-mattcl | 47.6 ± 0.5 | 46.6 | 48.7 | 33.37 ± 3.89 |
| mattcl-py | input-lanjian | 47.8 ± 0.6 | 46.6 | 49.6 | 33.52 ± 3.91 |
| kcen | input-mattcl | 177.6 ± 1.4 | 175.2 | 180.3 | 124.48 ± 14.47 |
| kcen | input-mikofo | 214.4 ± 2.7 | 211.3 | 220.2 | 150.25 ± 17.53 |
| kcen | input-kcen | 226.3 ± 2.0 | 223.6 | 229.2 | 158.62 ± 18.46 |
| kcen | input-lanjian | 369.6 ± 4.0 | 364.1 | 375.4 | 259.09 ± 30.19 |
| mikofo | input-mattcl | 524.9 ± 13.3 | 509.7 | 540.8 | 367.88 ± 43.68 |
| mikofo | input-mikofo | 571.2 ± 18.1 | 549.6 | 594.4 | 400.38 ± 48.15 |
| mikofo | input-kcen | 683.1 ± 7.8 | 674.8 | 692.3 | 478.83 ± 55.82 |
| mikofo | input-lanjian | 995.6 ± 3.4 | 992.1 | 999.0 | 697.81 ± 80.99 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|