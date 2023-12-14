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
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.09 |
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.11 |
| lanjian | input-kcen | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.11 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.005 | 1.32 ± 0.18 |
| mattcl | input-pting | 0.003 ± 0.000 | 0.002 | 0.006 | 1.35 ± 0.19 |
| mattcl | input-lanjian | 0.003 ± 0.000 | 0.002 | 0.005 | 1.35 ± 0.23 |
| mattcl | input-mattcl | 0.003 ± 0.000 | 0.002 | 0.005 | 1.36 ± 0.23 |
| pting | input-kcen | 0.067 ± 0.001 | 0.066 | 0.069 | 36.06 ± 2.66 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.066 | 0.071 | 36.69 ± 2.72 |
| pting | input-mattcl | 0.070 ± 0.005 | 0.067 | 0.103 | 37.41 ± 3.97 |
| pting | input-pting | 0.070 ± 0.001 | 0.067 | 0.075 | 37.56 ± 2.83 |
| mattcl-py | input-kcen | 0.089 ± 0.001 | 0.088 | 0.091 | 48.03 ± 3.52 |
| mattcl-py | input-lanjian | 0.091 ± 0.001 | 0.088 | 0.093 | 49.05 ± 3.61 |
| mattcl-py | input-mattcl | 0.091 ± 0.001 | 0.090 | 0.094 | 49.23 ± 3.62 |
| mattcl-py | input-pting | 0.095 ± 0.001 | 0.092 | 0.098 | 50.88 ± 3.77 |
| kcen | input-kcen | 1.261 ± 0.012 | 1.247 | 1.271 | 678.83 ± 49.62 |
| kcen | input-pting | 1.292 ± 0.002 | 1.290 | 1.294 | 695.26 ± 50.38 |
| kcen | input-mattcl | 1.392 ± 0.010 | 1.384 | 1.403 | 749.40 ± 54.55 |
| kcen | input-lanjian | 1.456 ± 0.038 | 1.430 | 1.500 | 783.79 ± 60.34 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|