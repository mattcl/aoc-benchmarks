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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.3 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.0 | 1.00 ± 0.18 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.3 | 1.01 ± 0.17 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.1 | 2.4 | 1.02 ± 0.17 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.5 | 5.1 | 2.87 ± 0.42 |
| lanjian | input-mikofo | 4.6 ± 0.3 | 3.9 | 5.6 | 3.29 ± 0.45 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.5 | 5.7 | 3.56 ± 0.45 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 7.2 | 4.45 ± 0.56 |
| mattcl-py | input-kcen | 47.9 ± 0.6 | 46.9 | 49.2 | 34.04 ± 4.12 |
| mattcl-py | input-mattcl | 48.4 ± 0.6 | 46.8 | 49.6 | 34.37 ± 4.17 |
| mattcl-py | input-lanjian | 48.5 ± 0.8 | 46.6 | 51.9 | 34.44 ± 4.19 |
| mattcl-py | input-mikofo | 48.6 ± 0.8 | 47.4 | 51.2 | 34.50 ± 4.20 |
| kcen | input-mattcl | 172.6 ± 1.5 | 168.7 | 175.4 | 122.66 ± 14.82 |
| kcen | input-mikofo | 211.9 ± 1.6 | 208.7 | 214.7 | 150.61 ± 18.19 |
| kcen | input-kcen | 224.5 ± 3.2 | 218.2 | 228.5 | 159.53 ± 19.36 |
| kcen | input-lanjian | 360.3 ± 4.0 | 354.6 | 365.3 | 256.02 ± 30.99 |
| mikofo | input-mattcl | 519.7 ± 18.1 | 492.9 | 541.7 | 369.28 ± 46.33 |
| mikofo | input-mikofo | 583.8 ± 5.4 | 575.6 | 590.5 | 414.85 ± 50.15 |
| mikofo | input-kcen | 691.4 ± 14.4 | 673.5 | 703.2 | 491.30 ± 60.09 |
| mikofo | input-lanjian | 996.9 ± 32.3 | 960.9 | 1023.3 | 708.38 ± 88.40 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|