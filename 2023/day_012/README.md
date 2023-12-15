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
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.003 | 1.04 ± 0.12 |
| lanjian | input-kcen | 0.002 ± 0.002 | 0.002 | 0.034 | 1.11 ± 1.17 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.004 | 1.30 ± 0.14 |
| mattcl | input-mattcl | 0.003 ± 0.000 | 0.002 | 0.003 | 1.31 ± 0.14 |
| mattcl | input-pting | 0.003 ± 0.000 | 0.002 | 0.003 | 1.32 ± 0.14 |
| mattcl | input-kcen | 0.003 ± 0.002 | 0.002 | 0.036 | 1.42 ± 1.24 |
| pting | input-kcen | 0.067 ± 0.005 | 0.065 | 0.096 | 35.03 ± 3.71 |
| pting | input-mattcl | 0.068 ± 0.001 | 0.066 | 0.070 | 35.13 ± 2.49 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.067 | 0.072 | 35.21 ± 2.51 |
| pting | input-pting | 0.069 ± 0.001 | 0.066 | 0.072 | 35.84 ± 2.56 |
| mattcl-py | input-kcen | 0.089 ± 0.001 | 0.087 | 0.092 | 46.33 ± 3.31 |
| mattcl-py | input-mattcl | 0.091 ± 0.001 | 0.089 | 0.094 | 47.37 ± 3.35 |
| mattcl-py | input-lanjian | 0.092 ± 0.003 | 0.089 | 0.105 | 47.65 ± 3.67 |
| mattcl-py | input-pting | 0.094 ± 0.001 | 0.091 | 0.097 | 48.66 ± 3.46 |
| kcen | input-kcen | 1.282 ± 0.016 | 1.264 | 1.293 | 665.70 ± 47.17 |
| kcen | input-pting | 1.293 ± 0.009 | 1.285 | 1.303 | 671.48 ± 47.05 |
| kcen | input-mattcl | 1.430 ± 0.032 | 1.398 | 1.461 | 742.47 ± 54.30 |
| kcen | input-lanjian | 1.481 ± 0.012 | 1.471 | 1.494 | 768.97 ± 53.97 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|