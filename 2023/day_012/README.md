# Day 12 benchmarks

[link to problem](https://adventofcode.com/2023/day/12)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 12)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [s] | Min [s] | Max [s] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 |
| lanjian | input-kcen | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.01 ± 0.08 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.003 | 1.33 ± 0.14 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.004 | 1.35 ± 0.16 |
| mattcl | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.003 | 1.36 ± 0.15 |
| mattcl | input-pting | 0.002 ± 0.000 | 0.002 | 0.004 | 1.38 ± 0.18 |
| pting | input-kcen | 0.067 ± 0.001 | 0.065 | 0.069 | 37.22 ± 2.34 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.066 | 0.071 | 37.72 ± 2.39 |
| pting | input-mattcl | 0.069 ± 0.001 | 0.067 | 0.073 | 38.05 ± 2.43 |
| pting | input-pting | 0.071 ± 0.004 | 0.068 | 0.083 | 39.63 ± 3.27 |
| mattcl-py | input-kcen | 0.090 ± 0.002 | 0.088 | 0.096 | 49.90 ± 3.21 |
| mattcl-py | input-mattcl | 0.092 ± 0.001 | 0.090 | 0.096 | 50.93 ± 3.23 |
| mattcl-py | input-lanjian | 0.093 ± 0.007 | 0.090 | 0.132 | 51.65 ± 5.13 |
| mattcl-py | input-pting | 0.094 ± 0.001 | 0.092 | 0.097 | 52.43 ± 3.30 |
| kcen | input-kcen | 1.272 ± 0.010 | 1.263 | 1.283 | 706.03 ± 43.71 |
| kcen | input-pting | 1.293 ± 0.004 | 1.290 | 1.297 | 717.35 ± 44.12 |
| kcen | input-mattcl | 1.409 ± 0.025 | 1.380 | 1.424 | 781.57 ± 49.97 |
| kcen | input-lanjian | 1.458 ± 0.018 | 1.438 | 1.471 | 808.92 ± 50.65 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|