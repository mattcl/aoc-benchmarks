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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 1.8 | 1.00 ± 0.16 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 1.9 | 1.01 ± 0.16 |
| lanjian | input-mattcl | 3.8 ± 0.2 | 3.5 | 4.6 | 2.75 ± 0.34 |
| lanjian | input-kcen | 5.0 ± 0.2 | 4.2 | 5.9 | 3.59 ± 0.45 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 7.3 | 4.51 ± 0.55 |
| mattcl-py | input-kcen | 48.0 ± 0.6 | 46.9 | 49.3 | 34.44 ± 4.03 |
| mattcl-py | input-mattcl | 48.3 ± 0.6 | 47.0 | 49.4 | 34.65 ± 4.06 |
| mattcl-py | input-lanjian | 48.4 ± 0.5 | 47.6 | 50.6 | 34.70 ± 4.06 |
| kcen | input-mattcl | 170.5 ± 1.6 | 167.9 | 173.5 | 122.30 ± 14.30 |
| kcen | input-kcen | 223.3 ± 1.9 | 218.8 | 225.8 | 160.13 ± 18.71 |
| kcen | input-lanjian | 360.4 ± 1.1 | 358.4 | 361.6 | 258.48 ± 30.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|