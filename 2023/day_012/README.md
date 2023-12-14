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
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.11 |
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.12 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.003 | 1.30 ± 0.15 |
| mattcl | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.005 | 1.31 ± 0.20 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.004 | 1.32 ± 0.17 |
| mattcl | input-pting | 0.002 ± 0.000 | 0.002 | 0.004 | 1.33 ± 0.17 |
| pting | input-kcen | 0.067 ± 0.001 | 0.065 | 0.069 | 35.67 ± 2.96 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.066 | 0.072 | 36.12 ± 3.04 |
| pting | input-mattcl | 0.068 ± 0.001 | 0.066 | 0.070 | 36.31 ± 3.02 |
| pting | input-pting | 0.069 ± 0.001 | 0.068 | 0.073 | 36.99 ± 3.07 |
| mattcl-py | input-kcen | 0.089 ± 0.001 | 0.087 | 0.092 | 47.49 ± 3.94 |
| mattcl-py | input-lanjian | 0.090 ± 0.001 | 0.088 | 0.093 | 48.32 ± 3.99 |
| mattcl-py | input-mattcl | 0.091 ± 0.001 | 0.088 | 0.095 | 48.84 ± 4.06 |
| mattcl-py | input-pting | 0.093 ± 0.001 | 0.091 | 0.095 | 49.76 ± 4.11 |
| kcen | input-kcen | 1.286 ± 0.012 | 1.277 | 1.300 | 688.19 ± 56.54 |
| kcen | input-pting | 1.330 ± 0.038 | 1.287 | 1.362 | 711.76 ± 61.60 |
| kcen | input-mattcl | 1.414 ± 0.023 | 1.388 | 1.434 | 756.65 ± 63.00 |
| kcen | input-lanjian | 1.453 ± 0.017 | 1.438 | 1.472 | 777.43 ± 64.10 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|