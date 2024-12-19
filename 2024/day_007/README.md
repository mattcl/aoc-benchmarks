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
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.1 | 2.5 | 1.00 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 1.0 | 2.5 | 1.00 ± 0.21 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.0 | 2.6 | 1.02 ± 0.20 |
| mattcl | input-kcen | 1.5 ± 0.2 | 1.0 | 2.7 | 1.02 ± 0.22 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.5 | 5.3 | 2.80 ± 0.47 |
| lanjian | input-mikofo | 4.7 ± 0.3 | 3.8 | 5.7 | 3.31 ± 0.52 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.3 | 6.1 | 3.51 ± 0.53 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 7.0 | 4.42 ± 0.66 |
| mattcl-py | input-kcen | 48.1 ± 1.0 | 46.7 | 54.0 | 33.65 ± 4.96 |
| mattcl-py | input-lanjian | 48.3 ± 0.6 | 46.8 | 49.8 | 33.79 ± 4.95 |
| mattcl-py | input-mattcl | 48.4 ± 0.8 | 47.1 | 51.6 | 33.85 ± 4.98 |
| mattcl-py | input-mikofo | 48.4 ± 0.7 | 47.2 | 50.8 | 33.87 ± 4.97 |
| kcen | input-mattcl | 175.1 ± 1.3 | 173.0 | 177.6 | 122.47 ± 17.90 |
| kcen | input-mikofo | 214.7 ± 1.7 | 211.4 | 216.8 | 150.19 ± 21.96 |
| kcen | input-kcen | 227.5 ± 1.3 | 225.1 | 229.4 | 159.12 ± 23.25 |
| kcen | input-lanjian | 367.1 ± 2.6 | 362.5 | 371.5 | 256.76 ± 37.53 |
| mikofo | input-mattcl | 523.2 ± 17.2 | 503.5 | 547.1 | 366.01 ± 54.78 |
| mikofo | input-mikofo | 578.1 ± 8.5 | 566.5 | 586.5 | 404.37 ± 59.34 |
| mikofo | input-kcen | 686.6 ± 8.6 | 679.7 | 698.5 | 480.31 ± 70.38 |
| mikofo | input-lanjian | 1002.3 ± 6.1 | 995.6 | 1007.5 | 701.12 ± 102.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|
|input-mikofo|<pre>1153997401072</pre>|<pre>97902809384118</pre>|