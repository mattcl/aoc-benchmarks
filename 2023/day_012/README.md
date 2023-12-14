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
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.005 | 1.01 ± 0.15 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.003 | 1.01 ± 0.10 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.004 | 1.33 ± 0.16 |
| mattcl | input-pting | 0.002 ± 0.000 | 0.002 | 0.003 | 1.33 ± 0.14 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.004 | 1.33 ± 0.17 |
| mattcl | input-mattcl | 0.003 ± 0.000 | 0.002 | 0.006 | 1.37 ± 0.21 |
| pting | input-kcen | 0.067 ± 0.001 | 0.065 | 0.071 | 35.84 ± 2.73 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.066 | 0.072 | 36.63 ± 2.79 |
| pting | input-pting | 0.070 ± 0.001 | 0.067 | 0.075 | 37.23 ± 2.84 |
| pting | input-mattcl | 0.070 ± 0.006 | 0.066 | 0.107 | 37.34 ± 4.29 |
| mattcl-py | input-kcen | 0.090 ± 0.001 | 0.088 | 0.092 | 47.94 ± 3.62 |
| mattcl-py | input-lanjian | 0.091 ± 0.001 | 0.089 | 0.094 | 48.92 ± 3.68 |
| mattcl-py | input-mattcl | 0.092 ± 0.002 | 0.090 | 0.096 | 49.22 ± 3.75 |
| mattcl-py | input-pting | 0.095 ± 0.001 | 0.092 | 0.099 | 50.73 ± 3.84 |
| kcen | input-kcen | 1.253 ± 0.016 | 1.236 | 1.266 | 670.62 ± 50.50 |
| kcen | input-pting | 1.295 ± 0.024 | 1.279 | 1.322 | 693.09 ± 53.05 |
| kcen | input-mattcl | 1.405 ± 0.024 | 1.391 | 1.433 | 751.99 ± 57.31 |
| kcen | input-lanjian | 1.447 ± 0.017 | 1.428 | 1.459 | 774.74 ± 58.25 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|