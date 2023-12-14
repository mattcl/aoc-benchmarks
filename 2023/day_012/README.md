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
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.12 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.005 | 1.29 ± 0.17 |
| mattcl | input-pting | 0.003 ± 0.000 | 0.002 | 0.003 | 1.30 ± 0.15 |
| mattcl | input-mattcl | 0.003 ± 0.000 | 0.002 | 0.005 | 1.32 ± 0.17 |
| mattcl | input-lanjian | 0.003 ± 0.000 | 0.002 | 0.006 | 1.32 ± 0.21 |
| pting | input-kcen | 0.066 ± 0.001 | 0.065 | 0.070 | 34.40 ± 2.84 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.065 | 0.071 | 35.15 ± 2.92 |
| pting | input-pting | 0.069 ± 0.001 | 0.067 | 0.072 | 35.86 ± 2.95 |
| pting | input-mattcl | 0.069 ± 0.006 | 0.066 | 0.100 | 35.89 ± 4.28 |
| mattcl-py | input-kcen | 0.089 ± 0.001 | 0.087 | 0.093 | 46.27 ± 3.83 |
| mattcl-py | input-lanjian | 0.091 ± 0.002 | 0.088 | 0.095 | 47.01 ± 3.90 |
| mattcl-py | input-mattcl | 0.091 ± 0.001 | 0.089 | 0.095 | 47.28 ± 3.90 |
| mattcl-py | input-pting | 0.094 ± 0.001 | 0.091 | 0.096 | 48.54 ± 4.00 |
| kcen | input-kcen | 1.283 ± 0.019 | 1.261 | 1.296 | 664.43 ± 54.88 |
| kcen | input-pting | 1.305 ± 0.019 | 1.286 | 1.323 | 675.86 ± 55.73 |
| kcen | input-mattcl | 1.412 ± 0.016 | 1.395 | 1.427 | 731.43 ± 59.99 |
| kcen | input-lanjian | 1.465 ± 0.011 | 1.454 | 1.476 | 758.62 ± 61.87 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|