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
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [s] | Min [s] | Max [s] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-kcen | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.003 | 1.00 ± 0.13 |
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.003 | 1.00 ± 0.12 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.003 | 1.01 ± 0.10 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.003 | 1.01 ± 0.10 |
| mattcl | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.02 ± 0.11 |
| mattcl | input-pting | 0.002 ± 0.000 | 0.002 | 0.003 | 1.07 ± 0.14 |
| pting | input-lanjian | 0.298 ± 0.003 | 0.292 | 0.301 | 157.63 ± 12.96 |
| pting | input-kcen | 0.301 ± 0.009 | 0.286 | 0.315 | 159.34 ± 13.79 |
| pting | input-mattcl | 0.302 ± 0.003 | 0.298 | 0.305 | 159.72 ± 13.10 |
| pting | input-pting | 0.311 ± 0.004 | 0.308 | 0.319 | 164.87 ± 13.60 |
| kcen | input-kcen | 1.261 ± 0.016 | 1.245 | 1.277 | 667.88 ± 55.14 |
| kcen | input-pting | 1.279 ± 0.013 | 1.269 | 1.294 | 676.98 ± 55.65 |
| kcen | input-mattcl | 1.376 ± 0.015 | 1.358 | 1.385 | 728.27 ± 59.93 |
| kcen | input-lanjian | 1.411 ± 0.014 | 1.401 | 1.427 | 747.21 ± 61.38 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|