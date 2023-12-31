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
| mattcl | input-pting | 0.024 ± 0.000 | 0.023 | 0.025 | 1.00 |
| mattcl | input-mattcl | 0.024 ± 0.001 | 0.023 | 0.026 | 1.02 ± 0.03 |
| mattcl | input-lanjian | 0.024 ± 0.001 | 0.022 | 0.026 | 1.02 ± 0.03 |
| mattcl | input-kcen | 0.024 ± 0.001 | 0.022 | 0.027 | 1.03 ± 0.03 |
| mattcl-py | input-pting | 0.379 ± 0.002 | 0.377 | 0.382 | 16.08 ± 0.32 |
| mattcl-py | input-lanjian | 0.385 ± 0.004 | 0.379 | 0.390 | 16.32 ± 0.35 |
| mattcl-py | input-mattcl | 0.386 ± 0.004 | 0.381 | 0.391 | 16.36 ± 0.35 |
| mattcl-py | input-kcen | 0.391 ± 0.003 | 0.386 | 0.393 | 16.57 ± 0.34 |
| pting | input-kcen | 1.893 ± 0.010 | 1.883 | 1.904 | 80.24 ± 1.62 |
| pting | input-pting | 1.894 ± 0.016 | 1.878 | 1.910 | 80.29 ± 1.70 |
| pting | input-lanjian | 1.897 ± 0.010 | 1.890 | 1.909 | 80.43 ± 1.62 |
| pting | input-mattcl | 1.906 ± 0.007 | 1.899 | 1.913 | 80.81 ± 1.60 |
| lanjian | input-mattcl | 2.382 ± 0.032 | 2.347 | 2.409 | 100.99 ± 2.39 |
| lanjian | input-pting | 2.396 ± 0.007 | 2.392 | 2.403 | 101.56 ± 1.99 |
| lanjian | input-lanjian | 2.396 ± 0.023 | 2.370 | 2.413 | 101.57 ± 2.20 |
| lanjian | input-kcen | 2.420 ± 0.006 | 2.413 | 2.424 | 102.59 ± 2.01 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|