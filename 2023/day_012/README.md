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
| lanjian | input-kcen | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 |
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.11 |
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.11 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| mattcl | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.004 | 1.31 ± 0.15 |
| mattcl | input-pting | 0.002 ± 0.000 | 0.002 | 0.006 | 1.33 ± 0.23 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.004 | 1.34 ± 0.18 |
| mattcl | input-kcen | 0.003 ± 0.000 | 0.002 | 0.006 | 1.34 ± 0.23 |
| pting | input-kcen | 0.067 ± 0.001 | 0.065 | 0.070 | 35.88 ± 2.91 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.066 | 0.070 | 36.38 ± 2.91 |
| pting | input-mattcl | 0.068 ± 0.001 | 0.066 | 0.070 | 36.53 ± 2.92 |
| pting | input-pting | 0.070 ± 0.001 | 0.068 | 0.073 | 37.28 ± 2.98 |
| mattcl-py | input-kcen | 0.089 ± 0.001 | 0.087 | 0.091 | 47.77 ± 3.81 |
| mattcl-py | input-lanjian | 0.092 ± 0.001 | 0.090 | 0.094 | 49.08 ± 3.93 |
| mattcl-py | input-mattcl | 0.093 ± 0.006 | 0.088 | 0.123 | 49.97 ± 5.25 |
| mattcl-py | input-pting | 0.094 ± 0.001 | 0.092 | 0.098 | 50.62 ± 4.06 |
| kcen | input-pting | 1.270 ± 0.013 | 1.259 | 1.285 | 680.54 ± 54.13 |
| kcen | input-kcen | 1.291 ± 0.030 | 1.258 | 1.316 | 691.70 ± 56.89 |
| kcen | input-mattcl | 1.405 ± 0.031 | 1.383 | 1.441 | 752.82 ± 61.72 |
| kcen | input-lanjian | 1.429 ± 0.014 | 1.413 | 1.440 | 765.38 ± 60.85 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|