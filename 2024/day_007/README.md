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
| mattcl | input-kcen | 1.4 ± 0.1 | 1.0 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.5 | 1.01 ± 0.17 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.2 | 1.02 ± 0.17 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.1 | 2.6 | 1.02 ± 0.17 |
| lanjian | input-mattcl | 3.9 ± 0.2 | 3.5 | 5.0 | 2.75 ± 0.32 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 3.9 | 5.7 | 3.36 ± 0.41 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.6 | 5.7 | 3.56 ± 0.38 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 7.3 | 4.47 ± 0.48 |
| mattcl-py | input-kcen | 47.9 ± 0.6 | 46.5 | 49.5 | 34.02 ± 3.49 |
| mattcl-py | input-mattcl | 48.4 ± 0.7 | 47.2 | 51.0 | 34.38 ± 3.53 |
| mattcl-py | input-lanjian | 48.4 ± 0.6 | 47.4 | 50.3 | 34.39 ± 3.52 |
| mattcl-py | input-mikofo | 48.5 ± 0.7 | 47.1 | 50.7 | 34.43 ± 3.54 |
| kcen | input-mattcl | 173.0 ± 2.2 | 169.4 | 177.6 | 122.91 ± 12.59 |
| kcen | input-mikofo | 211.7 ± 1.9 | 209.6 | 216.6 | 150.43 ± 15.36 |
| kcen | input-kcen | 223.8 ± 2.5 | 219.8 | 228.0 | 159.02 ± 16.27 |
| kcen | input-lanjian | 364.4 ± 1.7 | 362.1 | 367.2 | 258.91 ± 26.36 |
| mikofo | input-mattcl | 522.9 ± 10.1 | 513.0 | 535.1 | 371.48 ± 38.45 |
| mikofo | input-mikofo | 589.8 ± 12.3 | 570.1 | 604.0 | 419.01 ± 43.50 |
| mikofo | input-kcen | 693.2 ± 8.9 | 681.8 | 703.3 | 492.49 ± 50.48 |
| mikofo | input-lanjian | 980.7 ± 3.2 | 977.2 | 983.6 | 696.74 ± 70.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|