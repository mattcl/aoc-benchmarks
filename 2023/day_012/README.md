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
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.11 |
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.005 | 1.30 ± 0.17 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.003 | 1.32 ± 0.15 |
| mattcl | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.004 | 1.32 ± 0.15 |
| mattcl | input-pting | 0.003 ± 0.000 | 0.002 | 0.004 | 1.34 ± 0.17 |
| pting | input-mattcl | 0.068 ± 0.001 | 0.066 | 0.071 | 36.09 ± 2.74 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.066 | 0.072 | 36.24 ± 2.77 |
| pting | input-kcen | 0.069 ± 0.010 | 0.065 | 0.131 | 36.65 ± 5.92 |
| pting | input-pting | 0.069 ± 0.001 | 0.067 | 0.071 | 36.88 ± 2.78 |
| mattcl-py | input-kcen | 0.090 ± 0.003 | 0.087 | 0.099 | 47.98 ± 3.82 |
| mattcl-py | input-lanjian | 0.091 ± 0.001 | 0.089 | 0.093 | 48.31 ± 3.63 |
| mattcl-py | input-mattcl | 0.091 ± 0.002 | 0.089 | 0.095 | 48.41 ± 3.70 |
| mattcl-py | input-pting | 0.093 ± 0.001 | 0.091 | 0.096 | 49.73 ± 3.75 |
| kcen | input-kcen | 1.287 ± 0.025 | 1.263 | 1.312 | 686.98 ± 52.64 |
| kcen | input-pting | 1.305 ± 0.022 | 1.291 | 1.331 | 696.55 ± 53.01 |
| kcen | input-mattcl | 1.415 ± 0.035 | 1.390 | 1.454 | 754.96 ± 58.98 |
| kcen | input-lanjian | 1.465 ± 0.023 | 1.444 | 1.490 | 781.68 ± 59.32 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|