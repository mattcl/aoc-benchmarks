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
| lanjian | input-kcen | 0.002 ± 0.000 | 0.002 | 0.003 | 1.00 ± 0.12 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.005 | 1.32 ± 0.18 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.004 | 1.33 ± 0.18 |
| mattcl | input-pting | 0.002 ± 0.000 | 0.002 | 0.004 | 1.33 ± 0.18 |
| mattcl | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.003 | 1.34 ± 0.15 |
| pting | input-kcen | 0.067 ± 0.001 | 0.065 | 0.070 | 36.36 ± 2.99 |
| pting | input-lanjian | 0.067 ± 0.001 | 0.066 | 0.071 | 36.82 ± 3.03 |
| pting | input-mattcl | 0.068 ± 0.001 | 0.066 | 0.070 | 36.95 ± 3.02 |
| pting | input-pting | 0.069 ± 0.001 | 0.067 | 0.071 | 37.50 ± 3.04 |
| mattcl-py | input-kcen | 0.089 ± 0.002 | 0.086 | 0.095 | 48.62 ± 4.00 |
| mattcl-py | input-lanjian | 0.091 ± 0.001 | 0.088 | 0.095 | 49.44 ± 4.04 |
| mattcl-py | input-mattcl | 0.093 ± 0.009 | 0.089 | 0.140 | 50.71 ± 6.39 |
| mattcl-py | input-pting | 0.093 ± 0.001 | 0.090 | 0.097 | 50.78 ± 4.15 |
| kcen | input-kcen | 1.286 ± 0.011 | 1.274 | 1.293 | 701.46 ± 56.67 |
| kcen | input-pting | 1.293 ± 0.016 | 1.279 | 1.310 | 705.14 ± 57.34 |
| kcen | input-mattcl | 1.433 ± 0.018 | 1.419 | 1.454 | 781.83 ± 63.62 |
| kcen | input-lanjian | 1.460 ± 0.015 | 1.443 | 1.473 | 796.26 ± 64.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|