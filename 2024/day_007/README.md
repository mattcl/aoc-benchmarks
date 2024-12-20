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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.1 | 2.4 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.1 | 2.2 | 1.00 ± 0.17 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.0 | 2.2 | 1.01 ± 0.18 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.0 | 2.7 | 1.02 ± 0.20 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.6 | 5.1 | 2.78 ± 0.39 |
| lanjian | input-mikofo | 4.7 ± 0.4 | 3.9 | 6.0 | 3.28 ± 0.46 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.5 | 5.8 | 3.50 ± 0.44 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.9 | 7.1 | 4.41 ± 0.54 |
| mattcl-py | input-kcen | 48.2 ± 0.6 | 47.0 | 51.0 | 33.56 ± 3.98 |
| mattcl-py | input-mattcl | 48.4 ± 0.6 | 47.2 | 50.3 | 33.71 ± 3.99 |
| mattcl-py | input-lanjian | 48.5 ± 0.8 | 47.1 | 51.4 | 33.83 ± 4.02 |
| mattcl-py | input-mikofo | 48.6 ± 0.6 | 47.3 | 50.3 | 33.85 ± 4.01 |
| kcen | input-mattcl | 175.4 ± 1.5 | 172.3 | 177.7 | 122.23 ± 14.44 |
| kcen | input-mikofo | 214.5 ± 1.9 | 211.8 | 217.8 | 149.50 ± 17.67 |
| kcen | input-kcen | 225.9 ± 3.6 | 221.8 | 231.8 | 157.42 ± 18.72 |
| kcen | input-lanjian | 365.4 ± 2.9 | 360.4 | 369.4 | 254.70 ± 30.09 |
| mikofo | input-mattcl | 528.0 ± 16.3 | 512.4 | 553.3 | 368.01 ± 44.85 |
| mikofo | input-mikofo | 579.6 ± 13.4 | 566.8 | 599.1 | 403.94 ± 48.52 |
| mikofo | input-kcen | 709.7 ± 8.3 | 697.9 | 716.1 | 494.67 ± 58.59 |
| mikofo | input-lanjian | 995.4 ± 10.8 | 985.7 | 1007.0 | 693.77 ± 82.12 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|