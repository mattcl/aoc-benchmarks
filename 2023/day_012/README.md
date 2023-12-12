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
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 |
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.11 |
| lanjian | input-kcen | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.11 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| mattcl | input-lanjian | 0.004 ± 0.001 | 0.003 | 0.010 | 2.22 ± 0.41 |
| mattcl | input-mattcl | 0.004 ± 0.000 | 0.003 | 0.006 | 2.24 ± 0.28 |
| mattcl | input-kcen | 0.004 ± 0.000 | 0.003 | 0.007 | 2.27 ± 0.31 |
| mattcl | input-pting | 0.004 ± 0.001 | 0.003 | 0.008 | 2.28 ± 0.40 |
| pting | input-kcen | 0.298 ± 0.003 | 0.293 | 0.303 | 162.26 ± 12.96 |
| pting | input-lanjian | 0.299 ± 0.004 | 0.293 | 0.303 | 162.65 ± 13.02 |
| pting | input-mattcl | 0.304 ± 0.002 | 0.301 | 0.309 | 165.74 ± 13.18 |
| pting | input-pting | 0.315 ± 0.004 | 0.308 | 0.320 | 171.76 ± 13.75 |
| kcen | input-pting | 1.277 ± 0.023 | 1.262 | 1.304 | 695.12 ± 56.46 |
| kcen | input-kcen | 1.297 ± 0.022 | 1.282 | 1.322 | 705.92 ± 57.18 |
| kcen | input-mattcl | 1.398 ± 0.023 | 1.373 | 1.420 | 761.00 ± 61.55 |
| kcen | input-lanjian | 1.444 ± 0.028 | 1.412 | 1.460 | 785.99 ± 64.01 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|