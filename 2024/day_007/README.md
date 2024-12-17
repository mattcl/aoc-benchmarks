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
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.1 | 1.9 | 1.00 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.1 | 2.3 | 1.01 ± 0.16 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.1 | 2.3 | 1.01 ± 0.17 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.0 | 2.5 | 1.01 ± 0.17 |
| lanjian | input-mattcl | 3.9 ± 0.2 | 3.5 | 4.8 | 2.71 ± 0.32 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 4.0 | 5.8 | 3.27 ± 0.42 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.2 | 5.7 | 3.50 ± 0.42 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.7 | 7.3 | 4.42 ± 0.52 |
| mattcl-py | input-kcen | 48.1 ± 0.6 | 46.4 | 49.6 | 33.46 ± 3.71 |
| mattcl-py | input-mattcl | 48.4 ± 0.8 | 46.9 | 51.9 | 33.70 ± 3.75 |
| mattcl-py | input-lanjian | 48.6 ± 0.7 | 47.2 | 50.8 | 33.83 ± 3.76 |
| mattcl-py | input-mikofo | 48.7 ± 0.7 | 47.2 | 51.7 | 33.89 ± 3.77 |
| kcen | input-mattcl | 175.0 ± 1.5 | 172.1 | 178.8 | 121.78 ± 13.46 |
| kcen | input-mikofo | 213.3 ± 1.8 | 209.8 | 215.9 | 148.48 ± 16.41 |
| kcen | input-kcen | 226.9 ± 3.2 | 221.6 | 233.9 | 157.92 ± 17.55 |
| kcen | input-lanjian | 367.3 ± 4.1 | 359.7 | 374.4 | 255.69 ± 28.33 |
| mikofo | input-mattcl | 528.7 ± 11.6 | 510.4 | 542.5 | 368.03 ± 41.37 |
| mikofo | input-mikofo | 582.1 ± 8.6 | 567.9 | 590.3 | 405.15 ± 45.06 |
| mikofo | input-kcen | 705.0 ± 8.9 | 696.5 | 717.1 | 490.75 ± 54.45 |
| mikofo | input-lanjian | 1000.9 ± 18.3 | 979.9 | 1012.0 | 696.72 ± 77.85 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|