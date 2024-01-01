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
| mattcl | input-pting | 0.024 ± 0.001 | 0.023 | 0.026 | 1.00 |
| mattcl | input-lanjian | 0.024 ± 0.001 | 0.023 | 0.027 | 1.01 ± 0.04 |
| mattcl | input-mattcl | 0.024 ± 0.001 | 0.023 | 0.026 | 1.01 ± 0.04 |
| mattcl | input-kcen | 0.024 ± 0.001 | 0.023 | 0.028 | 1.02 ± 0.04 |
| mattcl-py | input-pting | 0.381 ± 0.006 | 0.369 | 0.386 | 15.90 ± 0.48 |
| mattcl-py | input-mattcl | 0.382 ± 0.004 | 0.376 | 0.388 | 15.93 ± 0.46 |
| mattcl-py | input-lanjian | 0.385 ± 0.007 | 0.380 | 0.396 | 16.07 ± 0.50 |
| mattcl-py | input-kcen | 0.389 ± 0.006 | 0.377 | 0.393 | 16.22 ± 0.48 |
| pting | input-mattcl | 1.876 ± 0.034 | 1.840 | 1.907 | 78.30 ± 2.48 |
| pting | input-kcen | 1.884 ± 0.007 | 1.876 | 1.889 | 78.64 ± 2.07 |
| pting | input-lanjian | 1.900 ± 0.033 | 1.869 | 1.935 | 79.31 ± 2.49 |
| pting | input-pting | 1.931 ± 0.013 | 1.917 | 1.943 | 80.60 ± 2.17 |
| lanjian | input-pting | 2.369 ± 0.028 | 2.350 | 2.401 | 98.87 ± 2.83 |
| lanjian | input-mattcl | 2.375 ± 0.025 | 2.346 | 2.394 | 99.11 ± 2.79 |
| lanjian | input-lanjian | 2.396 ± 0.032 | 2.361 | 2.426 | 100.00 ± 2.94 |
| lanjian | input-kcen | 2.428 ± 0.006 | 2.422 | 2.434 | 101.35 ± 2.65 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|