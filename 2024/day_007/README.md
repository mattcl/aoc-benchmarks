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


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.5 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.3 | 1.01 ± 0.17 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.0 | 2.0 | 1.03 ± 0.18 |
| lanjian | input-mattcl | 3.9 ± 0.2 | 3.5 | 4.6 | 2.74 ± 0.39 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.7 | 5.7 | 3.55 ± 0.48 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 7.1 | 4.43 ± 0.61 |
| mattcl-py | input-kcen | 47.0 ± 0.5 | 45.9 | 48.3 | 33.11 ± 4.38 |
| mattcl-py | input-lanjian | 47.4 ± 0.6 | 46.2 | 48.8 | 33.40 ± 4.43 |
| mattcl-py | input-mattcl | 47.4 ± 0.8 | 45.9 | 51.9 | 33.42 ± 4.45 |
| kcen | input-mattcl | 169.7 ± 1.3 | 167.1 | 171.8 | 119.54 ± 15.81 |
| kcen | input-kcen | 220.0 ± 1.1 | 218.5 | 222.6 | 155.02 ± 20.48 |
| kcen | input-lanjian | 355.3 ± 1.6 | 353.0 | 358.0 | 250.32 ± 33.06 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|