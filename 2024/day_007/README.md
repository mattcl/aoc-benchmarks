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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.2 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.1 | 1.1 | 1.9 | 1.00 ± 0.17 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.4 | 1.01 ± 0.19 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.1 | 2.4 | 1.02 ± 0.19 |
| lanjian | input-mattcl | 4.1 ± 0.3 | 3.5 | 5.0 | 2.89 ± 0.45 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 4.0 | 5.7 | 3.35 ± 0.49 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.3 | 5.5 | 3.56 ± 0.49 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 7.1 | 4.47 ± 0.62 |
| mattcl-py | input-kcen | 48.1 ± 0.8 | 46.4 | 52.0 | 34.09 ± 4.60 |
| mattcl-py | input-mattcl | 48.3 ± 0.8 | 46.8 | 50.2 | 34.26 ± 4.63 |
| mattcl-py | input-lanjian | 48.4 ± 1.1 | 46.8 | 55.1 | 34.34 ± 4.67 |
| mattcl-py | input-mikofo | 48.7 ± 0.7 | 47.7 | 50.7 | 34.57 ± 4.66 |
| kcen | input-mattcl | 174.2 ± 1.9 | 171.4 | 179.1 | 123.56 ± 16.62 |
| kcen | input-mikofo | 213.0 ± 1.4 | 210.7 | 216.1 | 151.09 ± 20.28 |
| kcen | input-kcen | 225.2 ± 2.7 | 221.3 | 228.9 | 159.71 ± 21.49 |
| kcen | input-lanjian | 362.7 ± 3.4 | 357.8 | 365.7 | 257.24 ± 34.57 |
| mikofo | input-mattcl | 529.0 ± 18.3 | 507.5 | 551.5 | 375.20 ± 51.95 |
| mikofo | input-mikofo | 581.9 ± 15.4 | 560.8 | 603.6 | 412.68 ± 56.39 |
| mikofo | input-kcen | 697.0 ± 5.6 | 689.2 | 702.3 | 494.31 ± 66.38 |
| mikofo | input-lanjian | 1001.6 ± 6.3 | 994.3 | 1005.6 | 710.31 ± 95.33 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|