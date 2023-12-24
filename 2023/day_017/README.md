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
| mattcl | input-mattcl | 0.024 ± 0.001 | 0.023 | 0.026 | 1.01 ± 0.04 |
| mattcl | input-lanjian | 0.024 ± 0.001 | 0.023 | 0.027 | 1.01 ± 0.04 |
| mattcl-py | input-lanjian | 0.381 ± 0.004 | 0.374 | 0.385 | 15.98 ± 0.44 |
| mattcl-py | input-pting | 0.382 ± 0.004 | 0.376 | 0.388 | 16.03 ± 0.45 |
| mattcl-py | input-mattcl | 0.383 ± 0.005 | 0.379 | 0.391 | 16.07 ± 0.46 |
| pting | input-mattcl | 1.866 ± 0.016 | 1.850 | 1.881 | 78.26 ± 2.11 |
| pting | input-lanjian | 1.884 ± 0.022 | 1.860 | 1.901 | 79.00 ± 2.21 |
| pting | input-pting | 1.885 ± 0.017 | 1.867 | 1.901 | 79.03 ± 2.15 |
| lanjian | input-mattcl | 2.337 ± 0.004 | 2.333 | 2.341 | 98.01 ± 2.51 |
| lanjian | input-lanjian | 2.379 ± 0.024 | 2.352 | 2.396 | 99.76 ± 2.74 |
| lanjian | input-pting | 2.401 ± 0.006 | 2.397 | 2.408 | 100.69 ± 2.59 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|