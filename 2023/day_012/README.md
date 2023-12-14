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
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 |
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.12 |
| lanjian | input-kcen | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.12 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.003 | 1.01 ± 0.11 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.005 | 1.31 ± 0.20 |
| mattcl | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.003 | 1.32 ± 0.15 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.006 | 1.32 ± 0.21 |
| mattcl | input-pting | 0.002 ± 0.000 | 0.002 | 0.004 | 1.33 ± 0.16 |
| pting | input-kcen | 0.067 ± 0.001 | 0.064 | 0.070 | 36.05 ± 3.03 |
| pting | input-mattcl | 0.067 ± 0.001 | 0.065 | 0.070 | 36.54 ± 3.05 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.066 | 0.073 | 36.61 ± 3.08 |
| pting | input-pting | 0.069 ± 0.001 | 0.067 | 0.072 | 37.39 ± 3.13 |
| mattcl-py | input-kcen | 0.089 ± 0.001 | 0.087 | 0.091 | 48.27 ± 4.01 |
| mattcl-py | input-lanjian | 0.091 ± 0.001 | 0.088 | 0.093 | 49.04 ± 4.08 |
| mattcl-py | input-mattcl | 0.091 ± 0.001 | 0.089 | 0.094 | 49.30 ± 4.11 |
| mattcl-py | input-pting | 0.093 ± 0.001 | 0.091 | 0.096 | 50.49 ± 4.19 |
| kcen | input-kcen | 1.295 ± 0.006 | 1.290 | 1.302 | 701.11 ± 57.74 |
| kcen | input-pting | 1.315 ± 0.020 | 1.292 | 1.328 | 712.02 ± 59.54 |
| kcen | input-mattcl | 1.422 ± 0.022 | 1.399 | 1.444 | 769.59 ± 64.42 |
| kcen | input-lanjian | 1.475 ± 0.036 | 1.441 | 1.512 | 798.32 ± 68.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|