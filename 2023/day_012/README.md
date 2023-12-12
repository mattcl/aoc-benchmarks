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
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.12 |
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.12 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.01 ± 0.11 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.004 | 1.30 ± 0.16 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.003 | 1.31 ± 0.16 |
| mattcl | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.006 | 1.33 ± 0.20 |
| mattcl | input-pting | 0.003 ± 0.000 | 0.002 | 0.006 | 1.34 ± 0.19 |
| pting | input-kcen | 0.293 ± 0.005 | 0.287 | 0.303 | 155.73 ± 13.04 |
| pting | input-lanjian | 0.297 ± 0.003 | 0.292 | 0.304 | 157.93 ± 13.01 |
| pting | input-mattcl | 0.301 ± 0.003 | 0.296 | 0.305 | 160.29 ± 13.22 |
| pting | input-pting | 0.309 ± 0.003 | 0.305 | 0.315 | 164.61 ± 13.56 |
| kcen | input-kcen | 1.259 ± 0.003 | 1.256 | 1.261 | 669.69 ± 54.75 |
| kcen | input-pting | 1.269 ± 0.006 | 1.262 | 1.273 | 674.74 ± 55.23 |
| kcen | input-mattcl | 1.395 ± 0.021 | 1.381 | 1.419 | 741.96 ± 61.66 |
| kcen | input-lanjian | 1.443 ± 0.043 | 1.394 | 1.474 | 767.66 ± 66.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|