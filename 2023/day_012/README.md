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
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.003 | 1.00 ± 0.10 |
| lanjian | input-kcen | 0.002 ± 0.000 | 0.002 | 0.003 | 1.00 ± 0.12 |
| mattcl | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.005 | 1.33 ± 0.18 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.006 | 1.33 ± 0.20 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.006 | 1.33 ± 0.23 |
| mattcl | input-pting | 0.002 ± 0.000 | 0.002 | 0.005 | 1.34 ± 0.19 |
| pting | input-kcen | 0.067 ± 0.001 | 0.065 | 0.068 | 35.96 ± 2.28 |
| pting | input-lanjian | 0.067 ± 0.001 | 0.066 | 0.072 | 36.42 ± 2.32 |
| pting | input-pting | 0.069 ± 0.001 | 0.067 | 0.072 | 37.27 ± 2.36 |
| pting | input-mattcl | 0.069 ± 0.007 | 0.066 | 0.112 | 37.51 ± 4.31 |
| mattcl-py | input-kcen | 0.089 ± 0.001 | 0.087 | 0.092 | 47.99 ± 3.04 |
| mattcl-py | input-lanjian | 0.090 ± 0.001 | 0.088 | 0.096 | 48.85 ± 3.10 |
| mattcl-py | input-mattcl | 0.091 ± 0.001 | 0.088 | 0.094 | 49.08 ± 3.11 |
| mattcl-py | input-pting | 0.093 ± 0.001 | 0.091 | 0.095 | 50.23 ± 3.14 |
| kcen | input-pting | 1.288 ± 0.013 | 1.274 | 1.300 | 695.35 ± 43.37 |
| kcen | input-kcen | 1.290 ± 0.004 | 1.287 | 1.295 | 696.46 ± 42.92 |
| kcen | input-mattcl | 1.426 ± 0.010 | 1.419 | 1.437 | 769.97 ± 47.68 |
| kcen | input-lanjian | 1.472 ± 0.044 | 1.423 | 1.509 | 794.63 ± 54.33 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|