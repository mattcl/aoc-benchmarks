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
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 |
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.09 |
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| lanjian | input-kcen | 0.002 ± 0.000 | 0.002 | 0.003 | 1.00 ± 0.10 |
| mattcl | input-lanjian | 0.003 ± 0.000 | 0.002 | 0.005 | 1.29 ± 0.18 |
| mattcl | input-mattcl | 0.003 ± 0.000 | 0.002 | 0.003 | 1.31 ± 0.12 |
| mattcl | input-kcen | 0.003 ± 0.000 | 0.002 | 0.005 | 1.32 ± 0.15 |
| mattcl | input-pting | 0.003 ± 0.000 | 0.002 | 0.004 | 1.33 ± 0.14 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.066 | 0.072 | 34.78 ± 2.07 |
| pting | input-mattcl | 0.068 ± 0.001 | 0.067 | 0.071 | 34.85 ± 2.03 |
| pting | input-kcen | 0.069 ± 0.009 | 0.065 | 0.115 | 35.33 ± 5.08 |
| pting | input-pting | 0.069 ± 0.001 | 0.067 | 0.071 | 35.39 ± 2.05 |
| mattcl-py | input-lanjian | 0.091 ± 0.001 | 0.088 | 0.093 | 46.37 ± 2.69 |
| mattcl-py | input-mattcl | 0.091 ± 0.001 | 0.089 | 0.094 | 46.72 ± 2.68 |
| mattcl-py | input-kcen | 0.094 ± 0.013 | 0.087 | 0.140 | 47.85 ± 6.94 |
| mattcl-py | input-pting | 0.094 ± 0.002 | 0.091 | 0.098 | 48.05 ± 2.82 |
| kcen | input-kcen | 1.269 ± 0.012 | 1.257 | 1.281 | 648.29 ± 36.98 |
| kcen | input-pting | 1.287 ± 0.018 | 1.272 | 1.307 | 657.31 ± 38.13 |
| kcen | input-mattcl | 1.423 ± 0.026 | 1.393 | 1.440 | 727.01 ± 43.04 |
| kcen | input-lanjian | 1.432 ± 0.031 | 1.410 | 1.467 | 731.29 ± 44.13 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|