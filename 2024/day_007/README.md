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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.8 | 1.00 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.0 | 2.6 | 1.01 ± 0.21 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.0 | 2.5 | 1.01 ± 0.23 |
| lanjian | input-mattcl | 3.9 ± 0.1 | 3.6 | 4.5 | 2.67 ± 0.46 |
| lanjian | input-kcen | 5.1 ± 0.3 | 4.4 | 7.5 | 3.52 ± 0.63 |
| lanjian | input-lanjian | 6.3 ± 0.2 | 5.8 | 7.0 | 4.34 ± 0.75 |
| mattcl-py | input-mattcl | 168.5 ± 7.4 | 158.3 | 179.1 | 116.26 ± 20.22 |
| kcen | input-mattcl | 170.6 ± 1.8 | 166.7 | 173.5 | 117.72 ± 19.86 |
| mattcl-py | input-kcen | 194.4 ± 3.2 | 188.5 | 199.4 | 134.10 ± 22.69 |
| kcen | input-kcen | 219.4 ± 2.1 | 216.5 | 223.9 | 151.37 ± 25.53 |
| mattcl-py | input-lanjian | 272.3 ± 6.4 | 258.4 | 279.7 | 187.84 ± 31.93 |
| kcen | input-lanjian | 356.9 ± 1.8 | 354.9 | 360.1 | 246.23 ± 41.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>850435817339</pre>|<pre>104824810233437</pre>|
|input-lanjian|<pre>4364915411363</pre>|<pre>38322057216320</pre>|
|input-mattcl|<pre>2299996598890</pre>|<pre>362646859298554</pre>|