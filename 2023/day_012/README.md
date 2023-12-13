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
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 |
| lanjian | input-kcen | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.12 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.11 |
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.12 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.004 | 1.31 ± 0.16 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.004 | 1.32 ± 0.17 |
| mattcl | input-pting | 0.002 ± 0.000 | 0.002 | 0.003 | 1.33 ± 0.15 |
| mattcl | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.005 | 1.33 ± 0.18 |
| pting | input-kcen | 0.067 ± 0.001 | 0.065 | 0.069 | 36.05 ± 3.19 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.066 | 0.071 | 36.58 ± 3.21 |
| pting | input-mattcl | 0.068 ± 0.001 | 0.066 | 0.070 | 36.60 ± 3.21 |
| pting | input-pting | 0.069 ± 0.001 | 0.067 | 0.072 | 37.35 ± 3.29 |
| mattcl-py | input-kcen | 0.089 ± 0.001 | 0.086 | 0.093 | 48.21 ± 4.25 |
| mattcl-py | input-lanjian | 0.091 ± 0.001 | 0.088 | 0.093 | 49.01 ± 4.28 |
| mattcl-py | input-mattcl | 0.091 ± 0.001 | 0.089 | 0.094 | 49.07 ± 4.29 |
| mattcl-py | input-pting | 0.094 ± 0.001 | 0.092 | 0.096 | 50.65 ± 4.44 |
| kcen | input-kcen | 1.265 ± 0.011 | 1.253 | 1.276 | 684.22 ± 59.56 |
| kcen | input-pting | 1.294 ± 0.026 | 1.265 | 1.314 | 699.86 ± 62.18 |
| kcen | input-mattcl | 1.393 ± 0.018 | 1.379 | 1.414 | 753.49 ± 66.00 |
| kcen | input-lanjian | 1.461 ± 0.010 | 1.450 | 1.466 | 790.12 ± 68.61 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|