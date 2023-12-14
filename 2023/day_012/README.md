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
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.01 ± 0.10 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.003 | 1.33 ± 0.14 |
| mattcl | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.004 | 1.33 ± 0.15 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.003 | 1.33 ± 0.15 |
| mattcl | input-pting | 0.002 ± 0.000 | 0.002 | 0.004 | 1.35 ± 0.17 |
| pting | input-kcen | 0.067 ± 0.001 | 0.065 | 0.070 | 36.62 ± 2.80 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.066 | 0.070 | 37.01 ± 2.82 |
| pting | input-mattcl | 0.068 ± 0.001 | 0.067 | 0.070 | 37.44 ± 2.87 |
| pting | input-pting | 0.069 ± 0.001 | 0.068 | 0.072 | 37.96 ± 2.89 |
| mattcl-py | input-kcen | 0.090 ± 0.001 | 0.088 | 0.092 | 49.05 ± 3.74 |
| mattcl-py | input-lanjian | 0.091 ± 0.001 | 0.089 | 0.094 | 49.95 ± 3.81 |
| mattcl-py | input-mattcl | 0.092 ± 0.001 | 0.090 | 0.096 | 50.43 ± 3.86 |
| mattcl-py | input-pting | 0.095 ± 0.001 | 0.092 | 0.098 | 51.81 ± 3.97 |
| kcen | input-kcen | 1.269 ± 0.008 | 1.260 | 1.275 | 693.97 ± 52.38 |
| kcen | input-pting | 1.306 ± 0.023 | 1.290 | 1.332 | 714.35 ± 55.18 |
| kcen | input-mattcl | 1.414 ± 0.004 | 1.411 | 1.418 | 773.35 ± 58.21 |
| kcen | input-lanjian | 1.447 ± 0.016 | 1.429 | 1.456 | 791.24 ± 60.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|