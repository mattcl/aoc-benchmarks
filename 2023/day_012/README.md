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
| lanjian | input-kcen | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.13 |
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.13 |
| lanjian | input-pting | 0.002 ± 0.003 | 0.002 | 0.045 | 1.12 ± 1.56 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.003 | 1.28 ± 0.15 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.003 | 1.28 ± 0.16 |
| mattcl | input-mattcl | 0.003 ± 0.000 | 0.002 | 0.004 | 1.31 ± 0.16 |
| mattcl | input-pting | 0.003 ± 0.000 | 0.002 | 0.006 | 1.34 ± 0.24 |
| pting | input-kcen | 0.295 ± 0.002 | 0.290 | 0.298 | 151.44 ± 13.90 |
| pting | input-lanjian | 0.297 ± 0.003 | 0.293 | 0.301 | 152.51 ± 14.03 |
| pting | input-mattcl | 0.302 ± 0.003 | 0.296 | 0.308 | 155.10 ± 14.29 |
| pting | input-pting | 0.309 ± 0.002 | 0.306 | 0.313 | 158.76 ± 14.57 |
| kcen | input-pting | 1.254 ± 0.009 | 1.244 | 1.263 | 644.37 ± 59.14 |
| kcen | input-kcen | 1.274 ± 0.006 | 1.267 | 1.280 | 654.69 ± 59.97 |
| kcen | input-mattcl | 1.391 ± 0.011 | 1.383 | 1.403 | 714.66 ± 65.59 |
| kcen | input-lanjian | 1.463 ± 0.034 | 1.424 | 1.486 | 751.72 ± 70.92 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|