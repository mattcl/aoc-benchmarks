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
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 |
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| lanjian | input-kcen | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.09 |
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.09 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.004 | 1.33 ± 0.14 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.003 | 1.33 ± 0.12 |
| mattcl | input-pting | 0.002 ± 0.000 | 0.002 | 0.005 | 1.35 ± 0.16 |
| mattcl | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.005 | 1.36 ± 0.17 |
| pting | input-kcen | 0.067 ± 0.001 | 0.065 | 0.070 | 36.55 ± 1.96 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.066 | 0.072 | 37.41 ± 2.07 |
| pting | input-mattcl | 0.069 ± 0.002 | 0.067 | 0.074 | 37.64 ± 2.18 |
| pting | input-pting | 0.069 ± 0.001 | 0.068 | 0.073 | 37.94 ± 2.07 |
| mattcl-py | input-kcen | 0.090 ± 0.002 | 0.088 | 0.096 | 49.21 ± 2.74 |
| mattcl-py | input-lanjian | 0.091 ± 0.001 | 0.089 | 0.095 | 49.88 ± 2.71 |
| mattcl-py | input-mattcl | 0.091 ± 0.001 | 0.088 | 0.094 | 49.98 ± 2.70 |
| mattcl-py | input-pting | 0.094 ± 0.001 | 0.092 | 0.096 | 51.50 ± 2.72 |
| kcen | input-kcen | 1.256 ± 0.012 | 1.246 | 1.269 | 686.31 ± 36.15 |
| kcen | input-pting | 1.299 ± 0.045 | 1.266 | 1.350 | 709.54 ± 44.28 |
| kcen | input-mattcl | 1.396 ± 0.013 | 1.386 | 1.411 | 762.90 ± 40.21 |
| kcen | input-lanjian | 1.456 ± 0.008 | 1.450 | 1.465 | 795.56 ± 41.49 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|