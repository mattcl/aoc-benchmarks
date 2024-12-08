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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.0 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.5 | 1.02 ± 0.18 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.1 | 2.7 | 1.03 ± 0.19 |
| lanjian | input-mattcl | 4.0 ± 0.3 | 3.6 | 5.2 | 2.80 ± 0.37 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.5 | 5.6 | 3.54 ± 0.41 |
| lanjian | input-lanjian | 6.3 ± 0.3 | 5.7 | 8.2 | 4.45 ± 0.53 |
| mattcl-py | input-kcen | 47.8 ± 0.6 | 46.3 | 49.2 | 33.74 ± 3.69 |
| mattcl-py | input-mattcl | 48.3 ± 0.7 | 47.1 | 50.6 | 34.07 ± 3.73 |
| mattcl-py | input-lanjian | 49.9 ± 1.5 | 47.2 | 52.9 | 35.17 ± 3.96 |
| kcen | input-mattcl | 169.6 ± 2.1 | 166.7 | 173.6 | 119.58 ± 13.07 |
| kcen | input-kcen | 220.8 ± 2.5 | 215.9 | 224.5 | 155.74 ± 17.00 |
| kcen | input-lanjian | 358.3 ± 2.3 | 354.2 | 362.1 | 252.73 ± 27.49 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|