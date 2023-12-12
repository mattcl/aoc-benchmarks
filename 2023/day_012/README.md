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
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 |
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.12 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.11 |
| lanjian | input-kcen | 0.002 ± 0.000 | 0.002 | 0.003 | 1.01 ± 0.14 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.003 | 1.31 ± 0.15 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.003 | 1.33 ± 0.16 |
| mattcl | input-pting | 0.002 ± 0.000 | 0.002 | 0.003 | 1.35 ± 0.16 |
| mattcl | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.005 | 1.36 ± 0.20 |
| pting | input-kcen | 0.298 ± 0.004 | 0.289 | 0.304 | 163.26 ± 14.09 |
| pting | input-lanjian | 0.299 ± 0.004 | 0.292 | 0.308 | 164.02 ± 14.17 |
| pting | input-mattcl | 0.302 ± 0.003 | 0.298 | 0.306 | 165.81 ± 14.21 |
| pting | input-pting | 0.311 ± 0.002 | 0.309 | 0.313 | 170.91 ± 14.57 |
| kcen | input-pting | 1.265 ± 0.008 | 1.259 | 1.274 | 693.94 ± 59.19 |
| kcen | input-kcen | 1.279 ± 0.018 | 1.259 | 1.294 | 702.10 ± 60.56 |
| kcen | input-mattcl | 1.394 ± 0.038 | 1.356 | 1.432 | 765.13 ± 68.34 |
| kcen | input-lanjian | 1.438 ± 0.020 | 1.426 | 1.460 | 789.01 ± 67.97 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|