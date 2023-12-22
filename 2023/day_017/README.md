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
| mattcl | input-pting | 0.024 ± 0.001 | 0.022 | 0.027 | 1.00 |
| mattcl | input-lanjian | 0.024 ± 0.001 | 0.023 | 0.026 | 1.01 ± 0.04 |
| mattcl | input-mattcl | 0.024 ± 0.001 | 0.023 | 0.027 | 1.01 ± 0.04 |
| mattcl-py | input-pting | 0.379 ± 0.004 | 0.372 | 0.384 | 15.93 ± 0.49 |
| mattcl-py | input-mattcl | 0.384 ± 0.003 | 0.379 | 0.388 | 16.14 ± 0.48 |
| mattcl-py | input-lanjian | 0.387 ± 0.007 | 0.375 | 0.396 | 16.26 ± 0.56 |
| pting | input-mattcl | 1.866 ± 0.006 | 1.859 | 1.872 | 78.38 ± 2.27 |
| pting | input-lanjian | 1.895 ± 0.033 | 1.859 | 1.924 | 79.63 ± 2.68 |
| pting | input-pting | 1.943 ± 0.028 | 1.920 | 1.974 | 81.64 ± 2.62 |
| lanjian | input-mattcl | 2.375 ± 0.023 | 2.348 | 2.393 | 99.77 ± 3.03 |
| lanjian | input-lanjian | 2.387 ± 0.026 | 2.357 | 2.405 | 100.28 ± 3.09 |
| lanjian | input-pting | 2.399 ± 0.007 | 2.391 | 2.405 | 100.80 ± 2.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|