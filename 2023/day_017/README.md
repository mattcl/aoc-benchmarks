# Day 17 benchmarks

[link to problem](https://adventofcode.com/2023/day/17)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 17)

- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [s] | Min [s] | Max [s] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-pting | 0.024 ± 0.001 | 0.023 | 0.027 | 1.00 |
| mattcl | input-lanjian | 0.024 ± 0.001 | 0.023 | 0.027 | 1.01 ± 0.03 |
| mattcl | input-mattcl | 0.024 ± 0.001 | 0.023 | 0.027 | 1.01 ± 0.04 |
| mattcl-py | input-pting | 0.381 ± 0.005 | 0.374 | 0.386 | 15.97 ± 0.43 |
| mattcl-py | input-mattcl | 0.383 ± 0.003 | 0.378 | 0.387 | 16.08 ± 0.41 |
| mattcl-py | input-lanjian | 0.384 ± 0.004 | 0.379 | 0.391 | 16.14 ± 0.43 |
| pting | input-lanjian | 1.902 ± 0.043 | 1.861 | 1.948 | 79.81 ± 2.66 |
| pting | input-pting | 1.902 ± 0.014 | 1.891 | 1.919 | 79.84 ± 2.04 |
| pting | input-mattcl | 2.099 ± 0.350 | 1.880 | 2.502 | 88.08 ± 14.84 |
| lanjian | input-mattcl | 2.370 ± 0.030 | 2.336 | 2.393 | 99.47 ± 2.73 |
| lanjian | input-pting | 2.382 ± 0.027 | 2.351 | 2.401 | 99.95 ± 2.69 |
| lanjian | input-lanjian | 2.405 ± 0.003 | 2.402 | 2.408 | 100.95 ± 2.46 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|