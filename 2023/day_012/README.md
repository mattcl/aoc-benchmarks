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
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| lanjian | input-kcen | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.09 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.005 | 1.33 ± 0.17 |
| mattcl | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.003 | 1.34 ± 0.13 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.005 | 1.34 ± 0.19 |
| mattcl | input-pting | 0.003 ± 0.000 | 0.002 | 0.005 | 1.36 ± 0.18 |
| pting | input-kcen | 0.067 ± 0.001 | 0.065 | 0.069 | 36.09 ± 2.19 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.066 | 0.070 | 36.56 ± 2.22 |
| pting | input-mattcl | 0.068 ± 0.001 | 0.066 | 0.071 | 36.98 ± 2.31 |
| pting | input-pting | 0.070 ± 0.001 | 0.067 | 0.073 | 37.74 ± 2.34 |
| mattcl-py | input-kcen | 0.089 ± 0.001 | 0.087 | 0.092 | 48.03 ± 2.91 |
| mattcl-py | input-lanjian | 0.091 ± 0.001 | 0.088 | 0.094 | 49.15 ± 2.98 |
| mattcl-py | input-mattcl | 0.092 ± 0.001 | 0.089 | 0.095 | 49.49 ± 3.01 |
| mattcl-py | input-pting | 0.094 ± 0.001 | 0.091 | 0.098 | 50.97 ± 3.12 |
| kcen | input-kcen | 1.254 ± 0.012 | 1.242 | 1.266 | 677.51 ± 40.59 |
| kcen | input-pting | 1.277 ± 0.014 | 1.263 | 1.292 | 689.89 ± 41.48 |
| kcen | input-mattcl | 1.397 ± 0.002 | 1.394 | 1.399 | 754.44 ± 44.61 |
| kcen | input-lanjian | 1.439 ± 0.019 | 1.421 | 1.458 | 777.50 ± 47.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|