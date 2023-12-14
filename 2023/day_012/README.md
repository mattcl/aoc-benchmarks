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
| lanjian | input-kcen | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 |
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.12 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.003 | 1.00 ± 0.11 |
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.003 | 1.01 ± 0.13 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.003 | 1.30 ± 0.15 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.004 | 1.30 ± 0.18 |
| mattcl | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.004 | 1.33 ± 0.18 |
| mattcl | input-pting | 0.002 ± 0.000 | 0.002 | 0.003 | 1.33 ± 0.16 |
| pting | input-kcen | 0.067 ± 0.001 | 0.065 | 0.070 | 36.06 ± 3.23 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.065 | 0.072 | 36.56 ± 3.29 |
| pting | input-mattcl | 0.068 ± 0.001 | 0.066 | 0.070 | 36.64 ± 3.27 |
| pting | input-pting | 0.069 ± 0.001 | 0.066 | 0.074 | 37.22 ± 3.35 |
| mattcl-py | input-kcen | 0.089 ± 0.001 | 0.087 | 0.092 | 48.21 ± 4.30 |
| mattcl-py | input-lanjian | 0.091 ± 0.002 | 0.089 | 0.096 | 49.07 ± 4.42 |
| mattcl-py | input-mattcl | 0.091 ± 0.001 | 0.088 | 0.094 | 49.09 ± 4.40 |
| mattcl-py | input-pting | 0.093 ± 0.001 | 0.091 | 0.096 | 50.54 ± 4.52 |
| kcen | input-pting | 1.294 ± 0.007 | 1.288 | 1.302 | 700.10 ± 61.90 |
| kcen | input-kcen | 1.301 ± 0.014 | 1.288 | 1.315 | 703.74 ± 62.54 |
| kcen | input-mattcl | 1.407 ± 0.003 | 1.404 | 1.409 | 761.13 ± 67.20 |
| kcen | input-lanjian | 1.484 ± 0.015 | 1.467 | 1.494 | 802.59 ± 71.29 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|