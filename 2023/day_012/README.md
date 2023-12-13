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
| lanjian | input-kcen | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.12 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.11 |
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.12 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.004 | 1.30 ± 0.16 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.003 | 1.30 ± 0.14 |
| mattcl | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.003 | 1.31 ± 0.15 |
| mattcl | input-pting | 0.003 ± 0.000 | 0.002 | 0.005 | 1.32 ± 0.18 |
| pting | input-kcen | 0.067 ± 0.002 | 0.064 | 0.072 | 35.27 ± 3.05 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.066 | 0.071 | 35.60 ± 3.00 |
| pting | input-pting | 0.069 ± 0.001 | 0.067 | 0.071 | 36.12 ± 3.03 |
| pting | input-mattcl | 0.069 ± 0.005 | 0.066 | 0.101 | 36.17 ± 4.02 |
| mattcl-py | input-kcen | 0.089 ± 0.001 | 0.086 | 0.090 | 46.79 ± 3.91 |
| mattcl-py | input-lanjian | 0.091 ± 0.001 | 0.088 | 0.094 | 47.88 ± 4.05 |
| mattcl-py | input-mattcl | 0.091 ± 0.001 | 0.089 | 0.094 | 47.99 ± 4.05 |
| mattcl-py | input-pting | 0.093 ± 0.001 | 0.091 | 0.096 | 49.07 ± 4.13 |
| kcen | input-pting | 1.292 ± 0.006 | 1.285 | 1.297 | 681.06 ± 56.64 |
| kcen | input-kcen | 1.304 ± 0.005 | 1.301 | 1.310 | 687.43 ± 57.13 |
| kcen | input-mattcl | 1.424 ± 0.013 | 1.415 | 1.439 | 750.41 ± 62.67 |
| kcen | input-lanjian | 1.470 ± 0.014 | 1.458 | 1.485 | 774.46 ± 64.72 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|