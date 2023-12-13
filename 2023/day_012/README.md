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
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.003 | 1.06 ± 0.12 |
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.003 | 1.08 ± 0.12 |
| lanjian | input-pting | 0.002 ± 0.001 | 0.002 | 0.006 | 1.11 ± 0.29 |
| mattcl | input-kcen | 0.003 ± 0.000 | 0.002 | 0.005 | 1.39 ± 0.25 |
| mattcl | input-mattcl | 0.003 ± 0.000 | 0.002 | 0.005 | 1.40 ± 0.18 |
| mattcl | input-lanjian | 0.003 ± 0.000 | 0.002 | 0.005 | 1.46 ± 0.19 |
| mattcl | input-pting | 0.003 ± 0.001 | 0.002 | 0.006 | 1.49 ± 0.31 |
| pting | input-kcen | 0.071 ± 0.002 | 0.067 | 0.075 | 37.84 ± 2.39 |
| pting | input-lanjian | 0.071 ± 0.002 | 0.068 | 0.076 | 38.17 ± 2.42 |
| pting | input-mattcl | 0.072 ± 0.002 | 0.068 | 0.075 | 38.61 ± 2.43 |
| pting | input-pting | 0.075 ± 0.003 | 0.071 | 0.081 | 40.14 ± 2.78 |
| mattcl-py | input-kcen | 0.094 ± 0.008 | 0.088 | 0.138 | 50.62 ± 5.29 |
| mattcl-py | input-lanjian | 0.096 ± 0.002 | 0.091 | 0.100 | 51.53 ± 3.27 |
| mattcl-py | input-mattcl | 0.097 ± 0.003 | 0.090 | 0.105 | 52.01 ± 3.58 |
| mattcl-py | input-pting | 0.103 ± 0.006 | 0.093 | 0.119 | 55.27 ± 4.52 |
| kcen | input-kcen | 1.293 ± 0.024 | 1.268 | 1.317 | 693.44 ± 42.75 |
| kcen | input-pting | 1.321 ± 0.012 | 1.311 | 1.334 | 708.08 ± 42.05 |
| kcen | input-mattcl | 1.455 ± 0.042 | 1.420 | 1.502 | 780.15 ± 51.07 |
| kcen | input-lanjian | 1.485 ± 0.025 | 1.463 | 1.511 | 796.19 ± 48.59 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|