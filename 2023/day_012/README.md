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
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.11 |
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.12 |
| mattcl | input-mattcl | 0.003 ± 0.000 | 0.002 | 0.005 | 1.29 ± 0.16 |
| mattcl | input-lanjian | 0.003 ± 0.000 | 0.002 | 0.005 | 1.30 ± 0.18 |
| mattcl | input-pting | 0.003 ± 0.000 | 0.002 | 0.004 | 1.31 ± 0.16 |
| mattcl | input-kcen | 0.003 ± 0.002 | 0.002 | 0.028 | 1.43 ± 0.92 |
| pting | input-kcen | 0.293 ± 0.003 | 0.289 | 0.298 | 147.35 ± 12.07 |
| pting | input-lanjian | 0.298 ± 0.002 | 0.296 | 0.301 | 149.96 ± 12.24 |
| pting | input-mattcl | 0.302 ± 0.005 | 0.297 | 0.313 | 152.02 ± 12.60 |
| pting | input-pting | 0.311 ± 0.002 | 0.307 | 0.313 | 156.35 ± 12.78 |
| kcen | input-pting | 1.246 ± 0.008 | 1.238 | 1.255 | 627.13 ± 51.25 |
| kcen | input-kcen | 1.262 ± 0.019 | 1.240 | 1.276 | 634.95 ± 52.63 |
| kcen | input-mattcl | 1.369 ± 0.023 | 1.349 | 1.393 | 688.89 ± 57.26 |
| kcen | input-lanjian | 1.428 ± 0.024 | 1.401 | 1.445 | 718.95 ± 59.81 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|