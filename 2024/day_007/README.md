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
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.1 | 2.7 | 1.00 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.1 | 2.2 | 1.00 ± 0.18 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.1 | 2.5 | 1.01 ± 0.18 |
| mattcl | input-kcen | 1.5 ± 0.2 | 1.0 | 2.6 | 1.02 ± 0.20 |
| lanjian | input-mattcl | 4.1 ± 0.3 | 3.6 | 5.4 | 2.81 ± 0.40 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 4.0 | 6.5 | 3.27 ± 0.46 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.4 | 5.9 | 3.46 ± 0.45 |
| lanjian | input-lanjian | 6.4 ± 0.2 | 5.9 | 7.1 | 4.41 ± 0.56 |
| mattcl-py | input-kcen | 47.7 ± 0.8 | 46.5 | 51.7 | 33.01 ± 4.06 |
| mattcl-py | input-mattcl | 47.8 ± 0.6 | 46.4 | 49.9 | 33.07 ± 4.05 |
| mattcl-py | input-mikofo | 47.8 ± 0.7 | 46.5 | 50.4 | 33.10 ± 4.06 |
| mattcl-py | input-lanjian | 48.0 ± 0.5 | 46.5 | 49.1 | 33.23 ± 4.06 |
| kcen | input-mattcl | 177.7 ± 2.0 | 174.2 | 181.0 | 123.01 ± 15.05 |
| kcen | input-mikofo | 217.4 ± 2.3 | 214.0 | 219.9 | 150.51 ± 18.40 |
| kcen | input-kcen | 228.6 ± 2.7 | 224.7 | 232.0 | 158.26 ± 19.37 |
| kcen | input-lanjian | 372.9 ± 5.4 | 368.3 | 382.2 | 258.20 ± 31.66 |
| mikofo | input-mattcl | 528.7 ± 20.8 | 494.3 | 542.8 | 366.02 ± 46.84 |
| mikofo | input-mikofo | 571.5 ± 10.8 | 558.3 | 581.9 | 395.64 ± 48.76 |
| mikofo | input-kcen | 695.8 ± 22.4 | 674.2 | 724.9 | 481.74 ± 60.68 |
| mikofo | input-lanjian | 977.8 ± 3.3 | 974.9 | 981.4 | 676.99 ± 82.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|