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
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.11 |
| lanjian | input-pting | 0.002 ± 0.003 | 0.002 | 0.048 | 1.15 ± 1.76 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.004 | 1.34 ± 0.16 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.006 | 1.34 ± 0.20 |
| mattcl | input-mattcl | 0.003 ± 0.000 | 0.002 | 0.004 | 1.35 ± 0.16 |
| mattcl | input-pting | 0.003 ± 0.000 | 0.002 | 0.004 | 1.35 ± 0.17 |
| pting | input-kcen | 0.067 ± 0.001 | 0.065 | 0.070 | 35.96 ± 2.99 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.066 | 0.076 | 36.73 ± 3.11 |
| pting | input-mattcl | 0.069 ± 0.001 | 0.067 | 0.074 | 37.02 ± 3.11 |
| pting | input-pting | 0.070 ± 0.001 | 0.068 | 0.072 | 37.41 ± 3.11 |
| mattcl-py | input-kcen | 0.089 ± 0.001 | 0.087 | 0.091 | 48.12 ± 3.96 |
| mattcl-py | input-lanjian | 0.091 ± 0.001 | 0.089 | 0.094 | 49.07 ± 4.05 |
| mattcl-py | input-mattcl | 0.092 ± 0.001 | 0.089 | 0.095 | 49.43 ± 4.12 |
| mattcl-py | input-pting | 0.095 ± 0.001 | 0.092 | 0.097 | 50.89 ± 4.23 |
| kcen | input-kcen | 1.283 ± 0.016 | 1.266 | 1.298 | 689.95 ± 57.08 |
| kcen | input-pting | 1.298 ± 0.009 | 1.288 | 1.307 | 698.31 ± 57.34 |
| kcen | input-mattcl | 1.431 ± 0.024 | 1.412 | 1.459 | 770.01 ± 64.30 |
| kcen | input-lanjian | 1.458 ± 0.013 | 1.443 | 1.467 | 784.24 ± 64.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|