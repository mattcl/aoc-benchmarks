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
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.11 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.01 ± 0.12 |
| mattcl | input-kcen | 0.004 ± 0.001 | 0.003 | 0.007 | 2.11 ± 0.32 |
| mattcl | input-mattcl | 0.004 ± 0.001 | 0.003 | 0.009 | 2.25 ± 0.36 |
| mattcl | input-lanjian | 0.004 ± 0.001 | 0.003 | 0.010 | 2.27 ± 0.41 |
| mattcl | input-pting | 0.004 ± 0.000 | 0.003 | 0.007 | 2.27 ± 0.31 |
| pting | input-kcen | 0.295 ± 0.004 | 0.291 | 0.302 | 159.98 ± 13.02 |
| pting | input-lanjian | 0.300 ± 0.002 | 0.296 | 0.304 | 162.95 ± 13.16 |
| pting | input-mattcl | 0.304 ± 0.005 | 0.296 | 0.315 | 165.05 ± 13.56 |
| pting | input-pting | 0.313 ± 0.002 | 0.310 | 0.316 | 169.98 ± 13.70 |
| kcen | input-kcen | 1.265 ± 0.003 | 1.261 | 1.268 | 686.20 ± 55.15 |
| kcen | input-pting | 1.279 ± 0.005 | 1.276 | 1.285 | 694.05 ± 55.82 |
| kcen | input-mattcl | 1.386 ± 0.005 | 1.381 | 1.390 | 752.01 ± 60.47 |
| kcen | input-lanjian | 1.434 ± 0.032 | 1.399 | 1.463 | 777.81 ± 64.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|