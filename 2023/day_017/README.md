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
| mattcl | input-lanjian | 0.024 ± 0.001 | 0.022 | 0.026 | 1.00 ± 0.04 |
| mattcl | input-mattcl | 0.024 ± 0.003 | 0.023 | 0.057 | 1.02 ± 0.13 |
| mattcl-py | input-pting | 0.382 ± 0.005 | 0.374 | 0.387 | 16.02 ± 0.49 |
| mattcl-py | input-mattcl | 0.385 ± 0.004 | 0.379 | 0.391 | 16.15 ± 0.49 |
| mattcl-py | input-lanjian | 0.387 ± 0.004 | 0.383 | 0.392 | 16.23 ± 0.48 |
| pting | input-mattcl | 1.883 ± 0.014 | 1.866 | 1.894 | 78.98 ± 2.30 |
| pting | input-lanjian | 1.908 ± 0.033 | 1.879 | 1.944 | 80.05 ± 2.63 |
| pting | input-pting | 1.912 ± 0.006 | 1.905 | 1.917 | 80.21 ± 2.27 |
| lanjian | input-pting | 2.389 ± 0.016 | 2.371 | 2.401 | 100.23 ± 2.89 |
| lanjian | input-lanjian | 2.398 ± 0.036 | 2.356 | 2.424 | 100.58 ± 3.21 |
| lanjian | input-mattcl | 2.399 ± 0.003 | 2.396 | 2.401 | 100.61 ± 2.83 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|