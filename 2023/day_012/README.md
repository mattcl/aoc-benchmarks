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
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.11 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| lanjian | input-kcen | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.12 |
| mattcl | input-kcen | 0.003 ± 0.000 | 0.002 | 0.004 | 1.33 ± 0.17 |
| mattcl | input-pting | 0.003 ± 0.000 | 0.002 | 0.003 | 1.33 ± 0.15 |
| mattcl | input-mattcl | 0.003 ± 0.000 | 0.002 | 0.005 | 1.33 ± 0.18 |
| mattcl | input-lanjian | 0.003 ± 0.000 | 0.002 | 0.005 | 1.33 ± 0.17 |
| pting | input-kcen | 0.067 ± 0.001 | 0.065 | 0.069 | 35.49 ± 2.83 |
| pting | input-lanjian | 0.069 ± 0.002 | 0.066 | 0.074 | 36.37 ± 3.01 |
| pting | input-mattcl | 0.069 ± 0.001 | 0.067 | 0.073 | 36.40 ± 2.93 |
| pting | input-pting | 0.070 ± 0.001 | 0.068 | 0.072 | 37.00 ± 2.95 |
| mattcl-py | input-kcen | 0.090 ± 0.001 | 0.087 | 0.092 | 47.62 ± 3.81 |
| mattcl-py | input-lanjian | 0.091 ± 0.001 | 0.089 | 0.094 | 48.37 ± 3.84 |
| mattcl-py | input-mattcl | 0.092 ± 0.001 | 0.089 | 0.094 | 48.87 ± 3.89 |
| mattcl-py | input-pting | 0.094 ± 0.001 | 0.092 | 0.096 | 49.98 ± 3.97 |
| kcen | input-kcen | 1.270 ± 0.019 | 1.255 | 1.291 | 674.21 ± 53.80 |
| kcen | input-pting | 1.289 ± 0.008 | 1.281 | 1.297 | 684.33 ± 53.82 |
| kcen | input-mattcl | 1.412 ± 0.010 | 1.402 | 1.422 | 749.43 ± 58.97 |
| kcen | input-lanjian | 1.460 ± 0.015 | 1.447 | 1.476 | 774.68 ± 61.25 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|