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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.5 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.2 | 1.01 ± 0.16 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.6 | 1.01 ± 0.19 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.6 | 1.01 ± 0.18 |
| lanjian | input-mattcl | 4.0 ± 0.2 | 3.6 | 4.9 | 2.79 ± 0.37 |
| lanjian | input-mikofo | 4.6 ± 0.3 | 3.8 | 5.6 | 3.27 ± 0.45 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.3 | 5.7 | 3.53 ± 0.45 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.7 | 7.1 | 4.42 ± 0.54 |
| mattcl-py | input-kcen | 47.3 ± 0.5 | 46.3 | 48.6 | 33.37 ± 3.95 |
| mattcl-py | input-mikofo | 47.9 ± 0.6 | 46.4 | 50.0 | 33.75 ± 4.00 |
| mattcl-py | input-lanjian | 48.1 ± 0.7 | 46.4 | 50.2 | 33.88 ± 4.03 |
| mattcl-py | input-mattcl | 48.1 ± 0.7 | 46.5 | 51.4 | 33.90 ± 4.03 |
| kcen | input-mattcl | 174.0 ± 2.0 | 170.5 | 177.5 | 122.66 ± 14.54 |
| kcen | input-mikofo | 211.3 ± 2.3 | 207.8 | 216.4 | 148.93 ± 17.64 |
| kcen | input-kcen | 223.8 ± 2.9 | 218.5 | 228.6 | 157.75 ± 18.72 |
| kcen | input-lanjian | 363.9 ± 3.4 | 358.1 | 367.5 | 256.48 ± 30.35 |
| mikofo | input-mattcl | 518.0 ± 13.2 | 502.9 | 535.8 | 365.09 ± 44.05 |
| mikofo | input-mikofo | 574.5 ± 14.7 | 558.3 | 591.3 | 404.92 ± 48.87 |
| mikofo | input-kcen | 692.2 ± 8.4 | 685.9 | 703.8 | 487.89 ± 57.85 |
| mikofo | input-lanjian | 988.2 ± 8.9 | 979.8 | 997.5 | 696.52 ± 82.40 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|