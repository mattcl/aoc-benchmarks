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
| mattcl | input-pting | 0.023 ± 0.000 | 0.022 | 0.025 | 1.00 |
| mattcl | input-mattcl | 0.023 ± 0.000 | 0.022 | 0.026 | 1.01 ± 0.03 |
| mattcl | input-lanjian | 0.023 ± 0.000 | 0.023 | 0.027 | 1.01 ± 0.03 |
| mattcl-py | input-lanjian | 0.382 ± 0.002 | 0.379 | 0.387 | 16.39 ± 0.27 |
| mattcl-py | input-mattcl | 0.384 ± 0.001 | 0.383 | 0.386 | 16.48 ± 0.26 |
| mattcl-py | input-pting | 0.393 ± 0.025 | 0.373 | 0.445 | 16.83 ± 1.09 |
| pting | input-mattcl | 1.871 ± 0.014 | 1.854 | 1.880 | 80.22 ± 1.38 |
| pting | input-pting | 1.893 ± 0.007 | 1.885 | 1.898 | 81.20 ± 1.29 |
| pting | input-lanjian | 1.901 ± 0.033 | 1.866 | 1.930 | 81.54 ± 1.89 |
| lanjian | input-mattcl | 2.362 ± 0.010 | 2.357 | 2.374 | 101.31 ± 1.62 |
| lanjian | input-pting | 2.365 ± 0.008 | 2.355 | 2.369 | 101.40 ± 1.60 |
| lanjian | input-lanjian | 2.401 ± 0.046 | 2.371 | 2.454 | 102.96 ± 2.53 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|