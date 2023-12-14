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
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.12 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.005 | 1.32 ± 0.21 |
| mattcl | input-pting | 0.002 ± 0.000 | 0.002 | 0.004 | 1.33 ± 0.16 |
| mattcl | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.005 | 1.34 ± 0.20 |
| mattcl | input-kcen | 0.003 ± 0.001 | 0.002 | 0.010 | 1.39 ± 0.40 |
| pting | input-kcen | 0.067 ± 0.001 | 0.065 | 0.069 | 36.69 ± 3.11 |
| pting | input-mattcl | 0.068 ± 0.001 | 0.066 | 0.069 | 37.25 ± 3.16 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.065 | 0.071 | 37.39 ± 3.21 |
| pting | input-pting | 0.069 ± 0.001 | 0.067 | 0.070 | 37.83 ± 3.20 |
| mattcl-py | input-lanjian | 0.091 ± 0.001 | 0.089 | 0.093 | 50.06 ± 4.23 |
| mattcl-py | input-mattcl | 0.091 ± 0.001 | 0.089 | 0.094 | 50.22 ± 4.26 |
| mattcl-py | input-kcen | 0.093 ± 0.010 | 0.087 | 0.146 | 50.98 ± 7.10 |
| mattcl-py | input-pting | 0.093 ± 0.001 | 0.091 | 0.097 | 51.12 ± 4.34 |
| kcen | input-pting | 1.290 ± 0.009 | 1.282 | 1.299 | 710.32 ± 59.72 |
| kcen | input-kcen | 1.299 ± 0.026 | 1.269 | 1.318 | 715.42 ± 61.70 |
| kcen | input-mattcl | 1.413 ± 0.024 | 1.396 | 1.441 | 778.52 ± 66.56 |
| kcen | input-lanjian | 1.501 ± 0.016 | 1.484 | 1.511 | 826.97 ± 69.83 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|