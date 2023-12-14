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
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| lanjian | input-kcen | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.003 | 1.01 ± 0.09 |
| mattcl | input-lanjian | 0.003 ± 0.000 | 0.002 | 0.004 | 1.30 ± 0.13 |
| mattcl | input-mattcl | 0.003 ± 0.000 | 0.002 | 0.004 | 1.30 ± 0.14 |
| mattcl | input-kcen | 0.003 ± 0.000 | 0.002 | 0.006 | 1.31 ± 0.19 |
| mattcl | input-pting | 0.003 ± 0.000 | 0.002 | 0.006 | 1.33 ± 0.19 |
| pting | input-kcen | 0.067 ± 0.001 | 0.065 | 0.073 | 34.32 ± 2.34 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.067 | 0.072 | 34.86 ± 2.33 |
| pting | input-mattcl | 0.068 ± 0.001 | 0.066 | 0.071 | 34.92 ± 2.33 |
| pting | input-pting | 0.070 ± 0.001 | 0.068 | 0.074 | 35.55 ± 2.37 |
| mattcl-py | input-kcen | 0.090 ± 0.005 | 0.087 | 0.114 | 46.12 ± 3.78 |
| mattcl-py | input-lanjian | 0.092 ± 0.002 | 0.089 | 0.096 | 46.81 ± 3.16 |
| mattcl-py | input-mattcl | 0.092 ± 0.001 | 0.090 | 0.094 | 46.86 ± 3.10 |
| mattcl-py | input-pting | 0.095 ± 0.002 | 0.092 | 0.099 | 48.33 ± 3.26 |
| kcen | input-kcen | 1.267 ± 0.024 | 1.242 | 1.291 | 646.54 ± 43.89 |
| kcen | input-pting | 1.287 ± 0.021 | 1.270 | 1.310 | 657.09 ± 44.05 |
| kcen | input-mattcl | 1.406 ± 0.019 | 1.385 | 1.419 | 717.82 ± 47.68 |
| kcen | input-lanjian | 1.456 ± 0.009 | 1.446 | 1.463 | 742.94 ± 48.56 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|