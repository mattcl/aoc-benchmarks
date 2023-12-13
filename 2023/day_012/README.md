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
| lanjian | input-kcen | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.11 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.09 |
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.11 |
| mattcl | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.003 | 1.33 ± 0.15 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.004 | 1.33 ± 0.16 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.005 | 1.34 ± 0.19 |
| mattcl | input-pting | 0.003 ± 0.000 | 0.002 | 0.004 | 1.35 ± 0.17 |
| pting | input-kcen | 0.067 ± 0.001 | 0.065 | 0.070 | 36.05 ± 2.87 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.066 | 0.073 | 36.77 ± 2.98 |
| pting | input-mattcl | 0.069 ± 0.002 | 0.066 | 0.078 | 37.49 ± 3.19 |
| pting | input-pting | 0.070 ± 0.001 | 0.067 | 0.071 | 37.51 ± 2.97 |
| mattcl-py | input-kcen | 0.090 ± 0.001 | 0.088 | 0.093 | 48.48 ± 3.85 |
| mattcl-py | input-lanjian | 0.091 ± 0.001 | 0.089 | 0.094 | 49.15 ± 3.87 |
| mattcl-py | input-mattcl | 0.092 ± 0.001 | 0.089 | 0.095 | 49.56 ± 3.96 |
| mattcl-py | input-pting | 0.094 ± 0.001 | 0.092 | 0.098 | 50.99 ± 4.04 |
| kcen | input-pting | 1.296 ± 0.018 | 1.277 | 1.311 | 699.15 ± 55.45 |
| kcen | input-kcen | 1.297 ± 0.035 | 1.258 | 1.326 | 699.77 ± 57.88 |
| kcen | input-mattcl | 1.407 ± 0.013 | 1.396 | 1.422 | 759.07 ± 59.74 |
| kcen | input-lanjian | 1.460 ± 0.024 | 1.434 | 1.482 | 787.75 ± 62.95 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|