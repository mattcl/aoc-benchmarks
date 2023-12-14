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
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.12 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| lanjian | input-kcen | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.11 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.004 | 1.30 ± 0.16 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.003 | 1.31 ± 0.16 |
| mattcl | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.004 | 1.32 ± 0.16 |
| mattcl | input-pting | 0.002 ± 0.000 | 0.002 | 0.006 | 1.34 ± 0.24 |
| pting | input-kcen | 0.066 ± 0.001 | 0.065 | 0.070 | 35.84 ± 2.93 |
| pting | input-lanjian | 0.067 ± 0.001 | 0.066 | 0.070 | 36.47 ± 2.95 |
| pting | input-mattcl | 0.068 ± 0.001 | 0.066 | 0.071 | 36.66 ± 2.99 |
| pting | input-pting | 0.069 ± 0.001 | 0.067 | 0.072 | 37.21 ± 3.02 |
| mattcl-py | input-kcen | 0.089 ± 0.001 | 0.086 | 0.092 | 48.03 ± 3.91 |
| mattcl-py | input-lanjian | 0.091 ± 0.001 | 0.088 | 0.093 | 49.03 ± 3.95 |
| mattcl-py | input-mattcl | 0.091 ± 0.001 | 0.089 | 0.093 | 49.08 ± 3.94 |
| mattcl-py | input-pting | 0.093 ± 0.001 | 0.091 | 0.096 | 50.29 ± 4.06 |
| kcen | input-kcen | 1.263 ± 0.012 | 1.252 | 1.275 | 683.69 ± 54.92 |
| kcen | input-pting | 1.307 ± 0.017 | 1.287 | 1.319 | 707.29 ± 57.17 |
| kcen | input-mattcl | 1.430 ± 0.027 | 1.402 | 1.456 | 774.13 ± 63.48 |
| kcen | input-lanjian | 1.468 ± 0.007 | 1.462 | 1.476 | 794.86 ± 63.54 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|