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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.6 | 1.00 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.1 | 2.4 | 1.01 ± 0.20 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.4 | 1.01 ± 0.20 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.4 | 1.01 ± 0.21 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.5 | 5.1 | 2.83 ± 0.45 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 4.0 | 5.7 | 3.31 ± 0.51 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.4 | 5.5 | 3.52 ± 0.51 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 7.3 | 4.46 ± 0.65 |
| mattcl-py | input-kcen | 47.8 ± 0.5 | 46.4 | 49.3 | 33.66 ± 4.74 |
| mattcl-py | input-mikofo | 48.2 ± 0.7 | 47.1 | 51.6 | 33.92 ± 4.78 |
| mattcl-py | input-mattcl | 48.3 ± 0.5 | 46.7 | 49.5 | 33.97 ± 4.78 |
| mattcl-py | input-lanjian | 48.3 ± 0.9 | 47.0 | 51.6 | 33.98 ± 4.81 |
| kcen | input-mattcl | 174.1 ± 2.3 | 170.4 | 178.6 | 122.53 ± 17.26 |
| kcen | input-mikofo | 213.9 ± 1.7 | 211.3 | 217.0 | 150.49 ± 21.14 |
| kcen | input-kcen | 225.6 ± 2.6 | 220.2 | 229.6 | 158.76 ± 22.35 |
| kcen | input-lanjian | 367.0 ± 3.2 | 364.3 | 372.9 | 258.24 ± 36.30 |
| mikofo | input-mattcl | 517.6 ± 11.9 | 504.2 | 527.5 | 364.20 ± 51.77 |
| mikofo | input-mikofo | 582.9 ± 5.7 | 574.9 | 588.5 | 410.15 ± 57.67 |
| mikofo | input-kcen | 694.3 ± 12.7 | 679.9 | 709.8 | 488.54 ± 69.11 |
| mikofo | input-lanjian | 999.6 ± 6.3 | 995.5 | 1006.8 | 703.32 ± 98.76 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|