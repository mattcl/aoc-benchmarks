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
| mattcl | input-lanjian | 0.024 ± 0.001 | 0.023 | 0.027 | 1.00 |
| mattcl | input-mattcl | 0.024 ± 0.001 | 0.023 | 0.027 | 1.00 ± 0.04 |
| mattcl | input-pting | 0.024 ± 0.003 | 0.023 | 0.045 | 1.01 ± 0.12 |
| mattcl-py | input-pting | 0.380 ± 0.005 | 0.373 | 0.389 | 15.77 ± 0.43 |
| mattcl-py | input-mattcl | 0.385 ± 0.004 | 0.379 | 0.389 | 15.98 ± 0.41 |
| mattcl-py | input-lanjian | 0.387 ± 0.005 | 0.379 | 0.392 | 16.06 ± 0.43 |
| pting | input-lanjian | 1.867 ± 0.022 | 1.842 | 1.882 | 77.55 ± 2.06 |
| pting | input-mattcl | 1.897 ± 0.044 | 1.858 | 1.945 | 78.79 ± 2.63 |
| pting | input-pting | 1.930 ± 0.002 | 1.929 | 1.932 | 80.18 ± 1.91 |
| lanjian | input-mattcl | 2.367 ± 0.038 | 2.334 | 2.409 | 98.32 ± 2.82 |
| lanjian | input-pting | 2.369 ± 0.024 | 2.353 | 2.397 | 98.40 ± 2.55 |
| lanjian | input-lanjian | 2.419 ± 0.052 | 2.376 | 2.477 | 100.47 ± 3.22 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|