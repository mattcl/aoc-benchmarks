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
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.2 | 1.00 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.6 | 1.00 ± 0.18 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.1 | 2.4 | 1.01 ± 0.17 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.5 | 1.01 ± 0.16 |
| lanjian | input-mattcl | 3.9 ± 0.3 | 3.5 | 4.9 | 2.79 ± 0.36 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 3.9 | 6.8 | 3.35 ± 0.44 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.5 | 5.8 | 3.56 ± 0.41 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.9 | 7.3 | 4.48 ± 0.52 |
| mattcl-py | input-kcen | 47.4 ± 0.5 | 46.5 | 48.6 | 33.73 ± 3.74 |
| mattcl-py | input-mikofo | 47.6 ± 0.5 | 46.3 | 48.5 | 33.84 ± 3.75 |
| mattcl-py | input-lanjian | 47.8 ± 0.6 | 46.4 | 49.3 | 33.96 ± 3.78 |
| mattcl-py | input-mattcl | 47.8 ± 0.7 | 46.4 | 50.2 | 34.00 ± 3.79 |
| kcen | input-mattcl | 175.8 ± 1.8 | 171.4 | 178.7 | 125.00 ± 13.87 |
| kcen | input-mikofo | 215.0 ± 3.1 | 210.6 | 220.6 | 152.85 ± 17.03 |
| kcen | input-kcen | 226.6 ± 2.1 | 222.4 | 229.4 | 161.10 ± 17.87 |
| kcen | input-lanjian | 368.3 ± 3.3 | 362.8 | 372.5 | 261.84 ± 29.03 |
| mikofo | input-mattcl | 520.7 ± 16.5 | 492.1 | 534.6 | 370.23 ± 42.57 |
| mikofo | input-mikofo | 572.5 ± 15.5 | 554.1 | 591.1 | 407.09 ± 46.33 |
| mikofo | input-kcen | 692.5 ± 5.4 | 687.5 | 700.0 | 492.40 ± 54.55 |
| mikofo | input-lanjian | 986.8 ± 10.3 | 976.8 | 997.4 | 701.68 ± 77.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|